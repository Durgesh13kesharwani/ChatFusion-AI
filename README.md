# ChatFusion-AI

ChatFusion-AI is an advanced AI assistant that combines conversational chatbot functionality with document-based question answering. The project leverages LangChain, Hugging Face, and ChromaDB technologies, providing an all-in-one solution for context-aware conversations and PDF-based queries.

## Features

- **Conversational AI Assistant**: Engage in meaningful, context-aware conversations with memory support.
- **Document-Based Q&A**: Upload PDF files and ask questions to retrieve insights directly from their content.
- **Customizable AI Models**: Use Hugging Face models for embeddings and language generation.
- **Efficient Retrieval**: Employ ChromaDB for quick and accurate document embedding search.

## Repository Structure

- `ChatFusion-AI.ipynb`: Jupyter Notebook containing the complete code for the chatbot and ChatPDF functionalities.

## Installation

### Prerequisites

- Python 3.10 or above
- Jupyter Notebook installed (`pip install notebook`)
- Hugging Face API key

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Durgesh13kesharwani/ChatFusion-AI.git
   cd ChatFusion-AI

2. Install dependencies:
   pip install -r requirements.txt

3. Set your Hugging Face API key:
   import os
   os.environ['HUGGINGFACEHUB_API_TOKEN'] = "your_api_key"

4. Open the Notebook:
   jupyter notebook ChatFusion-AI.ipynb


# Usage
Run the Notebook: Open the ChatFusion-AI.ipynb file in Jupyter Notebook and execute the cells sequentially.
Conversational AI: Use the chatbot functionality to engage in context-aware conversations.
PDF Q&A:
Provide the path to a PDF file when prompted.
Ask questions related to the content of the PDF and get accurate responses.

# Future Enhancements
Support for multiple file formats (e.g., Word, Excel).
Deployment as a web app using frameworks like Streamlit or Flask.
Integration with cloud services for real-time performance.

# Acknowledgments
LangChain
Hugging Face
ChromaDB

# Contribute
We welcome contributions! Submit issues or pull requests to improve ChatFusion-AI.
