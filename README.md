# VTalk 💬

**VTalk** is a full-stack real-time chat application that allows users to send and receive messages instantly. Built with modern technologies like React, Node.js, MongoDB, and Socket.IO, it supports real-time communication, authentication, and image-based user profiles.

---

## 🚀 Features

- 🔐 User authentication (Sign up / Login)
- 🧑‍🤝‍🧑 Real-time 1-on-1 chat with Socket.IO
- 🟢 Online user status indicator
- 📸 Profile image upload via Cloudinary
- 📝 Editable profile information
- 💬 Message history with auto-scroll
- 🌙 Dark mode support
- 🧭 React Router-based navigation

---

## 🛠 Tech Stack

**Frontend:**
- React
- Tailwind CSS
- React Router
- Context API
- Axios
- Socket.IO Client

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- Socket.IO
- Cloudinary (for image uploads)

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/v1shwaj1th/VTalk.git
cd VTalk
```

### 2. Setup the Backend

```bash
cd server
npm install
```

Create a `.env` file in the `server/` directory with the following variables:

```env
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the backend server:

```bash
npm run dev
```

### 3. Setup the Frontend

```bash
cd ../client
npm install
npm run dev
```

---

## 🧪 Future Enhancements

- ✅ Group chats  
- ✅ Typing indicators  
- ✅ Message delete/edit  
- ✅ Read receipts  
- ✅ Push notifications  

---

## 🙋‍♂️ Author

**Vishwajith**  
GitHub: [@v1shwaj1th](https://github.com/v1shwaj1th)

---

## 📄 License

This project is licensed under the **MIT License**.
