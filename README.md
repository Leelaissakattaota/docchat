# 📑 DocChat: Multi-Agent Document Intelligence

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/IBM%20WatsonX-AI-be95ff?style=for-the-badge&logo=ibm&logoColor=white" alt="WatsonX">
  <img src="https://img.shields.io/badge/Gradio-v4.0-FF5000?style=for-the-badge&logo=gradio&logoColor=white" alt="Gradio">
  <img src="https://img.shields.io/badge/Llama--3.3-70B-04ADFF?style=for-the-badge&logo=meta&logoColor=white" alt="Llama3">
  <img src="https://img.shields.io/badge/License-MIT-44CC11?style=for-the-badge" alt="License">
</p>

**DocChat** is an advanced RAG (Retrieval-Augmented Generation) application that transforms static documents into interactive knowledge bases. By leveraging a multi-agent orchestration layer powered by **IBM WatsonX**, it ensures that every response is verified, cited, and accurate.

---

## 🌟 Key Features

* **📂 Intelligent Parsing**: Deep document understanding for various formats (PDF, DOCX, TXT) with layout preservation.
* **🤖 Multi-Agent Workflow**:
    * **Research Agent**: Scans document chunks to find the most relevant context using high-performance models like `llama-3-3-70b-instruct`.
    * **Verification Agent**: Fact-checks the research output to eliminate hallucinations and ensure alignment with the source text.
* **⚡ Enterprise-Grade Models**: Native support for IBM Granite and Meta Llama 3 architectures.
* **🌐 Real-Time UI**: A sleek, user-friendly **Gradio** interface for seamless document interaction and instant querying.

---

## 🛠️ System Architecture



The system operates on a dual-agent architecture to ensure high-fidelity responses:
1.  **Extraction**: Documents are processed and converted into searchable text chunks.
2.  **Retrieval**: The **Researcher Agent** identifies the most relevant data points within the provided context.
3.  **Validation**: The **Verifier Agent** audits the response for factual accuracy before it is presented in the UI.

---

## 🚀 Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/Leelaissakattaota/docchat.git](https://github.com/Leelaissakattaota/docchat.git)
cd docchat

