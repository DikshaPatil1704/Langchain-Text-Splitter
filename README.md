# LangChain Text Splitters

This repository demonstrates different types of **text splitters in LangChain**.  
Text splitters are used to break large text or documents into smaller chunks for
LLMs, embeddings, and RAG (Retrieval-Augmented Generation) pipelines.

---

## 📂 Included Splitters

### 1️⃣ Semantic Splitter
- Uses **embeddings** to split text based on **meaning**
- Best for RAG and semantic search

**File:** `semantic_splitter.py`

---

### 2️⃣ Document Splitter
- Splits already created **Document objects**
- Useful when loading data from PDFs, Word files, or web pages

**File:** `document_splitter.py`

---

### 3️⃣ Length-Based Splitter
- Splits text based on **token or character length**
- Useful to control context window size of LLMs

**File:** `length_splitter.py`

---

### 4️⃣ Text (Character) Splitter
- Simple character-based splitting
- Easy and fast for basic use cases

**File:** `text_splitter.py`

---

## ⚙️ Installation

Create a virtual environment (optional but recommended):

```bash
pip install -r requirements.txt

