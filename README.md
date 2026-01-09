# Montreal Civic Assistant 🇨🇦🤖

An AI-powered iOS app that answers Montreal city service questions in **plain English** using **LLMs, Retrieval-Augmented Generation (RAG), and real-time open data**.

---

## 🚀 What This App Does

Montreal Civic Assistant helps residents and newcomers instantly understand:

* Garbage, recycling, and compost schedules
* Snow removal and parking restrictions
* Parking permits and bylaws
* How to report city issues (311)
* French city notices explained in English

Instead of searching through PDFs, French-only pages, or outdated forums, users simply **ask a question in natural language**.

---

## 🧠 Tech Stack

### Frontend

* iOS (SwiftUI)
* Chat-style interface
* Location-aware (GPS / postal code)

### Backend

* FastAPI (Python)
* REST APIs

### AI / ML

* OpenAI GPT-4.x (reasoning + tool calling)
* Retrieval-Augmented Generation (FAISS / Chroma)
* Montreal Open Data
* Prompt-engineered intent classification

---

## 🏗️ System Architecture

```
iOS App
  ↓
FastAPI Backend
  ├── Intent Classifier (LLM)
  ├── Tool Layer (City APIs)
  ├── RAG Engine (311, bylaws)
  ├── Response Generator (LLM)
  ↓
Formatted Answer → iOS
```

---

## 📊 Example User Queries

**"When is garbage pickup for my address?"**

→ Returns collection days, reminders, and borough-specific rules.

**"Can I park on my street tonight?"**

→ Checks snow removal alerts and parking bylaws.

**"How do I report a pothole?"**

→ Explains steps and links directly to 311 with pre-filled context.

---

## 🧪 LLM Evaluation

The project includes automated tests for:

* Intent classification accuracy
* Hallucination detection
* Bylaw correctness
* Location-aware answers

---

## 🔮 Roadmap

* French language support
* OCR for city letters
* Push notifications
* User preferences
* Open-source LLM fallback

---

## 🎯 Why This Project

This app demonstrates real-world usage of:

* LLM orchestration
* RAG over structured + unstructured data
* Multilingual NLP
* Practical AI system design

Built as a **portfolio project** showcasing applied machine learning and LLM engineering.

---

## 🧑‍💻 Demo Script

1. Ask about garbage pickup
2. Ask about snow parking restrictions
3. Ask how to report an issue
4. Show French letter explanation

---

## 📄 License

MIT
