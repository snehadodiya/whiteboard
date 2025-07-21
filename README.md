
# 🖌️ WhiteSync – Real-time synced whiteboard with AI

An interactive real-time whiteboard tool designed to enhance teamwork and visual communication. Built using **React**, **Konva**, **Express.js**, **MongoDB**, and **Socket.IO**, this application enables users to co-create using drawing tools, sticky notes, live cursors, and even **AI-powered canvas commands**. It includes permissions, edit locks, undo/redo, and real-time chat to support seamless collaboration.

> 🎥 **Watch the demo here:** [View Video](https://youtu.be/5W2jGOEhk0U?si=TIyaFz1lMwrEyfMN)

---

## 📊 Overview at a Glance

- 👨‍👩‍👧‍👦 **Up to 5 users** per session
- ⚡ **<300ms latency** for real-time updates
- 🤖 **15+ AI commands** interpreted using backend LLM
- 🔁 Tracks **100+ undo/redo actions** per board
- 💬 Built-in chat with **message persistence**

---

## ✨ Key Features

### 🔐 Login & Sessions

- Secure login with username/password
- Persistent user sessions across reloads

### 🗂️ Board Management

- Create/delete boards
- Invite collaborators by username
- Assign roles as `viewer` or `editor`
- Edit or remove collaborators easily

### 🤝 Real-Time Interaction

- Live sync using **Socket.IO** for:

  - Shapes
  - Drawing
  - Cursor tracking
  - Messaging

- Real-time updates with named cursor highlights

### 🖍️ Drawing Tools

- Tools: `Select`, `Draw`, `Eraser`, `Arrow`, `Sticky Notes`
- Add elements:

  - Rectangle, Circle, Ellipse
  - Arrows, Text, Sticky Notes

- Each element supports:

  - Drag & drop
  - Resize & rotate
  - Color customization
  - Snap-to-grid precision

- Synchronized freehand drawing

### 🧠 AI Commands

- Enter prompts like `"draw a green rectangle"` or `"add a sticky note here"`
- AI generates content via `/api/ai` route on the backend

### 🔐 Role & Locking System

- **Editors**: full canvas control
- **Viewers**: read-only mode
- Shape locking prevents simultaneous edits
- Lock icons appear when items are locked

### ⏪ Undo/Redo Tracking

- Track individual user actions
- Undo/redo with full synchronization across devices

### 💬 Chat

- Built-in live chat for communication
- Persistent history per board

### 🔍 Zoom and Pan

- Zoom with scroll
- Drag to pan
- Infinite canvas with grid layout

---

## 🛠️ Technologies Used

| Layer       | Stack                        |
|------------|------------------------------|
| Frontend    | React, Konva, Material UI    |
| Real-time   | Socket.IO                    |
| Backend     | Node.js, Express.js          |
| Database    | MongoDB                      |
| Auth        | JWT for authentication       |

---

## 🧪 Future Upgrades

- 📤 Export whiteboards as image or PDF
- 🧩 Pre-designed templates for boards
- 📝 Auto-save and version tracking
- 💡 Smarter AI prompt handling
- 📋 Copy/paste and element duplication
- 🌗 Light & dark theme modes

---

## 🙌 Credits

Designed and developed by **Sneha Dodiya** — a passionate full-stack developer driven by creativity and curiosity in real-time applications and AI integration.

---

# 🧑‍🎨 Collaborative Whiteboard

A real-time collaborative whiteboard application built with **React**, **Konva**, **Express**, **MongoDB**, and **Socket.IO**. Users can draw, add shapes, write sticky notes, collaborate live, and use **AI-assisted canvas features**. Complete with role-based permissions, live cursors, edit locking, and undo/redo.

> ✅ **Check the video walkthrough here:** [Watch Demo](#)
> *(Replace `#` with your actual video link)*

---

## 🚀 Features

### 🔐 Authentication

* Login via **username and password**.
* Session management with persistent access.

### 🗂️ Dashboard

* Create and delete boards.
* Invite users by **username** with role assignment (`viewer` or `editor`).
* Manage collaborators (change permission, remove access).

### 🧑‍🤝‍🧑 Real-Time Collaboration

* Built with **Socket.IO** for syncing:

  * Shapes
  * Lines
  * Live cursors
  * Chat
* Multi-user collaboration on the same board.
* Live **cursor tracking** with user names.

### ✍️ Drawing & Editing Tools

* Tools: `Select`, `Draw`, `Erase`, `Arrow`, `Sticky Note`.
* Add Shapes:

  * Rectangle
  * Circle
  * Ellipse
  * Arrow
  * Text
  * Sticky Notes
* All shapes are:

  * **Draggable**
  * **Resizable** (with Transformer)
  * **Editable**
  * **Color customizable** (fill + stroke)
  * **Snap-to-grid** support
* Freehand drawing with live syncing.

### 🧠 AI-Powered Commands

* Type prompts like `"draw a red circle"` or `"add a sticky note"` and let AI generate it.
* Powered by backend `/api/ai` route.

### 🔒 Role-Based Access

* **Editors** can draw, edit, delete.
* **Viewers** can only view canvas in real-time.
* **Edit lock system**: shape-level lock prevents others from editing simultaneously.
* 🔒 Lock icon appears on locked objects.

### 🔄 Undo / Redo System

* Track changes per user.
* Restore or redo last actions.
* Fully synced across sessions.

### 💬 Chat System

* Real-time chat between collaborators.
* History synced per board.

### 🌐 Zoom & Pan

* Mouse wheel zooming (in/out).
* Pan with mouse drag.
* Infinite background grid with scaling.

---

## 🛠️ Tech Stack

| Layer    | Technology                |
| -------- | ------------------------- |
| Frontend | React, Konva, Material UI |
| Realtime | Socket.IO                 |
| Backend  | Node.js, Express.js       |
| Database | MongoDB                   |
| Auth     | JWT-based authentication  |

---

## 📌 TODO / Future Enhancements

* 🔁 Export board as image or PDF
* 📄 Templates for quick board creation
* 💾 Auto-saving and versioning
* 🧠 Better AI response handling
* ✂️ Copy-paste and duplication of shapes
* 🎨 Color themes / dark mode

---

## 🙌 Acknowledgements

Crafted with passion by Sneha Dodiya — a dedicated full-stack developer with a strong interest in AI and machine learning.
