# Conversation Management & Classification using Groq API

This project implements a comprehensive conversation management system with summarization capabilities and a classification module using the Groq API. The system demonstrates advanced techniques for managing conversational data, performing periodic summarization, and classifying user inputs with structured extraction.

**Features**

- **Task 1: Conversation Management with Summarization**
- Dynamic Conversation History: Maintains a running conversation history between user and assistant
- Periodic Summarization: Automatically summarizes conversations after a configurable number of turns
- Flexible Truncation Options: Supports truncation by:
- Number of conversation turns
- Character length limits
- Word count limits
- Real-time API Integration: Uses Groq's OpenAI-compatible API for both conversation and summarization

- **Task 2: User Chat Classification**
- Structured Data Extraction: Classifies user messages into predefined categories
- JSON Schema Compliance: Ensures extracted data follows specified JSON schemas
- Intent Recognition: Identifies user intent and extracts relevant entities
- Multi-category Classification: Supports classification across multiple domains

-**Technical Implementation**

- Groq API: For all LLM interactions using OpenAI-compatible SDK
- Python: Core implementation without external frameworks
- Object-Oriented Design: Modular architecture with separate managers for conversation and classification
- Error Handling: Robust exception handling for API interactions

Installation
clone this git repo and ensure your own Groq api key is embedded under Notebook secret key section in name GROQ_API_KEY
