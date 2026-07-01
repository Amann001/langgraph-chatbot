# LangGraph Chatbot

A conversational AI chatbot built using LangGraph, LangChain, Groq, and Streamlit.

## Features

- Interactive Streamlit chat interface
- LangGraph-powered backend
- Groq LLM integration
- Conversation memory
- MemorySaver persistence
- Multi-turn conversations
- Real-time token streaming
- Resume previous chats using thread IDs
- Multiple conversation support
- SQLite-backed conversation persistence
- Resume previous conversations from database
- Automatic thread management
- Persistent chat history across application restarts
- Backend/frontend separation

## Tech Stack

- Python
- LangGraph
- LangChain
- Groq
- Streamlit

## Project Structure
- langgraph_backend.py
- streamlit_frontend.py
- streamlit_frontend_streaming.py
- streamlit_frontend_threading.py
- streamlit_frontend_database.py
- streamlit_backend_database.py
- requirements.txt
- README.md

## Chat Capabilities

- Start a new conversation
- Resume an existing conversation
- Stream responses in real time
- Maintain conversation memory
- Manage multiple chat sessions using unique thread IDs

## Persistence

The chatbot stores conversations using SQLite through LangGraph checkpointing.

### Benefits

- Persistent conversation history
- Resume chats after restarting the application
- Multiple independent conversations
- Thread-based retrieval

## Development Progress

### Version 1
Basic chatbot

### Version 2
Conversation memory

### Version 3
Streaming responses

### Version 4
Resume previous conversations

### Version 5
SQLite database integration