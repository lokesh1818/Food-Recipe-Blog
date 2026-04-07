# 🍽️ Food Recipe Sharing Platform

A full-stack web application where users can explore, create, and share their favorite food recipes. This platform connects food lovers and makes discovering new dishes easy and interactive.

---

## 🚀 Features

- 📝 Add and share your own recipes  
- 📖 Browse recipes with ingredients and instructions  
- 🔍 Clean and user-friendly interface  
- 📱 Fully responsive design  
- 🌐 REST API integration  

---

## 🛠️ Tech Stack

**Frontend:**
- React.js  
- CSS / Tailwind CSS  

**Backend:**
- Node.js  
- Express.js  

**Database:**
- MongoDB  

---

## 📂 Project Structure

Food-Recipe-App/
│
├── client/        # Frontend (React)
├── server/        # Backend (Node + Express)
├── README.md

---

## ⚙️ Installation & Setup (Run Locally)

Follow these steps to run the project on your local system:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2️⃣ Setup Backend
cd server
npm install

Create a .env file inside the server folder and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string

Start the backend server:

npm start
3️⃣ Setup Frontend

Open a new terminal:

cd client
npm install
npm start
▶️ Running the Application
Frontend: http://localhost:3000
Backend: http://localhost:5000