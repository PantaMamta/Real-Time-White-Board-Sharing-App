# Real-Time-White-Board-Sharing-App
# 🖊️ Real-Time Whiteboard Sharing App

A real-time collaborative whiteboard application that allows multiple users to draw, write, and interact on the same canvas simultaneously. Built for online collaboration such as remote teaching, team brainstorming, and live discussions.

---

## 🚀 Features

* ✏️ Real-time drawing & sketching
* 👥 Multi-user collaboration
* 🔄 Live synchronization using WebSockets
* 🎨 Pen, eraser, and clear board options
* 🧹 Clear whiteboard for all users
* 📱 Responsive design (desktop & mobile)
* ⚡ Low-latency updates

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5 Canvas
* CSS / SCSS

### Backend

* Node.js
* Express.js
* Socket.IO

---

## 📂 Project Structure

```
Real-Time-White-Board-Sharing-App/
│
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── server/                 # Node.js backend
│   ├── index.js
│   └── package.json
│
├── README.md
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Real-Time-White-Board-Sharing-App.git
cd Real-Time-White-Board-Sharing-App
```

### 2️⃣ Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd client
npm install
```

---

## ▶️ Running the Application

### Start Backend Server

```bash
cd server
npm start
```

### Start Frontend

```bash
cd client
npm start
```

📍 Open browser at: `http://localhost:3000`

---

## 🔌 How It Works

* Users connect to the server via **Socket.IO**
* Drawing events are emitted in real-time
* Server broadcasts events to all connected clients
* Canvas updates instantly for everyone

---

## 📸 Screenshots

> Add screenshots or GIFs here to demonstrate real-time drawing

---

## 🎯 Use Cases

* Online classrooms
* Team brainstorming sessions
* Remote meetings
* Interview explanations
* Live tutorials

---

## 🔮 Future Improvements

* User authentication
* Different colors & brush sizes
* Save / export whiteboard as image
* Voice or video chat integration
* Undo / redo functionality

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/new-feature`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

