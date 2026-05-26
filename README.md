# Omni 🌌

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://t6jfcj3dumhrs8jqthynpl.streamlit.app/)

Omni is a lightweight, local-first vector ingestion and parsing engine...

Omni is a lightweight, local-first vector ingestion and parsing web application built using **Streamlit**. It manages, processes, and flushes document metadata seamlessly before embedding data chunks into a vector store, ensuring your live application remains perfectly synchronized without data duplication.

🚀 **Live App:** [https://t6jfcj3dumhrs8jqthynpl.streamlit.app/](https://t6jfcj3dumhrs8jqthynpl.streamlit.app/)

---

## 🚀 Features

- **Streamlit Web UI**: Easy drag-and-drop document upload and vector parsing directly from your browser.
- **Metadata Management**: Tracks file parsing histories, schemas, and processing loops using an automated SQLite metadata catalog (`document_metadata`).
- **Idempotent Vector Uploads**: Cleanly purges or replaces existing document records prior to fresh indexing runs to avoid vector dilution.
- **Deployment-Ready**: Optimized to run smoothly on local environments and serverless platforms.

---

## 🛠️ Tech Stack

* **Frontend/UI:** Streamlit
* **Language:** Python 3.10+
* **Database ORM:** SQLAlchemy
* **Database Engine:** SQLite (File-based)
* **Vector Architecture:** [e.g., LangChain / LlamaIndex / ChromaDB]

---

## 💾 Installation & Local Setup

To run Omni locally on your machine:

```bash
# Clone the repository
git clone [https://github.com/sinanmuhammedsk/omni.git](https://github.com/sinanmuhammedsk/omni.git)
cd omni

# Install dependencies
pip install -r requirements.txt

# Launch the Streamlit application
streamlit run app.py

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

