# 🌐 LangGraph MongoDB Seeder

A LangGraph-powered Node.js + TypeScript project for generating and inserting realistic synthetic employee data into a MongoDB database. Perfect for testing dashboards, HR systems, or AI-driven apps.

---

## 🚀 Features

- ✅ Generates complex nested employee records (address, contact, job, emergency contacts, etc.)
- 🤖 AI-generated synthetic data using OpenRouter models (like GPT-4o)
- 🧠 Fallback logic for JSON repair if malformed responses are returned
- 🌿 Built with TypeScript, LangChain, LangGraph, and MongoDB
- 🔄 Easy to re-seed your DB for testing or development purposes

---

## 🧠 Supported LLMs via OpenRouter

| Model Name        | Use as `modelName`              |
| ----------------- | ------------------------------- |
| GPT-4o            | `"gpt-4o"`                      |
| Claude 3.5 Sonnet | `"anthropic/claude-3.5-sonnet"` |
| Gemini Pro        | `"google/gemini-pro"`           |
| Mixtral           | `"mistralai/mixtral-8x7b"`      |

## 📌 Notes
- If JSON responses are malformed, the script tries to auto-repair them.
- Logs will show preview errors and fallback attempts if the LLM output fails to parse.

