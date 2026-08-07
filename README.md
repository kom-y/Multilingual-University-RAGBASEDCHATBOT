# Multilingual-University-Chatbot
# Introduction:
University RAG Chatbot is a Retrieval-Augmented Generation (RAG) chatbot that answers university-related queries using data scraped from the official websites of FAST-NUCES, NED University, IBA Karachi, and MAJU. The project uses Python, FastAPI, FAISS, multilingual E5 and MiniLM embedding models, and a local LLM via Ollama to provide accurate, context-aware responses. Character-based chunking and semantic retrieval were implemented to improve search quality. Performance evaluation showed that the multilingual E5 embeddings achieved higher retrieval accuracy than MiniLM, while RAG significantly reduced hallucinations and generated more reliable university-specific answers.
## 📋 Requirements

### Software
- Python 3.10+
- FastAPI
- Ollama
- FAISS
- BeautifulSoups
- Requests

### Python Packages

```bash
pip install fastapi uvicorn faiss-cpu langchain langchain-community sentence-transformers transformers torch beautifulsoup4 requests numpy pandas
```

Or install from `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Embedding Models

- `intfloat/multilingual-e5-large`
- `sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2`

### Dataset

The chatbot uses data scraped from the official websites of:

- FAST-NUCES
- NED University
- IBA Karachi
- Mohammad Ali Jinnah University (MAJU)

- GPU (Optional)

