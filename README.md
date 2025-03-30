# Real-Time Chat Application

## Overview

This is a real-time chat application built with React, TypeScript, and WebSocket technology. The application allows users to create and join temporary chat rooms with unique room codes, enabling instant communication between two users.

## 🌟 Features

### Key Functionalities
- **Dynamic Room Creation**: Generate unique 6-character room codes
- **Real-Time Messaging**: Instant message transmission using WebSocket
- **User Count Tracking**: Live updates of connected users
- **Responsive Design**: Mobile and desktop-friendly interface
- **Temporary Rooms**: Rooms expire when users exit

### Technical Highlights
- React with TypeScript frontend
- WebSocket-based backend
- Context API for state management
- Tailwind CSS for styling
- Automatic scrolling in chat interface
- Differentiated message styling (sent vs. received)

## 🚀 Technologies Used

### Frontend
- React
- TypeScript
- React Router
- Tailwind CSS
- WebSocket Client

### Backend
- Node.js
- WebSocket Server (`ws` library)
- TypeScript

## 🔧 Installation

### Prerequisites
- Node.js (v14 or later)
- npm or yarn

### Setup Steps

1. Clone the repository
```bash
git clone https://github.com/yourusername/real-time-chat.git
cd real-time-chat
```

2. Install Frontend Dependencies
```bash
# Navigate to frontend directory
cd frontend
npm install
```

3. Install Backend Dependencies
```bash
# Navigate to backend directory
cd backend
npm install
```

## 🖥️ Running the Application

### Start Backend
```bash
# In backend directory
npm run start
# or
ts-node index.ts
```

### Start Frontend
```bash
# In frontend directory
npm run dev
```

## 📂 Project Structure
```
real-time-chat/
│
├── frontend/
│   ├── src/
│   │   ├── Dashboard.tsx      # Room creation & joining
│   │   ├── Home.tsx           # Chat interface
│   │   ├── RoomContext.tsx    # Room state management
│   │   └── App.tsx            # Main application routing
│
└── backend/
    └── index.ts               # WebSocket server logic
```

## 🔒 How It Works

1. **Room Creation**
   - Users can create a new room with a unique 6-character code
   - Code is randomly generated using alphanumeric and special characters

2. **Room Joining**
   - Enter the room code to join an existing room
   - Maximum of 2 users per room
   - Real-time user count updates

3. **Messaging**
   - Send messages in real-time
   - Messages are color-coded (white for sent, dark for received)
   - Automatic scrolling to latest message

## 🌈 User Interface

### Dashboard
- Create new room button
- Room code input
- Room code sharing section

### Chat Interface
- Room code display
- User count indicator
- Message input area
- Scrollable message history

## 🔍 WebSocket Communication

### Message Types
- `join`: User enters a room
- `chat`: Send/receive messages
- `userCount`: Update connected users


Live Link: [[https://chat-sphere-frontend-chi.vercel.app/](https://chat-sphere-frontend-chi.vercel.app/)]

---

**Happy Chatting! 🚀💬**
