# GenAI / RAG Data Pipeline — Embeddings, Vector Databases & MLflow Features

The data engineering layer for generative AI: pipelines that parse, cleanse and chunk unstructured clinical documentation and financial filings/news, de-identify PHI, generate embeddings and load a vector database for LLM-powered search and summarization. A companion PySpark feature-engineering pipeline, tracked in MLflow, builds model-ready features such as those used for readmission-risk modeling. All documents and data are synthetic.

**Tech stack:** Python • PySpark • RAG • Embeddings • Vector Databases • MLflow

## Architecture Overview
Unstructured documents → parse & cleanse → PHI de-identification → chunking → embeddings → vector database (for LLM retrieval); in parallel: structured data → PySpark feature pipelines → MLflow-tracked feature sets.

## Project Structure
`ingest/, chunking/, embeddings/, vector_store/, features/`

## How to Run
Place synthetic sample documents in ingest/, run chunking and embeddings steps, load the vector store, then query it with a sample question to see retrieved context.

## Skills Demonstrated
Python, PySpark, Retrieval-Augmented Generation (RAG), LLM Integration, Embeddings, Vector Databases, Document Chunking, PHI De-identification, Feature Engineering, MLflow

## Notes
Portfolio project built on **synthetic data only** — real production engineering patterns from healthcare and financial services data engineering, with no real patient, customer, or market data, and no employer-confidential code or data.

---
*By Sreya Peddu — Senior Data Engineer, Dallas–Fort Worth, TX • peddusreya02@gmail.com • [LinkedIn](https://www.linkedin.com/in/sreyapeddu)*
