# LLM-Powered Book Recommender System

An end-to-end book recommendation system that leverages large language models, semantic embeddings, and emotion-aware text analysis to surface relevant and personalized book recommendations from natural language queries. This project combines modern NLP tooling (LangChain, Hugging Face Transformers, vector embeddings) with practical engineering considerations such as efficient batching and document chunking.

![Demo](https://github.com/user-attachments/assets/7fad2954-60a7-4cad-9ebf-fe7965cb9acc)

## Project Overview

The system follows a multi-stage pipeline:

1. Represent books using semantic embeddings derived from their descriptions.
2. Enrich content with emotion-based and genre-aware signals.
3. Retrieve recommendations via semantic similarity, not keyword matching.
4. Support flexible, natural-language queries using LLM-powered retrieval.

## Key Features

- Semantic search over thousands of book descriptions  
- Emotion-aware and genre-aware recommendation signals  
- Efficient transformer inference via batching and input truncation  
- Modular pipeline design using LangChain components  
- Hugging Face–based model integration for classification and embeddings  

## Repository Structure 

```text
├── data/                # Raw and processed book data
├── notebooks/           # Exploration and model implementation
├── gradio_dash.py       # Gradio dashboard for interactive recommendations
├── cover-not-found.jpg  # Placeholder image for books with no cover
├── README.md
