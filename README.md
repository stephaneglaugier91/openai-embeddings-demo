# 📚 Vector Search with OpenAI Embeddings & PostgreSQL

This project demonstrates how to generate vector embeddings using OpenAI's `text-embedding-3-small` model, store them in a PostgreSQL database with the `pgvector` extension, and perform semantic search queries on the data.


## 🔧 Features

* Load and preprocess text data from a JSON file
* Generate OpenAI embeddings for each document
* Store the data and embeddings in PostgreSQL using `pgvector`
* Perform vector similarity searches using `<=>` (Euclidean distance)
* Basic search example with OpenAI-generated query embedding
