# 💬🧠 AI Todo Chatbot
**Talk to your tasks. Let AI do the rest.**

---

## ✨ What is this?

This isn't just another todo app.

It's a **conversation-first task manager** where you don't click buttons or fill forms — you simply **talk**, and the system handles everything behind the scenes.

💬 **"Add a task to study at 9pm"**  
✅ Done. Stored. Confirmed.

---

## 🎬 How it feels to use

Instead of navigating UI:

- You type naturally
- The AI understands your intent
- It performs real operations
- You get a human-like response

**It feels less like software… and more like an assistant.**

---

## ⚡ Core Experience

| You say | System does |
|---------|-------------|
| "Add a meeting tomorrow" | Creates a task |
| "Update it to 5pm" | Updates task |
| "Delete my last task" | Removes it |
| "Show my tasks" | Lists everything |

**No commands. No syntax. Just conversation.**

---

## 🧠 What's happening behind the scenes?

This project is built on a **tool-driven AI architecture** — not direct database access.

```
User → AI Brain → Tool Selection → Backend Execution → Response
```

### 🔍 Translation layer (the magic)

The AI:

1. Understands your message
2. Maps it to an action
3. Calls a structured backend tool
4. Waits for execution
5. Responds naturally

---

## 🧩 System Design Philosophy

This system is built on **separation of concerns**:

- 🧠 **AI** = thinking layer
- 🔌 **MCP** = communication bridge
- ⚙️ **Backend** = execution engine
- 🗄️ **Database** = memory

**Each layer has one job, and does it well.**

---

## 🏗️ Architecture Snapshot

```
[ User ]
   ↓
[ Chat Interface ]
   ↓
[ AI Agent ]
   ↓
[ MCP Server ]
   ↓
[ FastAPI Backend ]
   ↓
[ Database ]
```

🎯 **Clean, modular, and scalable by design.**

---

## 🔄 Lifecycle of a Message

Every message goes through a structured journey:

1. 💬 User sends input
2. 🧠 AI interprets meaning
3. 🔧 Tool is selected dynamically
4. ⚙️ Backend executes logic
5. 🗄️ Database updates state
6. 🤖 AI replies in natural language

---

## 🧰 Tools the AI Can Use

The AI doesn't guess — it chooses from **defined tools**:

- `create_task`
- `update_task`
- `delete_task`
- `list_tasks`

**Think of these as abilities the AI can unlock on demand.**

---

## 🧠 Tech Stack (Layered View)

### 🎨 Interaction Layer
- OpenAI ChatKit

### 🤖 Intelligence Layer
- OpenAI Agents SDK

### 🔌 Tooling Layer
- MCP (Model Context Protocol)

### ⚙️ Execution Layer
- FastAPI (Python)

### 🧩 Data Layer
- SQLModel (ORM)
- Neon PostgreSQL

### 🔐 Security Layer
- Better Auth

---

## 🔐 Security Model

Security is built into the core:

- Token-based authentication
- Per-user task isolation
- Strict backend validation

🔒 **Your tasks are yours only.**

---

## 🗄️ What gets stored?

Even though the API is stateless, the system remembers:

- 👤 Users
- 📝 Tasks
- 💬 Conversations

This allows:

- Context-aware responses
- Scalable backend design

---

## 📡 API — Minimal but Powerful

### `POST /chat`

**That's it.**

One endpoint that:

- Accepts natural language
- Triggers AI reasoning
- Executes backend tools
- Returns a human-like response

---

## 🐳 Deployment Ready

The system supports containerization:

- Separate frontend & backend containers
- Easy scaling
- Consistent environments

---

## 📚 What this project demonstrates

This isn't just a CRUD app — it's an **AI system design project**.

### Key takeaways:

- Agent-based architecture
- Tool-calling workflows
- MCP integration patterns
- Stateless + persistent hybrid systems
- Production-grade backend structuring

---

## 🚀 What's next?

Future evolution could include:

- ⏰ Smart reminders
- 🔔 Real-time notifications
- 🎙️ Voice commands
- 🤝 Multi-agent workflows
- 🧠 Advanced planning AI

---

## 💡 Final Thought

This project shows a shift:

**From UI-driven apps → to conversation-driven systems**

**And this is just the beginning.**
