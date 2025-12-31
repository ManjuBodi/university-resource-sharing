# AI-Powered University Study Resource Platform

University students rely on scattered study materials, informal sharing groups, and unstructured preparation for exams. Existing platforms lack personalization, exam-centric insights, and intelligent analysis of previous year questions (PYQs).

This project aims to build a centralized, AI-assisted study platform that enables students to share resources and receive personalized, exam-oriented learning support.

The platform allows students to upload and access shared study resources. Using Retrieval-Augmented Generation (RAG), the system provides AI-driven summaries, question answering, and PYQ-based topic importance analysis.

The system follows a layered architecture consisting of:
- Client Layer (Web App)
- API Layer (Backend Services)
- Data Layer (Relational + Vector Storage)
- AI Layer (LLM + Embeddings)
(Diagram incoming!)

Frontend: React / Next.js  
Backend: Node.js / FastAPI  
Database: PostgreSQL  
Vector DB: FAISS / Pinecone  
AI: LLM APIs (Gemini / OpenAI)  
Storage: Object Storage (S3 / Firebase)  
