
# Groq Document Chatbot Q&A

## Overview

The Groq Document Chatbot Q&A is a Streamlit-based web application designed to answer questions based on documents loaded from a specified directory. Utilizing advanced language processing and AI technologies, this application provides accurate responses to user queries by leveraging the power of Google Generative AI Embeddings and FAISS for efficient similarity search among document embeddings.

## Features

- **Document Processing**: Automatically processes PDF documents from a specified directory to extract text content.
- **Question Answering**: Provides answers to user queries based on the processed documents.
- **Efficient Search**: Uses FAISS to perform fast similarity searches among document embeddings for relevant information retrieval.
- **User-Friendly Interface**: Built with Streamlit, offering an intuitive interface for users to input their questions and receive answers.

## Dependencies

- Python 3.x
- Streamlit
- Langchain-Groq
- PyPDF2
- Faiss-CPU
- Langchain-Google-GenAI
- Dotenv
- Langchain-Community

Ensure all dependencies are installed by running `pip install -r requirements.txt`.

## Setup

1. Clone the repository: `git clone https://your-repository-url.git`
2. Navigate to the project directory: `cd Groq-Document-Chatbot-QA`
3. Install the dependencies: `pip install -r requirements.txt`
4. Set up environment variables (`GROQ_API_KEY`, `GOOGLE_API_KEY`) in a `.env` file or directly in your system's environment variables.
5. Run the application: `streamlit run app.py`

## Usage

Upon launching the application, you will be greeted with a simple interface where you can enter your question. After submitting your question, the application will process the query against the loaded documents and display the most relevant answer.

## Contributing

Contributions are welcome If you find a bug or have a feature request, please open an issue on GitHub.

## License

[Insert License Here]
