# 🧠 StackIt – A Minimal Q&A Forum Platform

StackIt is a lightweight and user-friendly question-and-answer platform that encourages collaborative learning and structured knowledge sharing. Built during the **Odoo Hackathon 2025**, StackIt focuses on simplicity, clean UI, and meaningful interaction between community members.

---

## 🚀 Problem Statement

**Problem 2: Minimal Q&A Platform**

Build a minimal platform like Stack Overflow where users can:
- Ask questions with title, description, and tags
- Answer questions with rich formatting
- Vote on answers
- Get notified when someone replies, comments, or mentions them
- Use a simple and responsive UI

---

## 👥 Team Members

- **Mohsin Khan** – `mohsinkhan800213@gmail.com`
- **Vaishnavi Singh**
- **Anshika pandey**

---

## 🔗 Submission Details

- ✅ Selected Problem Statement: **Q&A Platform (Problem 2)**
- ✅ [GitHub Repository](https://github.com/mohsinkhan85090/stackit-qa-platform)
- ✅ Collaborator Added: `ajo-odoo`

---

## ⚙️ Tech Stack

| Layer       | Tech Used                      |
|-------------|-------------------------------|
| Frontend    | React + Vite + Tailwind CSS   |
| Backend     | FastAPI + SQLAlchemy          |
| Auth        | JWT Authentication            |
| Database    | SQLite (local) via SQLAlchemy |
| Styling     | TailwindCSS                   |
| Dev Tools   | Git, GitHub, VS Code          |

---

## 📂 Project Structure

<pre lang="md"> ## 📂 Project Structure ``` stackit-qa-platform/ ├── backend/ │ ├── app/ │ │ ├── models/ │ │ ├── routers/ │ │ └── main.py │ └── requirements.txt ├── frontend/ │ ├── src/ │ │ ├── components/ │ │ └── pages/ │ ├── index.html │ └── main.jsx └── README.md ``` </pre>
---

## ✅ Features

### 🧑‍💻 Users
- Register and Login using JWT Auth
- Post new questions and answers
- Receive notifications

### ❓ Ask Questions
- Title, description (rich text), and multi-tag support
- Rich text editor with formatting, emoji, images, links

### 📝 Answer Questions
- Post formatted answers using the same rich editor
- Mark answers as accepted

### 👍 Voting System
- Upvote/downvote on answers
- Votes affect answer ranking

### 🔔 Notification System
- Get notified when:
  - Someone answers your question
  - Someone comments on your answer
  - You are mentioned (@username)

### 🛡️ Admin Features
- Reject spam/inappropriate content
- Ban users who violate platform rules
- Broadcast updates or alerts

---

## ⚙️ How to Run Locally

### 🔧 Backend (FastAPI + SQLite)


## 📄 License

This project is licensed under the **MIT License**.

---

## 🙏 Acknowledgements

- **Odoo Hackathon 2025 Team**  
- **FastAPI**, **React**, **Tailwind CSS**  
- All open-source contributors
