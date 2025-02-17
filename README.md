RAG Chatbot
Fast-Food Customer Segmentation Chatbot

This project builds a Retrieval-Augmented Generation (RAG) Chatbot for customer segmentation analysis in a fast-food chain using Google Gemini API. The chatbot retrieves relevant information from synthetic reports stored in ChromaDB and generates responses using Gemini LLM.

🚀 Features:
Segment-Based Analysis: Generates insights for different customer segments.

Retrieval-Augmented Generation (RAG): Uses ChromaDB for vector storage and retrieval.

Google Gemini API: Generates responses using a powerful LLM.

Streamlit UI: Provides an interactive chatbot interface.

ngrok Integration: Makes the chatbot accessible via a public URL.



🛠️ Tech Stack:
LLM API: Google Gemini

Vector DB: ChromaDB

Embeddings: Sentence-Transformers

Backend: FastAPI / Flask (Optional)

Frontend: Streamlit

Orchestration: LangChain (Optional)

Deployment: Google Colab, ngrok


🔑 Setup Google Gemini API

Obtain an API key from Google AI

Set up the key in app.py:
import google.generativeai as genai
GENAI_API_KEY = "your-gemini-api-key"
genai.configure(api_key=GENAI_API_KEY)

Also need an Auth token for ngrok

