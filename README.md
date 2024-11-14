# Qdrant-go


## What is Qdrant?
Qdrant is a vector search engine that supports similarity search, nearest neighbor search, and works with data that is represented as vectors. It’s ideal for use cases like recommendation systems, image search, and more.

## What’s in this Repo?
In this repository, I will demonstrate different challenges and examples using Qdrant.

## Deploy Qdrant

Deploy a single-node setup using docker:

```bash
docker pull qdrant/qdrant
docker run -p 6333:6333 -p 6334:6334 qdrant/qdrant
```