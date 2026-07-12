# Semantic Search using TF-IDF, Sentence Transformers, and FAISS

## Project Overview

This project demonstrates multiple approaches for semantic document retrieval using a collection of machine learning research papers from arXiv. The notebook compares traditional text vectorization methods with modern embedding-based semantic search techniques to identify the most relevant research papers for a user query.

The project illustrates the evolution of semantic search from keyword-based representations to dense vector embeddings and efficient similarity search using FAISS.

---

## Project Objectives

- Compare traditional and modern semantic search techniques.
- Implement Bag-of-Words and Term Frequency–Inverse Document Frequency (TF-IDF) vectorization.
- Generate semantic embeddings using Sentence Transformers.
- Build a FAISS vector index for efficient nearest-neighbor search.
- Retrieve the most relevant research papers using natural language queries.

---

## Project Workflow

```text
Research Paper Collection
          │
          ▼
Text Preprocessing
          │
          ▼
Bag-of-Words
          │
          ▼
TF-IDF
          │
          ▼
Sentence Transformer Embeddings
          │
          ▼
FAISS Vector Index
          │
          ▼
Semantic Similarity Search
          │
          ▼
Retrieve Most Relevant Papers
```

---

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- Sentence Transformers
- FAISS
- Cosine Similarity

---

## Skills Demonstrated

- Natural Language Processing (NLP)
- Semantic Search
- Document Similarity
- Vector Embeddings
- Sentence Transformers
- FAISS Vector Database
- Information Retrieval
- Feature Engineering

---

## Key Features

- Compared **Bag-of-Words** and **TF-IDF** vectorization methods.
- Generated dense semantic embeddings using **Sentence Transformers**.
- Built a **FAISS** vector database for efficient similarity search.
- Retrieved the most semantically relevant research papers from natural language queries.
- Demonstrated the progression from traditional keyword-based retrieval to modern embedding-based semantic search.

---

## Repository Contents

```text
├── README.md
├── data/
│   └── arxiv_papers.csv
└── notebooks/
    └── Semantic_Search_FAISS.ipynb
```

---

## Future Improvements

- Compare multiple embedding models.
- Evaluate retrieval performance using benchmark metrics.
- Explore hybrid keyword and semantic search.
- Integrate the semantic search pipeline into a Retrieval-Augmented Generation (RAG) application.

---

**Author:** Sivaraja Vaithiyalingam