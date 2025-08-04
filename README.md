# Retrieval-Augmented-Generation-RAG-System-with-BBC-News-Data





This project demonstrates a basic Retrieval-Augmented Generation (RAG) system using the 2024 BBC News dataset to enable a language model (LLaMA 3) to answer queries with up-to-date context. It retrieves relevant news items and augments the LLM prompt with factual information for improved output quality.

## Features
- Uses vector-based retrieval to fetch top-k relevant news headlines.
- Formats and injects context into LLM prompts.
- Compares responses from standard LLM vs. RAG-enhanced generation.
- Built for education and demonstration of RAG workflows.

## Technologies
- Python, Jupyter Notebook
- LLaMA-3-Instruct-Turbo (via Together AI)
- FAISS / semantic search
- Prompt Engineering
- Pandas, Numpy

## Usage
1. Clone the repo
2. Download the [News Headlines 2024](https://www.kaggle.com/datasets/dylanjcastillo/news-headlines-2024) dataset
3. Install dependencies:
```bash
pip install -r requirements.txt
