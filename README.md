# Video Call Web Application

ChatSphere is a real-time video chat application that allows users to **signup**, **login**, and see all other online users. Users can initiate **video calls** with other online users seamlessly. The application is built with **React** on the frontend, **Node.js** and **Express** on the backend, and uses **MongoDB** for data storage. Authentication is handled with **JWT**, ensuring secure access and user sessions.
---

## 🚀 Features

- **User Authentication**
  - Sign up and log in securely with JWT-based authentication.
- **Real-Time Presence**
  - View all users who are currently online.
- **One-to-One Video Calls**
  - Start a video call with any online user.
- **Protected Routes**
  - Access certain pages only after authentication.
- **Responsive UI**
  - Clean and responsive frontend built with React.

---

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS (for styling)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose for ODM)
- JWT for authentication
- WebRTC / Socket.io (for video call & real-time presence)

---

## 🖥 Run Locally

Follow the steps below to set up the project on your local machine.

### 1. Clone the repository


```bash
  git clone https://github.com/Astha-950/Chat-Sphere.git
```

Backend Setup

```bash
  cd backend
  npm install
 MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=3000
npm start

```

Frontend Setup 

```bash
  npm install

```

Start the server

```bash
  npm run dev
```

