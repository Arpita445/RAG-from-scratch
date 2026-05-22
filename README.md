# RAG-from-scratch

<a href="https://colab.research.google.com/drive/1IKpRW_pJi7vKM56px1nhuqqNDSDVA1FI?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="180" height="35">
</a>

---

## 🚀 Project Overview
This repository contains a lightweight, custom **Retrieval-Augmented Generation (RAG)** pipeline built completely from scratch. The system allows an LLM to answer complex user queries by fetching relevant context from a localized knowledge source, ensuring accurate and hallucination-free responses.

### 🧠 Core Features & Tech Stack
* **LLM Engine:** Powered by Google's `gemini-2.5-flash` model for intelligent text generation.
* **Framework:** Built using `langchain` and its ecosystem components (`langchain-google-genai`).
* **Vector Database:** Utilizes `faiss-cpu` for efficient, fast semantic similarity search.
* **Data Processing:** Uses advanced text splitters to segment documentation into readable, optimized chunks.
* **Secure API Handling:** Integrates Google Colab's background Secrets panel to handle private API keys securely.

---
