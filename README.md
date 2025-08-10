# 🚀 Multi-Document RAG Orchestrator

A lightning-fast, AI-powered system for extracting, chunking, embedding, and querying multiple document types—powered by **LangChain**, **Azure OpenAI**, and **Qdrant**.

---

## 🚀 How to Run

### 🐳 Run with Docker (Zero Setup Vibes)
```bash
docker build -t multi-doc-rag .
docker run --rm -it \
    -e AZURE_OPENAI_CHAT_ENDPOINT=your_value \
    -e AZURE_OPENAI_CHAT_API_KEY=your_value \
    -e AZURE_OPENAI_EMB_ENDPOINT=your_value \
    -e AZURE_OPENAI_EMB_API_KEY=your_value \
    -e QDRANT_URL=your_value \
    -e QDRANT_API_KEY=your_value \
    multi-doc-rag
