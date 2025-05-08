# Task Manager Application

A full-stack task management application built with Next.js, Node.js, and MongoDB.

## Features

- 🔐 Authentication (JWT-based)
- 📝 CRUD operations for tasks
- 🔔 Real-time notifications
- 🔍 Advanced filtering and search
- 📊 Dashboard with task analytics
- 🎨 Modern and responsive UI

## Tech Stack

- **Frontend**: Next.js 14 (React)
- **Backend**: Node.js with Express
- **Database**: MongoDB
- **Authentication**: JWT
- **Real-time**: Socket.IO
- **Styling**: Tailwind CSS

## Project Structure

```
task-manager-app/
├── frontend/           # Next.js frontend application
├── backend/           # Node.js backend application
└── README.md
```

## Prerequisites

- Node.js (v18 or higher)
- MongoDB
- npm or yarn

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Set up environment variables:
   - Create `.env` files in both frontend and backend directories
   - Add necessary environment variables (see .env.example files)

4. Start the development servers:
   ```bash
   # Start backend server
   cd backend
   npm run dev

   # Start frontend server
   cd ../frontend
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Environment Variables

### Backend (.env)
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/task-manager
JWT_SECRET=your_jwt_secret
```

### Frontend (.env.local)
```
NEXT_PUBLIC_API_URL=http://localhost:5000
```

## License

MIT 