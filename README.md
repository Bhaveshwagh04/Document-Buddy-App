# Document-Buddy-App
![alt text](image.png)


Document Buddy App is a powerful Streamlit-based application designed to simplify document management. Upload your PDF documents, create embeddings for efficient retrieval, and interact with your documents through an intelligent chatbot interface. 🚀

## 🛠️ Features

- 📂 Upload Documents: Easily upload and preview your PDF documents within the app.
- 🧠 Create Embeddings: Generate embeddings for your documents to enable efficient search and retrieval.
- 🤖 Chatbot Interface: Interact with your documents using a smart chatbot that leverages the created embeddings.
- 📧 Contact: Get in touch with the developer or contribute to the project on GitHub.
- 🌟 User-Friendly Interface: Enjoy a sleek and intuitive UI with emojis and responsive design for enhanced user experience.

## 🖥️ Tech Stack

The Document Buddy App leverages a combination of cutting-edge technologies to deliver a seamless and efficient user experience. Here's a breakdown of the technologies and tools used:

- `LangChain`: Utilized as the orchestration framework to manage the flow between different components, including embeddings creation, vector storage, and chatbot interactions.

- `Unstructured`: Employed for robust PDF processing, enabling the extraction and preprocessing of text from uploaded PDF documents.

- `BGE Embeddings from HuggingFace`: Used to generate high-quality embeddings for the processed documents, facilitating effective semantic search and retrieval.

- `Qdrant`: A vector database running locally via Docker, responsible for storing and managing the generated embeddings for fast and scalable retrieval.

- `LLaMA 3.2 via Ollama`: Integrated as the local language model to power the chatbot, providing intelligent and context-aware responses based on the document embeddings.

- `Streamlit`: The core framework for building the interactive web application, offering an intuitive interface for users to upload documents, create embeddings, and interact with the chatbot.

## 📁 Directory Structure

document_buddy_app/ │ ├── app.py ├── vectors.py ├── chatbot.py ├── requirements.txt

## 🚀 Getting Started

Follow these instructions to set up and run the Document Buddy App on your local machine.

### 1. Clone the Repository

# # How to run?

# STEPS:

- Clone the repository
Project repo: https://github.com/

# STEP 01- Create a conda environment after opening the repository
```bash
conda create -n document python=3.10 -y
```
```bash
conda activate document
```
# STEP 02- install the requirement
```bash
pip install -r requirements.txt
```
# STEP 03 - Run the App

```bash
streamlit run app.py
```

## 📝 Usage
1. Home: Get an overview of the app and its functionalities.
2. Chatbot: • Column 1: Upload a PDF document and preview it within the app. • Column 2: Create embeddings for the uploaded document. This process enables efficient search and retrieval. • Column 3: Interact with the chatbot by asking questions related to your uploaded 
3. document. The chatbot leverages the created embeddings to provide accurate and context-aware responses.
4. Contact: Find the developer’s contact information and contribute to the project on GitHub.