
<h1 align="center">✨ Full-Stack Interview Platform ✨</h1>

<h4>Talent-IQ is a web application designed to support coding practice, collaborative sessions, and technical interview preparation through an interactive development environment.</h4>

---
![Demo App](/frontend/public/screenshot-for-readme.png)
---

<h1 align="center">Live Demo</h1>

<h1 align="center">[Visit Talent-IQ] https://talent-iq-1-148b.onrender.com/</h1>


##  Key Features

- 🧑‍💻 VSCode-Powered Code Editor
- 🔐 Authentication via Clerk
- 🎥 1-on-1 Video Interview Rooms
- 🧭 Dashboard with Live Stats
- 🔊 Mic & Camera Toggle, Screen Sharing & Recording
- 💬 Real-time Chat Messaging
- ⚙️ Secure Code Execution in Isolated Environment
- 🎯 Auto Feedback — Success / Fail based on test cases
- 🎉 Confetti on Success + Notifications on Fail
- 🧩 Practice Problems Page (solo coding mode)
- 🔒 Room Locking — allows only 2 participants
- 🧠 Background Jobs with Inngest (async tasks)
- 🧰 REST API with Node.js & Express
- ⚡ Data Fetching & Caching via TanStack Query
- 🧑‍💻 Git & GitHub Workflow (branches, PRs, merges)
---

## 🛠️ Tech Stack

- **Frontend:**React.js, JavaScript, Tailwind CSS
- **Backend:** Node.js, Express.js, REST APIs
- **Database:** MongoDB, Mongoose
- **Authentication:** Clerk 
- **Real-Time Communication:** Stream 
- **Background Jobs:** Inngest 
- **Code Execution:** OneCompiler API 
- **Cloud Database:** MongoDB Atlas
- **Deployment:** Render

## 🧪 .env Setup

### Backend (`/backend`)

```bash
PORT=3000
NODE_ENV=development

DB_URL=your_mongodb_connection_url

INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key

STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

CLIENT_URL=http://localhost:5173
```

### Frontend (`/frontend`)

```bash
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

VITE_API_URL=http://localhost:3000/api

VITE_STREAM_API_KEY=your_stream_api_key
```

