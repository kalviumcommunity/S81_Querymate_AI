QueryMate AI 🤖

QueryMate AI is a smart chatbot that helps students solve subject-related doubts using Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG). It provides structured, clear, and relevant answers, while demonstrating core GenAI concepts like embeddings, function calling, and prompt engineering.

🚀 Features

LLM-powered question & answer system

Structured outputs (bullet points, code blocks, tables)

Retrieval-Augmented Generation (RAG) for improved correctness

Function calling for definitions, examples, or document search

Embeddings & similarity search (Cosine, Dot Product, L2 distance)

Token logging and tunable parameters (Temperature, Top-K, Top-P)

Responsive UI for smooth interaction across devices

🛠️ Tech Stack

Frontend: React.js (responsive chat interface)

Backend: Node.js + Express

Database: MongoDB Atlas + Vector Database (Pinecone/FAISS/Weaviate)

LLM Integration: OpenAI API

Deployment: Netlify/Vercel (frontend), Render/Railway (backend)

📊 Evaluation Criteria

Correctness → Achieved with structured prompts, embeddings, and evaluation dataset

Efficiency → Fast retrieval using vector search + optimized API calls

Scalability → Cloud deployment (frontend + backend separately), supports large traffic and datasets

📦 API Endpoints (Sample)

POST /api/query → Send a question, return structured answer + token usage

GET /api/history → Fetch past queries with embeddings

POST /api/eval/run → Run evaluation tests with judge prompts

📅 6-Day Build Plan

| Day | Task                                                |
| --- | --------------------------------------------------- |
| 1   | Project setup, branch creation, folder structure    |
| 2   | Responsive chat interface (React)                   |
| 3   | Backend setup with LLM integration                  |
| 4   | Add embeddings + vector search                      |
| 5   | Implement function calling + evaluation pipeline    |
| 6   | Testing, deployment, README update, video recording |
