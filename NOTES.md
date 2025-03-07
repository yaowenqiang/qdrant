# Vector Databases

+ Data is not stored in structured tables
+ Optmized for numeric data storage and retrieval
+ Vector indexing
+ Query the similar vectors
+ Frequently used in ML and AI applications

Vector embeddings


Searching vectors

euclidean(欧几里得)

> Distance between two vectors, smaller the distance, similar the vecgors are

cosine

> Cosine of the angle between two vectors.Larger the value, similar the vectors are.


dot product

> the dot product, also called scalar product, is a measure of how closely two vectors align, in terms of the directions they point .Larger the value, similar the vectors are



> pip install qdrant-client jupyterlab numpy requests tensorflow tensorflow-hub tiktoken


## collections

+ vectors
  + Named Vectors
  + Unnamed Vectors
+ Payload
  + Integer
  + Float
  + Bool
  + Keyword
  + Geo
+ Distance metrics
  + Cosine
  + Dot
  + Euclidean
  + Manhattan

```
docker run -p 6333:6333 -p 6334:6334 \ 
-v "$(pwd)/qdrant_storage:/qdrant/storage:z" \ 
qdrant/qdrant

```
