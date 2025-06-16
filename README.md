# 📘 AI Teacher Chat Web App

An interactive AI-powered web chat application where users can talk to a virtual teacher. It uses OpenAI's GPT-4 model to answer questions in various categories like Mathematics, English, Programming, and more.

---

## 🌐 Features

- 🎓 Chat with different AI teacher personas (e.g., AI Tutor, Math, English)
- 💬 Voice input using Web Speech API
- 🌙 Dark mode toggle
- 📱 Responsive layout with Bootstrap
- 🤖 Backend powered by OpenAI's GPT-4 API

---

## 🗂 Folder Structure


<pre lang="nohighlight"><code>onlineLearningWeb/
├── backend/
│   └── openai-api-server/
│       ├── index.js
│       ├── .env
│       ├── .gitignore
│       ├── package.json
│       ├── package-lock.json
│       └── node_modules/
├── frontend/
│   ├── index.html
│   ├── script.js
│   └── style.css
 </code></pre>

 ## 🚀 Setup Instructions

### 1. Extract the Project Folder

After downloading or cloning the repository as a ZIP file:

1. Unzip the folder.
2. Open the folder named `onlineLearningWeb`.

---

### 2. Backend Setup (Node.js + Express)

Navigate to the backend server directory:

```bash
cd backend/openai-api-server
```

Install dependencies using npm:

```bash
npm install
```

Start the backend server:

```bash
node index.js
```

✅ The server will run locally at:  
`http://localhost:3000`

---

### 3. Frontend Setup (HTML/CSS/JS)

Go back to the main folder and open the frontend:

1. Navigate to the `frontend/` folder.
2. Open the file `index.html` in your browser.
