# ChatSphere - Real-Time Chat Application with AI

## Overview
ChatSphere is a real-time chat application built with React, TypeScript, and WebSocket technology, enhanced with AI capabilities. The application allows users to create and join temporary chat rooms with unique room codes, enabling instant communication with AI-powered features.

## 🌟 Features

### Key Functionalities
- **Dynamic Room Creation**: Generate unique 6-character room codes
- **Real-Time Messaging**: Instant message transmission using WebSocket
- **User Count Tracking**: Live updates of connected users
- **AI-Powered Chat Summarization**: Get AI-generated summaries of conversations
- **Responsive Design**: Mobile and desktop-friendly interface
- **Temporary Rooms**: Rooms expire when users exit

### Technical Highlights
- React with TypeScript frontend
- WebSocket-based backend
- Context API for state management
- Tailwind CSS for styling
- Automatic scrolling in chat interface
- Differentiated message styling (sent vs. received)
- AI integration for conversation analysis and summaries

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
- AI integration for chat summarization

## 🔧 Installation

### Prerequisites
- Node.js (v14 or later)
- npm or yarn

### Setup Steps
1. Clone the repository
```bash
git clone https://github.com/yourusername/chatsphere.git
cd chatsphere
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
# or ts-node index.ts
```

### Start Frontend
```bash
# In frontend directory
npm run dev
```

## 📂 Project Structure
```
chatsphere/
│
├── frontend/
│   ├── src/
│   │   ├── Dashboard.tsx      # Room creation & joining
│   │   ├── Home.tsx           # Chat interface
│   │   ├── RoomContext.tsx    # Room state management
│   │   └── App.tsx            # Main application routing
│
└── backend/
    └── index.ts               # WebSocket server logic & AI integration
```

## 🔒 How It Works

1. **Room Creation**
   - Users can create a new room with a unique 6-character code
   - Code is randomly generated using alphanumeric and special characters

2. **Room Joining**
   - Enter the room code to join an existing room
   - Real-time user count updates

3. **Messaging**
   - Send messages in real-time
   - Messages are color-coded (white for sent, dark for received)
   - Automatic scrolling to latest message

4. **AI Chat Summarization**
   - Request AI-generated summaries of your conversations
   - One-click summary generation
   - AI-processed content shared with all room participants

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
- AI summary request button

## 🔍 WebSocket Communication

### Message Types
- `join`: User enters a room
- `chat`: Send/receive messages
- `userCount`: Update connected users

## 🤖 AI Integration

ChatSphere leverages artificial intelligence to enhance the chat experience:

- **Conversation Summarization**: Get concise AI-generated summaries of your chat history
- **Clean Formatting**: AI removes unnecessary formatting characters for readable summaries
- **Seamless Integration**: Summary results are broadcast to all room participants

## 📱 Live Demo

Live Link: [ChatSphere](https://chatsphere1-zeta.vercel.app/)

---

**Happy AI-Enhanced Chatting! 🚀💬**
