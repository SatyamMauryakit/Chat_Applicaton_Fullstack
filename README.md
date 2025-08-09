# Real-time Chat Application

A full-stack real-time chat application built with React, Node.js, Socket.IO, and MongoDB.

## Features

- 🔒 User authentication (signup, login, logout)
- 👤 User profile management with avatar upload
- 💬 Real-time messaging with Socket.IO
- 🌅 Image sharing in conversations
- 🎨 Multiple theme options with DaisyUI
- 🟢 Online/offline user status
- 💅 Responsive design
- ⚡ Message history persistence
- 🔄 Real-time message updates

## Tech Stack

### Frontend
- React with Vite
- TailwindCSS + DaisyUI for styling
- Socket.IO Client for real-time communication
- Zustand for state management
- React Router for navigation
- Axios for HTTP requests

### Backend
- Node.js & Express
- MongoDB with Mongoose
- Socket.IO for real-time functionality
- JWT for authentication
- Cloudinary for image storage
- bcrypt for password hashing

## Prerequisites

- Node.js (v14+ recommended)
- MongoDB installed and running locally
- Cloudinary account for image storage

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/chat-application.git
cd chat-application
cd backend
npm install
cd frontend
npm install

MONGODB_URI=mongodb://127.0.0.1:27017/chat_app
PORT=5001
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
NODE_ENV=development

├── backend/
│   ├── src/
│   │   ├── controllers/      # Request handlers
│   │   ├── models/          # Database models
│   │   ├── routes/          # API routes
│   │   ├── middleware/      # Custom middleware
│   │   ├── lib/            # Utilities and configurations
│   │   └── seeds/          # Database seeds
│   └── package.json
│
└── frontend/
    ├── src/
    │   ├── components/     # Reusable React components
    │   ├── pages/         # Page components
    │   ├── store/         # Zustand store configurations
    │   ├── lib/           # Utilities and configurations
    │   └── constants/     # Constants and configurations
    └── package.json
