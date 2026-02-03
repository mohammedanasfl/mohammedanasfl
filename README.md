# Mohammed Anas (mohammedanasfl)

Hi — I'm Mohammed Anas. I build practical, LLM-powered conversational systems and document Q&A solutions using Retrieval-Augmented Generation (RAG). I focus on turning documents and knowledge bases into reliable, interactive assistants and developer-friendly tools.

---

## 🔭 TL;DR
- LLMs, RAG, document ingestion, vector search & chatbots
- Practical experience building FAQ/chatbots and document Q&A systems
- GitHub: [mohammedanasfl](https://github.com/mohammedanasfl)  
- Email: [nanass21072001@gmail.com](mailto:nanass21072001@gmail.com)

---

## 💼 What I build
- LLM-Powered FAQ chatbots that answer user questions with concise, contextual responses.
- Document-Q-A systems (RAG) that ingest PDFs and other docs, index them with embeddings, and answer queries using vector retrieval + LLM generation.
- End-to-end pipelines: ingestion → chunking → embeddings → vector store → retrieval → answer generation.

---

## ⭐ Pinned / Key Projects
- **LLM-Powered-FAQ-Chatbot** — FAQ-style conversational agent.  
  Repo: https://github.com/mohammedanasfl/LLM-Powered-FAQ-Chatbot

- **Document-Q-A-RAG-Chatbot** — RAG chatbot for answering questions from documents (PDFs, docs).  
  Repo: https://github.com/mohammedanasfl/Document-Q-A-RAG-Chatbot

(See the repositories above for demos, architecture, installation steps, and example usage.)

---

## 🛠️ Tech & Tools
- LLMs: OpenAI (GPT family), Hugging Face models
- RAG & Retrieval: Embeddings, FAISS / Chroma / Pinecone / Milvus
- Orchestration / Libraries: LangChain patterns, Python
- Data ingestion: PDF/DOCX parsing, text chunking, metadata
- Deployment & infra: Docker, cloud hosting, basic CI
- Languages: Python, occasional JavaScript/TypeScript

---

## 🔎 Typical architecture (pattern)
1. Ingest documents (PDF, DOCX, HTML)
2. Preprocess & chunk text + attach metadata
3. Compute embeddings for chunks
4. Store embeddings in a vector store (FAISS / Chroma / Pinecone)
5. Retrieve top-k relevant chunks for a query
6. Pass retrievals + query to an LLM to generate the final answer
7. (Optional) tools: summarization, citations, follow-up Q/A

---

## 📂 What you’ll find in my repos
- Clear setup instructions and environment variables (API keys)
- Scripts to ingest documents and build vector indexes
- Example notebooks or small apps for local testing
- Basic web frontends / APIs (where applicable) to demonstrate chat UX
- Notes on evaluation: answer quality, hallucination mitigation, and citation

---

## 🤝 Collaboration / Contribution
- I welcome contributions: bug fixes, new connectors (file types / vector stores), UX improvements, and evaluation scripts.
- If you want to collaborate:
  1. Open an issue describing the idea or bug.
  2. Create a branch per feature/fix.
  3. Include tests or usage examples if possible.
  4. Open a PR with a clear description.

---

## 📝 Want to use my work?
- Clone the repo you want to try.
- Create a virtual environment and install dependencies (see each repo README).
- Set your OpenAI (or chosen provider) API key as an environment variable.
- Run the ingest / build-index script, then start the app (examples are in each repo).

---

## 📫 Contact
- Email: [nanass21072001@gmail.com](mailto:nanass21072001@gmail.com)  
- GitHub: https://github.com/mohammedanasfl

---

If you want, I can:
- Convert this into a shorter bio for GitHub profile README (README.md for the profile repo).
- Generate README.md files tailored to each of the two pinned projects (with setup/run examples) — I can inspect those repos if you give me permission or share links.
