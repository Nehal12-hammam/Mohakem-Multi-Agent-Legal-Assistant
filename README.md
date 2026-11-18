# Mohakem - Multi-Agent AI Legal Assistant

## 📌 Overview
Architected **Mohakem**, a production-grade multi-agent AI system for Egyptian law, with specialized agents coordinated by a central router. Built a LangGraph document-auditing pipeline for multi-step clause validation and custom OCR workflows (OpenCV & Gemma) for scanned legal papers. Qdrant and Neo4j power hybrid semantic, graph-based, and lexical (BM25) retrieval across three main tracks:

- **Contract Generation & Review Track:** Automates drafting and analyzes legal contracts for risk detection, compliance, and anomaly detection.
- **Defense Memorandum Generation Track:** Assists in structuring comprehensive legal arguments and compiling defense briefs.
- **Legal Consultation Track:** Delivers precise, context-aware answers to complex legal inquiries grounded in indexed reference materials.

## 🛠️ Technologies Used
- **Languages & Frameworks:** Python, LangGraph, LangChain
- **Databases & Search:** Qdrant (Vector DB), Neo4j (Graph DB), Hybrid Search (Vector, Graph & BM25)
- **Models & Vision:** Gemma LLM, OpenCV
