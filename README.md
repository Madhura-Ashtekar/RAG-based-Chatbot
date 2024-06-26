# RAG-based-Chatbot

This project involves the development of a chatbot leveraging Retrieval-Augmented Generation (RAG) to provide contextually relevant responses. The chatbot uses OpenAI's GPT-3.5 for generative responses and is integrated with Streamlit for a user-friendly interface. The project focuses on the seminal paper "Attention Is All You Need" to demonstrate the practical application of Transformer models.

Introduction:

This chatbot is designed to retrieve relevant information from a given document (in this case, the "Attention Is All You Need" paper) and provide accurate and contextually relevant responses using OpenAI's GPT-3.5 model. The integration with Streamlit ensures a seamless and interactive user experience.

Features:

Retrieval-Augmented Generation: Combines retrieval-based and generative approaches for accurate responses.
Transformer Model Application: Demonstrates the practical use of Transformer models based on the "Attention Is All You Need" paper.
User-Friendly Interface: Utilizes Streamlit for an intuitive and interactive user experience.
Efficient Information Retrieval: Implements a retrieval mechanism to fetch relevant information from the document.

The pdf version of the .ipynb covers the following steps:

Data Ingestion: Load text data from different sources (text files, web pages, PDFs) using langchain_community document loaders.

Environment Setup: Load the OpenAI API key from environment variables using dotenv.

Web-Based Loader: Load and index content from specified HTML pages.

PDF Loader: Load content from a PDF file, specifically the "Attention Is All You Need" paper.

Text Splitting: Split documents into manageable chunks using RecursiveCharacterTextSplitter.

Vector Embedding and Vector Store: Embed documents into vectors using OpenAIEmbeddings and store them in a Chroma vector store.

FAISS Vector Database: Create and query a FAISS vector store from the documents.

Language Model Loading: Load the llama2 model using Ollama.

ChatPrompt Template Design: Design a chat prompt template for generating responses.
