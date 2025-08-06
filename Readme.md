# QueryMate AI 🤖

QueryMate AI is a smart chatbot built to help students quickly solve their subject-related doubts using the power of Large Language Models (LLMs). It provides structured, clear, and relevant answers with basic Retrieval-Augmented Generation (RAG) and mock function calling support.

---

## 🚀 Features

- Prompt-based Q&A using OpenAI API
- Structured outputs: bullet points, code blocks, tables
- Tuning parameters for accurate and helpful responses
- Mock function calling (e.g., getDefinition, getCodeExample)
- Basic RAG support using local dataset
- Simple chat interface for user interaction

---

## 🛠️ Tech Stack

- **Frontend**: React.js / HTML + CSS
- **Backend**: Node.js or Python (Flask)
- **LLM**: OpenAI API or LangChain
- **Deployment**: Netlify (frontend), Render/Railway (backend)

---

## 📅 6-Day Build Plan

| Day | Task |
|-----|------|
| 1   | Project setup, folder structure, prompt planning |
| 2   | Frontend: chat interface (input, display) |
| 3   | Backend: LLM integration, tuning parameters |
| 4   | Add structured outputs + function calling |
| 5   | Implement basic RAG with local files |
| 6   | Final polish, deployment, testing, README update |
---

## 🧠 How It Works

1. User enters a question (e.g., "Explain arrays in C++")
2. System sends a combined prompt to LLM with optional context (RAG)
3. LLM responds with a structured explanation
4. If relevant, a function is called to get examples or definitions

---