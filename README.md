# FAISS_Example

I am demonstrating a use case in which I provide a curated list of content spanning multiple categories. Using the FAISS library for efficient similarity search and SentenceTransformers for embedding-based text representations, I ask targeted questions to retrieve relevant answers directly from the provided text.

Library Reference: https://faiss.ai/

Facebook AI Similarity Search (FAISS) is an open-source library that allows developers to: 
- Search for similar embeddings in multimedia documents
- Cluster dense vectors
- Build an index and perform searches quickly and efficiently
- Find visually similar images or semantically similar text within a large dataset
- FAISS is implemented in C++
- Algorithms that search in sets of vectors of any size
- Supporting code for evaluation and parameter tuning
- Methods that use a compressed representation of the vectors
- Methods that add an indexing structure on top of the raw vectors
- You can index a set of vectors using FAISS, and then search for the most similar vectors within the index using another vector.

Faiss is built around an index type that stores a set of vectors, and provides a function to search in them with L2 and/or dot product vector comparison. Some index types are simple baselines, such as exact search. Most of the available indexing structures correspond to various trade-offs with respect to

- search time
- search quality
- memory used per index vector
- training time
- adding time
- need for external data for unsupervised training
