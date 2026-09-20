# Streamify 🎥

Streamify is a **MERN stack-based real-time chat and video calling application**. It allows users to securely communicate through real-time messaging and video calls.

## Features

* 🔐 User Registration & Login
* 💬 Real-time Chat
* 📹 Video Calling
* 🔑 JWT Authentication
* 👤 User Profiles
* 💾 MongoDB Database
* ⚡ Real-time Communication
* 📱 Responsive UI

## Tech Stack

**Frontend:** React.js, JavaScript, HTML, CSS

**Backend:** Node.js, Express.js

**Database:** MongoDB

**Authentication:** JWT

**Real-Time:** Socket.io, Stream Chat & Video

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
cd streamify-video-calls
```

Install dependencies:

```bash
cd backend
npm install
```

```bash
cd ../frontend
npm install
```

## Environment Variables

Create a `.env` file in the backend folder and add your required MongoDB, JWT, and Stream credentials.

```env
PORT=5000
MONGODB_URI=your_mongodb_url
JWT_SECRET_KEY=your_jwt_secret
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
```

## Run the Project

Start the backend:

```bash
cd backend
npm run dev
```

Start the frontend in another terminal:

```bash
cd frontend
npm run dev
```

Then open the local frontend URL in your browser.

## Author

**Ashutosh Gangwar**

B.Tech Computer Science & Engineering

---

⭐ If you like this project, consider giving it a star!
