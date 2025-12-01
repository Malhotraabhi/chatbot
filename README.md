PDF RAG Chatbot with LangGraph, Gemini & Streamlit

A fully functional PDF Question-Answering Chatbot built using:

LangGraph – for building controllable AI workflows

Google Gemini Flash (Gemini 2.5) – as the main LLM

FAISS – for fast and accurate PDF vector search

Streamlit – for a clean, chat-like UI

SQLite Checkpointing – for persistent chat history

DuckDuckGo Search + Calculator Tools – for live search & numeric reasoning

This chatbot allows users to:

✅ Upload PDFs
✅ Ask questions about the PDF
✅ Use built-in tools (calculator, web search)
✅ Maintain multiple chat threads
✅ Resume conversations with saved context
✅ Get accurate answers powered by Retrieval-Augmented Generation (RAG)
🚀 Features
🔍 PDF Ingestion

Splits large PDFs into chunks

Creates embeddings using Gemini Embeddings

Stores vectors in FAISS

Thread-specific vector databases

🤖 Intelligent Chat Flow (LangGraph)

LLM node → decides how to answer

Tool node → executes calculator/search/RAG

Automatic tool-calling

Persistent memory using SQLite checkpoints

📚 RAG Tool

Retrieves the most relevant pages from the uploaded PDF

Provides context to Gemini

Enables accurate PDF-based responses

🌐 Integrated Tools

🔎 DuckDuckGo Web Search

➗ Calculator (add, subtract, multiply, divide)

📄 PDF Retrieval (custom RAG tool)

💬 Streamlit Chat UI

Clean, modern chat interface

Multiple chat threads

PDF upload panel

Real-time responses
