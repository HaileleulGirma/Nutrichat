# 🥗 NutriChat — A RAG-Powered Nutrition Assistant Chatbot
An AI-powered chatbot that answers questions about nutrition using information from uploaded documents. Built with LangChain, FastAPI, Streamlit, and a local vector database.

---

## 💡 Features

- 🔍 Retrieval-Augmented Generation (RAG) with LangChain
- 🧠 OpenAI-powered natural language conversations
- 🧠 Open-source Hugging Face embedding model for vectorization
- 📄 Upload and delete custom PDF documents
- 📚 Comes with 3 preloaded nutrition PDFs
- 🌐 Streamlit frontend for interactive Q&A
- ⚙️ FastAPI backend for document processing

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/nutrichat.git
cd nutrichat
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Set API keys

Create a `.env` file in the root directory with the following:

```env
OPENAI_API_KEY=your-openai-api-key
HUGGINGFACEHUB_API_TOKEN=your-huggingface-api-token
```

### 4. Run the application

Start the backend:

```bash
cd api
uvicorn main:app --reload
```

Then start the frontend:

```bash
cd ../app
streamlit run app.py
```

---

## 🛠 Built With

* LangChain
* ChromaDB
* FastAPI
* Streamlit
* OpenAI
* Hugging Face

---

## 📚 PDF Management

* Upload private documents via the frontend
* Delete existing PDFs as needed
* Current vector store includes 3 preloaded nutrition documents

---

## 🙋‍♀️ Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you want to add.

---

## 📜 License

MIT License

---

## 🌟 Acknowledgements

Built with LangChain and open-source tools to support document-based QA in the health and nutrition space.

```

Let me know if you'd like badges, screenshots, or a project tagline at the top.
```
