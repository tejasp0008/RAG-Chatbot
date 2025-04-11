# RAG Chatbot with Langchain and HuggingFace 🦜🔗🤗

## Developed by Tejas Pal

Retrieval Augmented Generation (RAG) Chatbot using Langchain 🦜🔗 and HuggingFace 🤗

## Overview

Retrieval Augmented Generation (RAG) enhances response generation by combining pre-trained Large Language Models (LLMs) with custom data. This approach integrates dense retrieval models with sequence-to-sequence transformers, ensuring that generated responses are both contextually relevant and knowledge-rich. The RAG model first retrieves relevant documents, processes them through an LLM, and then generates informed responses by combining both pre-trained knowledge and custom data insights.

## Getting Started

### Environment Setup

Set up your virtual environment:

```bash
virtualenv venv
source venv/bin/activate
```

Create a `.env` file and add your Hugging Face API key:

```bash
HF_TOKEN=your_huggingface_api_key
```

### Install Dependencies

Install the necessary dependencies:

```bash
pip install -r requirements.txt
```

### Run the Application

Start the chatbot application:

```bash
gradio app.py
```

This will launch the web-based chatbot interface, allowing real-time interaction with the RAG model.

## Usage

Once the application is running, you can interact with the chatbot through the web interface, where it will generate responses based on both pre-trained knowledge and retrieved documents.

## Additional Resources

- Try out the chatbot on [![Hugging Face Spaces](https://img.shields.io/badge/🤗%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/mca183/retrieval-augmented-generation-langchain)
- Learn more about the [Databricks-Dolly-15K dataset](https://huggingface.co/datasets/databricks/databricks-dolly-15k)
- Explore the [Dynamic-TinyBERT model](https://huggingface.co/Intel/dynamic_tinybert)
- Discover the [Sentence-Transformers (all-MiniLM-L6-v2) model](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)

---

This guide provides everything needed to set up and run a RAG chatbot using Langchain and Hugging Face. 🚀

