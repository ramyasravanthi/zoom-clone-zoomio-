# 🎥 Zoom Clone – Real-Time Video Conferencing App
> A full-stack **Zoom-like video conferencing web app** that supports real-time **video/audio**, **screen sharing**, **chat**, and **guest access**, along with **meeting history** for logged-in users.
>
> Built using **WebRTC**, **Socket.io**, **React**, and **Node.js**.


---

## 🚀 Features

✅ Real-time *video and audio* calls
✅ *Screen sharing* support
✅ In-call *chat* with Socket.io
✅ *Guest access* – join without signing up
✅ *Login/Signup* for registered users
✅ *Mic/Camera toggle* controls
✅ *Meeting history* for authenticated users
✅ *Responsive design* using custom CSS + Material UI

---

## 🧰 Tech Stack

### 🔹 Frontend

* React
* WebRTC
* Socket.io‑client
* Axios
* Material UI
* Pure CSS (no Bootstrap/Tailwind)

### 🔹 Backend

* Node.js
* Express.js
* Socket.io
* MongoDB + Mongoose
* bcrypt / crypto

---

## 🗂 Project Structure

### 📁 Backend (/backend)


backend/
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
├── app.js
└── package.json


### 📁 Frontend (/frontend)


frontend/
├── public/
├── src/
│   ├── pages/
│   ├── contexts/
│   ├── styles/
│   ├── utils/
├── App.js
├── index.js
└── package.json


---

## 🧪 Getting Started

### 1. Clone the Repository

bash
git clone https://github.com/your-username/zoom-clone.git
cd zoom-clone


### 2. Start the Backend

bash
cd backend
npm install
npm start


### 3. Start the Frontend

bash
cd ../frontend
npm install
npm start


> ⚠ Make sure the backend runs on port *5000* and the frontend on *3000*, or adjust proxy settings accordingly.

---

## 🧠 What I Learned

* Real-time peer connections with *WebRTC*
* Handling events and signaling using *Socket.io*
* Implementing *authentication* from scratch
* Writing *responsive layouts* using raw CSS
* Integrating a *Node/Express API* with MongoDB

---

## ✨ Future Improvements

* ✅ JWT-based authentication
* ✅ Group calls (multi-user video rooms)
* ✅ Mute/unmute other participants (host control)
* ✅ Deploy with HTTPS (required for WebRTC in production)
* ✅ Add “End Call” functionality

---

## 📄 License

This project is licensed under the *MIT License*.

---

## 🙌 Acknowledgements

* [MDN WebRTC Documentation](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)
* [Socket.io Documentation](https://socket.io/docs/)
* [React Documentation](https://reactjs.org/)

---

## 📝 Project Tagline 

> *A full-stack Zoom alternative using WebRTC, Socket.io, React, and Node.js. Supports real-time video calls, chat, screen sharing, and meeting history.*


