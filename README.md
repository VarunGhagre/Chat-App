# 💬 Real-Time Chat Application

A full-stack real-time chat application built using the MERN Stack and Socket.IO. Users can register, log in securely, and exchange instant messages in real time with a modern and responsive user interface.

## 🚀 Features

- 🔐 User Authentication (JWT)
- 👤 User Registration & Login
- 💬 One-to-One Real-Time Chat
- 🟢 Online/Offline User Status
- 📩 Instant Message Delivery
- 📜 Chat History
- 😊 Emoji Support
- 🔔 Real-Time Notifications
- 📱 Responsive Design
- 🔒 Protected Routes

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios
- React Router DOM


### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Socket.IO
- bcrypt.js

## 📂 Project Structure

```
Real-Time-Chat-App
│
├── client
│   ├── src
│   ├── public
│   └── package.json
│
├── server
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── socket
│   ├── config
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Real-Time-Chat-App.git
```

### Go to Project Directory

```bash
cd Real-Time-Chat-App
```

### Install Backend Dependencies

```bash
cd server
npm install
```

### Install Frontend Dependencies

```bash
cd ../client
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the **server** folder.

```env
PORT=5000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:5173
```

---

## ▶️ Run the Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

---

## 📸 Screenshots

Add screenshots here:

- Login Page
- Register Page
- Chat Window
- Online Users

---

## 🔄 Real-Time Communication Flow

1. User logs in.
2. JWT authenticates the user.
3. Socket.IO establishes a WebSocket connection.
4. Users join the server.
5. Messages are sent instantly.
6. Receiver gets the message in real time.
7. Messages are stored in MongoDB.
8. Chat history is available after refresh.

---

## 🔒 Security Features

- Password Hashing using bcrypt
- JWT Authentication
- Protected API Routes
- Input Validation
- Secure Socket Connection

---

## 📈 Future Improvements

- Group Chat
- Voice Calling
- Video Calling
- File Sharing
- Image Sharing
- Message Reactions
- Typing Indicator
- Read Receipts
- Push Notifications

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## ⭐ Support

If you found this project helpful, don't forget to give it a **Star ⭐** on GitHub.

---

## 📧 Contact

**Varun Ghagre**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile
