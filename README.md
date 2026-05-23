# Emergency Detection Research Q&A Bot
A RAG (Retrieval Augmented Generation) pipeline that answers questions 
about my published research paper on AI-based emergency detection.

# Built by
**Bokka Sowjanya** | B.E CSE AI & ML | Sai Vidya Institute of Technology
Published Researcher | IDCIoT 2026 Conference

# Problem It Solves
Finding specific information across research documents is slow and painful.
This bot lets you ask natural language questions and get cited answers 
directly from the paper — instantly.

# RAG Architecture
PDF Paper → Text Extraction → Chunking (800 words, 100 overlap)
→ ChromaDB Vector Store → Query Embedding → Top-3 Retrieval
→ Llama 3.3 (Groq) → Cited Answer

# Tech Stack
- **LLM:** Llama 3.3 70B via Groq API
- **Vector Store:** ChromaDB (all-MiniLM-L6-v2 embeddings)
- **PDF Processing:** PyPDF2
- **UI:** Gradio
- **Platform:** Google Colab

# How to Run
1. Open the notebook in Google Colab
2. Install dependencies
3. Add your Groq API key
4. Upload your PDF
5. Ask questions!

# Research Paper
Smart AI Multimodal Architecture for Automated Emergency Detection and Alerts
presented at IDCIoT 2026, Kerala, India.

# Results
- 🎯 Audio Model (Scream Detection): **95% accuracy**
- 🎯 Video Model (Gesture Detection): **80% accuracy**
