# Semantic-search-with-GitHub-issues
This repository provides a semantic search system over the lewtun/github-issues dataset using sentence-transformers/multi-qa-mpnet-base-dot-v1. It allows developers to find the most relevant issue titles, descriptions, and solutions based on query meaning rather than keywords. 
Each issue’s title, body, and comments are combined into a single text and converted into a 768-dimensional embedding. Queries are matched against these embeddings, returning a ranked list of the most relevant results. FAISS is used to enable fast similarity search across the dataset.

