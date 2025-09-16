# IR-Search-Engine

An end-to-end **Information Retrieval (IR) system** implemented in Python.  
This project brings together classical IR techniques and machine learning methods to demonstrate how search, ranking, and recommendation systems can be built from the ground up.

## 🚀 Features

- **Indexing**
  - Inverted Index with Delta Encoding for efficient storage and fast lookups.
  - Statistics: term frequency, unique tokens, collection size.
  - Validation of Zipf’s Law through visualization.

- **Ranking Models**
  - Vector Space Model (VSM) with cosine similarity.
  - Okapi BM25.
  - Query Likelihood Model with Jelinek-Mercer smoothing.
  - Evaluation using **P@k, R@k, MAP@k, and NDCG@k**.

- **Relevance Feedback**
  - RM1 and RM3 models for query expansion.
  - Improved retrieval results by blending original queries with feedback terms.

- **Keyword Extraction**
  - **TextRank algorithm** for unsupervised keyword extraction.
  - Graph-based approach inspired by Google PageRank.

- **Clustering**
  - K-Means clustering on TF-IDF vectors.
  - Intra-cluster and inter-cluster similarity evaluation.

- **Recommender System**
  - Collaborative filtering with **matrix factorization**.
  - Trained on MovieLens 100K dataset using TensorFlow.
  - Addressed challenges like **cold-start problem** and popularity bias.

