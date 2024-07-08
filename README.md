# RAG-GPT



RAG-GPT is a versatile chatbot utilizing the OpenAI GPT Model, Langchain, ChromaDB, and Gradio to enhance document interaction. It supports functionalities for both pre-processed documents and real-time uploads, allowing users to integrate, process, and summarize PDFs or Docs seamlessly during chat sessions. The interface, built with Gradio, is designed for ease of use, and the model’s memory feature maintains a record of user interactions for personalized responses. Users can adjust settings like the GPT model's temperature to optimize performance and can view retrieved content or associated PDFs directly in the chat interface.



## Features



- Integration and Processing: Supports both pre-processed documents and real-time uploads.
- Document Summarization: Summarize PDFs or Docs seamlessly during chat sessions.
- User-Friendly Interface: Built with Gradio for ease of use.
- Memory Feature: Maintains a record of user interactions for personalized responses.
- Customizable Settings: Adjust GPT model's temperature to optimize performance.
- Content Retrieval: View retrieved content or associated PDFs directly in the chat interface.



## Getting Started



### Prerequisites



Ensure you have the following installed on your local machine:
- Python 3.11
- pip (Python package installer)



### Installation



1. Clone the Repository
```sh
git clone https://github.com/erjonb19/RAG-GPT.git
cd RAG-GPT

2. Install Dependencies
pip install gradio==4.13.0 langchain==0.0.354 openai==0.28.0 chromadb==0.4.22 pypdf==3.17.4 pandas==2.1.4
3. Set Up and Activate Virtual Environment
python3 -m venv projectenv
source projectenv/bin/activate # On macOS/Linux
.\projectenv\Scripts\activate # On Windows
4.**Running the Project**
python src/serve.py
python src/raggpt_app.py
