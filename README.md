# ContextualRAG

**ContextualRAG** is an advanced Retrieval-Augmented Generation (RAG) system that improves upon traditional RAG by incorporating *context-aware retrieval* and *ranking*. This approach is designed for applications that require precise, context-sensitive answers across multi-turn conversations or documents.

---

## 🚀 What is ContextualRAG?

ContextualRAG enhances the standard RAG pipeline by embedding **conversational or semantic context** into the retrieval process. While normal RAG retrieves passages purely based on the latest query, ContextualRAG takes into account the full context (such as previous conversation turns or document history). This leads to more accurate and coherent responses.

---

## 🔍 How is it Different from Conventional RAG?

| Feature | Conventional RAG | ContextualRAG |
|--------|------------------|----------------|
| Retrieval Basis | Latest query only | Full conversation or semantic context |
| Ranking | Basic similarity match | Ranks based on contextual relevance |
| Accuracy | May miss intent | Higher due to context tracking |
| Ideal For | FAQ bots, short queries | Multi-turn chat, document Q&A |

---

## 🧠 Why and When to Use ContextualRAG?

Use ContextualRAG when:
- You want a chatbot that understands ongoing conversations.
- The user's query depends on past turns or previous content.
- You’re building a document Q&A system where context influences the answer.

Benefits:
- Improved relevance and user satisfaction.
- Better understanding of nuanced or ambiguous queries.
- Smoother conversational experience.

---

## 📦 Installation

```bash
git clone https://github.com/RishulGupta/ContextualRAG.git
cd ContextualRAG
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
```

---


