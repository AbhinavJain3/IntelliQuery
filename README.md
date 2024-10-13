# IntelliQuery – AI-Powered PDF Knowledge Extraction

**IntelliQuery** is an advanced Retrieval-Augmented Generation (RAG) system designed to provide accurate, context-aware answers to queries based on content from large PDF files. Built using Pinecone for efficient vector-based search and Google Gemini API for generating human-like responses, IntelliQuery offers a smart solution for extracting and presenting relevant information from NCERT PDF texts.

---

## 🚀 Features

- **Intelligent Query Resolution**: Extracts relevant answers from NCERT PDF files using advanced vector search techniques.
- **Seamless Integration**: Combines Pinecone’s vector database with Google Gemini API to deliver natural language responses.
- **Real-time Results**: Responds to queries instantly, providing relevant information from a large corpus.
- **FastAPI Backend**: Served through FastAPI for efficient and scalable API integration.
- **Optimized for Educational Use**: Perfect for knowledge retrieval from structured academic resources like NCERT.

---

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Database**: Pinecone (Vector Search)
- **API**: Google Gemini API for Natural Language Processing
- **Backend Framework**: FastAPI
- **Deployment**: Google Colab

---

## 📂 Setup and Installation

Follow these steps to run the IntelliQuery project on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AbhinavJain3/IntelliQuery.git
   cd IntelliQuery
   ```

2. **Install Required Libraries**:
   Install all dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Pinecone**:
   - Sign up at [Pinecone.io](https://www.pinecone.io) and create an API key.
   - Set up a vector index with the relevant embeddings.

4. **Configure Google Gemini API**:
   - Use the `google-generativeai` package to interact with the Google Gemini API.
   - Store your API key as an environment variable `API_KEY` in Colab or your environment.


## 🧑‍💻 Colab Notebook

To try out IntelliQuery directly in Google Colab, use the link below:

[Run in Colab](https://colab.research.google.com/github/AbhinavJain3/IntelliQuery/IntelliQuery.ipynb)

---

## 📝 Future Enhancements

- **Multi-Language Support**: Adding NLP support for multiple languages.
- **Improved Frontend**: Develop a user-friendly interface to interact with the system.
- **Advanced PDF Parsing**: Implementing more efficient parsing techniques for complex PDFs.
- **Expanded Dataset**: Integrating more diverse and extensive academic resources beyond NCERT.

