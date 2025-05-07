# Real-Time Chat Application

A full-stack real-time chat application built using MERN Stack (MongoDB, Express, React, Node.js) with Socket.IO for real-time communication and JWT authentication for secure user access.

## Features
- 🔒 Secure Login & Signup with JWT-based authentication
- 💬 Real-time Messaging with Socket.IO
- 👥 One-to-One Chat Functionality
- 🟢 Online Users Indicator
- 🎨 Responsive UI built with React
- 🔄 Auto Sync of messages across all open clients
- 🧾 User Authentication & Authorization
- 🗂️ RESTful API for user management and message handling

## How to Setup and Run Locally

### 1. Clone the Repository
```bash
  -git clone https://github.com/your-username/chat-app.git
  -cd chat-app ```


### **2. Setup Backend**

Follow these steps to configure and run the backend server:

1. Navigate to the `backend` folder and install dependencies:

    ```bash
    cd backend
    npm install
    ```

2. Create a `.env` file in the `backend/` directory with the following content:

    ```ini
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_secret_key
    ```

3. Start the backend server:

    ```bash
    npm start
    ```

> ⚠️ Ensure MongoDB is running locally or provide a valid MongoDB Atlas URI in `MONGO_URI`.

### **3. Setup Frontend**
```bash
cd ../frontend
npm install
npm start
```

