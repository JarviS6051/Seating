# 🔥 Train seat booking (MERN + Firebase)

This is a full stack web application with a **Node.js + Express** backend and a **React** frontend. The frontend is integrated with **Firebase** for additional services such as hosting or authentication.

---

## 📂 Project Structure

root/ │ ├── backend/ # Node.js + Express API └── frontend/ # React app with Firebase integration

yaml
Copy
Edit

---

## 🚀 Getting Started

### 📦 Backend Setup

1. Navigate to the backend folder:

   ```bash
   cd backend
Install all dependencies:

bash
Copy
Edit
npm install

Add an env file :

MONGO_URI=...
PORT=...

Start the backend server:

bash
Copy
Edit
npm run start
The server should now be running on http://localhost:5000 .

💻 Frontend Setup
Navigate to the frontend folder:

bash
Copy
Edit
cd frontend
Install all dependencies:

bash
Copy
Edit
npm install
Connect your app to Firebase:

Create a Firebase project at Firebase Console.

Copy your Firebase project ID.

Configure your Firebase connection in the app:

In the .firebaserc - change name according to your firebase project

Start the frontend:

bash
Copy
Edit
npm start
The React app should now be running on http://localhost:5000.

🛠️ Tech Stack
Frontend: React, Firebase

Backend: Node.js, Express

Package Manager: npm