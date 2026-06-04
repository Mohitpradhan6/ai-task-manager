# 🤖 Full Stack AI-Powered Task Manager

### 👨‍💻 Developed & Customized by: Mohit Sharma
**B.Tech CSE | Rajasthan Technical University, Jaipur**
🔗 [LinkedIn](https://linkedin.com/in/mohit-sharma-62a09b350) | [LeetCode](https://leetcode.com/u/mohitpradhan123/)

![Next.js](https://img.shields.io/badge/Next.js-14-black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT4-green)
![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 🚀 Features

- 🤖 AI-assisted task prioritization using OpenAI API
- 📋 Kanban board with drag & drop task management
- 🔐 JWT-based User Authentication & Authorization
- 📊 Real-time task updates with WebSocket
- 👥 Team collaboration & task assignment
- 📈 Productivity analytics dashboard
- 🔔 Smart notifications & deadline reminders
- 📱 Fully Responsive UI (Mobile + Desktop)
- ⚡ Server-Side Rendering with Next.js for fast performance

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 14, React.js, Tailwind CSS |
| Backend | NestJS, Node.js, REST APIs |
| Database | PostgreSQL, Prisma ORM |
| Auth | JWT, bcryptjs |
| AI | OpenAI GPT-4 API |
| Real-time | WebSocket |
| Tools | Git, GitHub, VS Code, Postman |

---

## 📁 Project Structure
ai-task-manager/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── utils/
├── backend/
│   ├── src/
│   │   ├── tasks/
│   │   ├── auth/
│   │   ├── ai/
│   │   └── users/
└── docker-compose.yml
---

## ⚙️ Setup & Installation

### 1. Clone the repo
```bash
git clone https://github.com/Mohitpradhan6/ai-task-manager.git
cd ai-task-manager
```

### 2. Install Dependencies
```bash
npm install
cd frontend && npm install
```

### 3. Environment Variables
Create `.env` in root:
DATABASE_URL=postgresql://user:password@localhost:5432/taskmanager
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
NODE_ENV=development
PORT=3000
### 4. Run the App
```bash
npm run dev
```

---

## 🌐 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register user |
| POST | /api/auth/login | Login user |
| GET | /api/tasks | Get all tasks |
| POST | /api/tasks | Create task |
| PUT | /api/tasks/:id | Update task |
| DELETE | /api/tasks/:id | Delete task |
| POST | /api/ai/prioritize | AI prioritization |
| GET | /api/analytics | Productivity stats |

---

## 🙋 Author

**Mohit Sharma**
- 📧 mohitpradhan113@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/mohit-sharma-62a09b350)
- 💻 [LeetCode](https://leetcode.com/u/mohitpradhan123/)
- 📍 Jaipur, Rajasthan

---

## 📜 License
Copyright (c) 2024 Mohit Sharma — MIT License
