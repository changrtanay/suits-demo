[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge)](https://suitsv2.vercel.app/)
##### Live Demo: https://suitsv2.vercel.app/
# ⚖️ Suits – AI-Powered Indian Judgement Explorer

**Suits** is an advanced AI-powered legal research platform that helps users explore Indian court judgements like never before. With AI summarization, semantic search, chatbot queries, topic tagging, and powerful insights—all in a beautiful, responsive interface—Suits transforms complex legal texts into accessible, searchable knowledge.

---

## Screenshot
Here is a screenshot from the live demo:

![Screenshot](screenshot.png)

## ✨ Features

### 🔍 Smart Search & Discovery
- **Search Judgements** by keyword, issue, or topic.
- **In-text Search & Highlighting** within judgement documents.
- **Vector Semantic Search** powered by **Pinecone** for contextual results.

### 🧠 AI Capabilities (Gemini 2 Flash)
- **AI Summarization**: Quick summaries for long judgements.
- **AI-Powered Key Highlights & Conclusions**.
- **Clean Infobox Generation** like Wikipedia for structured knowledge.
- **Conversational Chatbot** to query judgements and ask legal questions.
- **Word Cloud** visual insights from each case.

### 🏷️ Rich Metadata Tagging
- Each judgement is parsed and annotated with:
  - **Issue**
  - **Precedent**
  - **Facts**
  - **Respondent's/Petitioner's Arguments**
  - **Conclusion**
  - ...and more.

### 🧱 UI/UX
- **Light/Dark Mode**
- **Responsive Design** (mobile/tablet/desktop)
- **Pagination**, **Skeleton Loaders**, and **Toasts** for smooth UX

---

## 🧰 Tech Stack

| Frontend        | Backend         | AI & Infra               |
|-----------------|-----------------|--------------------------|
| Vite + React    | Express.js      | Gemini 2 Flash API       |
| Tailwind CSS    | MongoDB (Atlas) | Pinecone (Vector DB)     |
| Redux           | REST API        | Cloudinary (Files/Images)|
| Vercel (Deploy) | Render (Deploy) | Resend (Emails)          |

---

## 🚀 Getting Started Locally

### 🔧 Prerequisites

- Node.js ≥ 18
- npm (comes with Node)
- Git

---

### 📁 Folder Structure

```
suitsv2/
│
├── client/      # Frontend (Vite + React + Tailwind)
└── server/      # Backend (Express + MongoDB)
```

---

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/changrtanay/suits.git
cd suits
```

---

### 2️⃣ Setup `.env` Files

#### 📦 `client/.env`

```env
VITE_API_URL=http://localhost:8080
```

#### ⚙️ `server/.env`

```env
FRONTEND_URL=http://localhost:5173
MONGODB_URI=
RESEND_API= (optional)
CLOUDINARY_CLOUD_NAME= (optional)
CLOUDINARY_API_KEY= (optional)
CLOUDINARY_API_SECRET_KEY=  (optional)
GEMINI_API_KEY=
PINECONE_API_KEY=
```

---

### 3️⃣ Install Dependencies

#### 🖥️ Client

```bash
cd client
npm install
npm run dev
```

App runs at: [http://localhost:5173](http://localhost:5173)

---

#### 🖥️ Server

In a **separate terminal**:

```bash
cd server
npm install
npm run dev
```

API runs at: [http://localhost:8080](http://localhost:8080)

---

## 🌍 Live Demo

Explore the deployed app here:  
🔗 [https://suitsv2.vercel.app](https://suitsv2.vercel.app)

---

## 📦 Deployment

- **Frontend** hosted on **Vercel**
- **Backend** hosted on **Render**
- **MongoDB Atlas** for database
- **Pinecone** for vector embeddings
- **Gemini AI** for summarization and chatbot

---

## 🧠 AI Use-Cases Summary

| Use Case           | Tech Stack                   |
|--------------------|------------------------------|
| AI Summary         | Gemini 2 Flash               |
| AI Chatbot         | Gemini + Pinecone            |
| Semantic Search    | Pinecone + Vector Embeddings |
| Infobox Generation | Gemini                       |
| Word Cloud         | Visualization from Tags      |

---

## 🤝 Contributing

If you'd like to contribute or extend this project, feel free to fork and raise a PR!

---

## 🛡️ License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙋‍♂️ Author

**Tanay Changoiwala**  
[GitHub](https://github.com/changrtanay) · [LinkedIn](https://www.linkedin.com/in/tanaychangoiwala)

---

## 📌 Notes

> 🔒 This repo is currently private. If you're viewing this README and need access, contact the author directly.
