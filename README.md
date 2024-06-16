# Rag_gemini_chatbot

This project is a Streamlit-based application that provides a Q&A interface using Geini's generative AI models. It processes documents to answer user queries based on the content of those documents. The application leverages several components from the LangChain library to handle text splitting, prompting, and document retrieval.

## Features

- **Document-Based Q&A**: Answers user questions based on the context provided by uploaded documents.
- **Streamlit Interface**: Simple and interactive web application interface.
- **Integration with Groq AI**: Utilizes Groq's generative AI models for processing and answering queries.
- **Vector Storage with FAISS**: Efficiently retrieves relevant document sections using FAISS vector storage.
- **Environment Configuration**: Uses environment variables for API keys and configuration settings.

## Prerequisites

- Python 3.8+
- Streamlit
- LangChain library
- FAISS
- dotenv

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/groq-document-chatbot.git
   cd groq-document-chatbot

 
