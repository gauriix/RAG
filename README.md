# Multi-Modal RAG (Retrieval-Augmented Generation)

This project implements a **multi-modal Retrieval-Augmented Generation (RAG)** system that processes **text and images** to generate context-aware responses using external documents and vector search.

The system integrates **Google Gemini**, **LangChain**, **FAISS**, and **CLIP** for multi-modal understanding and retrieval.

---

## 🚀 Features
- Multi-modal RAG pipeline (text + image understanding)
- Document ingestion from PDFs
- Chunking and vector-based retrieval using FAISS
- Image–text similarity using CLIP
- Context-aware response generation using Google Gemini
- End-to-end flow: **Query → Retrieve → Augment → Generate**

---

## 🧰 Technologies & Libraries Used
- **Python**
- **LangChain**
- **Google Gemini (ChatGoogleGenerativeAI)**
- **FAISS** (vector database)
- **CLIP (CLIPModel, CLIPProcessor)** for image–text similarity
- **PyMuPDF (fitz)** for PDF processing
- **scikit-learn** (cosine similarity)
- **Pillow (PIL)** for image handling
