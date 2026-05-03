# Realtime Checkbox System

## 📌 Overview

This project is a real-time system where multiple users interact with a shared grid of checkboxes.

When one user toggles a checkbox, the change will be reflected for all connected users instantly.

The goal of this project is to understand how real-time systems work at a deep level and build it step by step like a backend engineer.

---

## 🎯 Learning Goals

- Understand client-server architecture
- Learn how WebSockets enable real-time communication
- Build shared state across multiple users
- Learn how to scale systems using Redis (later phase)
- Think like a system designer

---

## 🧱 Tech Stack

- Node.js
- Express.js
- WebSockets (ws)
- pnpm
- HTML, CSS, JavaScript

---

## ⚙️ Project Setup

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/realtime-checkbox.git
cd realtime-checkbox
```

Install dependencies:

```bash
pnpm install
```

Run the server:

```bash
node server/index.js
```

Open browser:

```text
http://localhost:8080
```

---

## 🏗️ Project Structure

```text
realtime-checkbox/
│
├── client/           # Frontend (UI)
│   └── index.html
│
├── server/           # Backend (Express + WebSocket)
│   └── index.js
│
├── package.json
├── pnpm-lock.yaml
├── .gitignore
├── README.md
```

---

## 🔄 System Flow (Current)

```text
User → Browser → HTTP Request → Server → Response
```

(Currently only basic server response is implemented)

---

## 🚧 Roadmap

### Phase 1 (Completed)

- Project setup (pnpm + Git)
- Basic Express server
- Initial repository structure

### Phase 2 (In Progress)

- Serve frontend HTML
- Establish WebSocket connection
- Send/receive messages

### Phase 3

- Real-time checkbox state sync
- Broadcast updates to all users

### Phase 4

- Redis integration (shared state across servers)

### Phase 5

- Rate limiting (prevent abuse)

### Phase 6

- Authentication (OAuth / OIDC)

### Phase 7

- Scaling & system design improvements

---

## 🧠 Key Concepts Covered

- Event-driven architecture
- Persistent connections (WebSockets)
- State management in distributed systems
- Backend scalability patterns

---

## 📌 Current Status

Phase 1 complete — basic server setup is working.

---

## 👤 Author

Ashish Kumar Jha
