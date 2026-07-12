 # SyncCode 🚀

A **real-time collaborative code editor** that enables multiple developers to code together simultaneously. Perfect for pair programming, technical interviews, and team collaborations.

🔗 **Live Demo:** [https://synccode-1-osu2.onrender.com](https://synccode-1-osu2.onrender.com)

---

## ✨ Features

- **Create or Join Rooms** – Enter a unique room ID to start or join a coding session
- **Custom Usernames** – Set your username to identify yourself in the room
- **Real-time Collaboration** – Changes made by one user are instantly reflected on all connected clients
- **Live Syntax Highlighting** – Code highlighting with CodeMirror editor
- **Editor Customization** – Customize your coding environment
- **Seamless Synchronization** – All users see the same code in real-time

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **React** | Building the front-end interface |
| **Node.js** | Running the server |
| **Express.js** | Handling API requests |
| **Socket.IO** | Enabling real-time communication |
| **CodeMirror** | Providing the code editor |
| **uuid** | Generating unique room IDs |
| **Render** | Deployment platform |

---

## 📁 Project Structure

```
SyncCode/
├── client/ # React frontend
│ ├── public/ # Static assets
│ ├── src/
│ │ ├── components/ # React components
│ │ │ ├── Client.js
│ │ │ ├── Editor.js
│ │ │ ├── EditorPage.js
│ │ │ └── Home.js
│ │ ├── App.js
│ │ ├── index.js
│ │ └── Socket.js # WebSocket configuration
│ └── package.json
├── server/ # Node.js backend
│ ├── index.js # Server entry point
│ ├── Actions.js # Socket event handlers
│ └── package.json
└── README.md

```

---

## Install client dependencies
cd client

npm install

---

## Install server dependencies
cd ../server

npm install

---

## Author
Rahul kewat – [GitHub](https://github.com/rahulkewat552)