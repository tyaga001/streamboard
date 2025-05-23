# StreamBoard (Kanban Chat Clone)

**A Trello‑style Kanban board with integrated real‑time chat built on Stream’s React SDK.**

---

## 🚀 Project Overview

StreamBoard is a demo app showcasing how to build a collaborative kanban board with:

* **Drag & Drop** lists and cards (React‑DND)
* **Card‑level Chat**: threaded comments, reactions, moderation (Stream Chat React SDK)
* **Activity Feed**: real‑time feed of moves, comments, reactions (Stream Feeds)
* **Responsive UI** built with Tailwind CSS and container‑queries

This repo will walk you through brick by brick, with a focus on the Chat integration.

---

## 📦 Tech Stack

* React (Create React App)
* Tailwind CSS (with container-queries plugin)
* React DnD (HTML5 Backend)
* @getstream/react-chat & @getstream/chat
* @getstream/react-feed & stream-feed-client

---

## 🛠 Setup & Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-org/streamboard.git
   cd streamboard
   ```

2. **Install dependencies**

   ```bash
   yarn install
   # or npm install
   ```

3. **Environment variables**
   Create a `.env` file in the root with:

   ```env
   REACT_APP_STREAM_API_KEY=your_stream_api_key
   REACT_APP_STREAM_API_SECRET=your_stream_api_secret
   ```

4. **Run the app**

   ```bash
   yarn start
   ```

---

## 📁 Project Structure

```
streamboard/
├── public/        # static assets
├── src/
│   ├── components/  # React components (Card, List, ChatChannel, Feed)
│   ├── stream/      # Stream client initialization (chatClient.ts, feedClient.ts)
│   ├── App.tsx
│   ├── index.tsx
│   └── styles/      # Tailwind config
├── .env
├── tailwind.config.js
└── README.md
```

---

## 🎯 Next Steps

1. **Initialize React & Tailwind**
2. **Set up StreamChat client & Auth**
3. **Build static Kanban columns**
4. **Integrate Chat Channel per card**

Stay tuned as we flesh out each step!
