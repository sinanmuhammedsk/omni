# Omni 🌌

Omni is a lightweight, local-first vector ingestion and parsing engine. It is designed to manage, process, and clear document metadata seamlessly before embedding chunks into a vector store, preventing redundant indexing and stale data.

## 🚀 Features

- **Document Parsing & Chunking**: Effortlessly parse multi-format documents for LLM and RAG applications.
- **Metadata Management**: Tracks file hashes, processing history, and vector storage indexing using an automated SQLite metadata catalog (`document_metadata`).
- **Idempotent Vector Uploads**: Automatically flushes or replaces existing document chunks before fresh uploads to avoid data duplication.
- **Local-first Architecture**: Minimal configuration required with file-based persistence.

---

## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **Database ORM:** SQLAlchemy
* **Database Engine:** SQLite (File-based)
* **Vector Pipeline Integration:** [e.g., LangChain / LlamaIndex / ChromaDB]

---

## 💾 Installation

Clone the repository and install the required dependencies:

```bash
git clone [https://github.com/sinanmuhammedsk/omni.git](https://github.com/sinanmuhammedsk/omni.git)
cd omni
pip install -r requirements.txt

