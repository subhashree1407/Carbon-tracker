# 🌿 Carbon Footprint Tracker – Frontend

A responsive and interactive frontend for the **Carbon Footprint Tracker**, a sustainability-focused MERN application that helps users monitor their daily carbon emissions, set eco-friendly goals, and take climate-positive actions.

🔗 **Backend Repository:** *Add your backend GitHub link here*  
🔗 **Live Demo:** *Add deployment link here*

---

## 🚀 Features

### 🔐 Authentication
- Secure User Registration & Login  
- JWT-based session handling  

### 🏡 Home Page
- Clean, blog-style layout  
- Smooth animations for a modern experience  

### 📊 Dashboard
- Weekly & monthly carbon insights  
- Recharts-based graphs & visual summaries  

### 📝 Activity Logging
Track carbon output from multiple categories:
- 🚗 Transport  
- ⚡ Energy  
- 🍽️ Diet  
- 🗑️ Waste  

### 🎯 Goals & Achievements
- Set and track eco-friendly goals  
- Earn achievements & badges dynamically  

### 🏆 Leaderboard
- Real-time ranking system  
- Compare your sustainability score with others  

### 👤 Profile Page
- Update profile information  
- Upload profile picture  
- Change password  

### 💬 Learn More Page
- Guides to help users adopt greener habits  

### 🌗 Responsive UI
- Works across all screen sizes  
- Compatible with light & dark mode  

---

## ⚙️ Tech Stack

### **Frontend**
- React.js (Vite)
- Tailwind CSS
- Axios
- Recharts
- Framer Motion
- React Router DOM

### **State Management**
- React Context API

### **Media & Uploads**
- Multer (via backend API)

---

## 📁 Folder Structure


# 🌿 Carbon Footprint Tracker  
## Student Innovation: **Swadeshi for Atmanirbhar Bharat** – Renewable & Sustainable Energy

**Carbon Footprint Tracker** is an open-source **MERN application** built to calculate, track, and visualize daily carbon emissions — inspiring sustainable choices and empowering users to contribute to India’s **Atmanirbhar Bharat** mission through renewable and responsible living.

By enabling users to measure and reduce their carbon impact, this project supports community action toward a greener, resilient India.

🔗 **Repository:** https://github.com/subhashree1407/Carbon-tracker  
⭐ Built with React, Node.js, and MongoDB :contentReference[oaicite:0]{index=0}

---

## 🌟 Features

### 🔐 User Authentication  
- Register & Login with secure password hashing  
- JSON Web Tokens (JWT) for session security

### 🏡 Home & Info Pages  
- Clean and inviting UI to encourage sustainable living  
- Articles and insights on renewable energy & eco habits

### 📊 Carbon Dashboard  
- Track weekly & monthly carbon emissions  
- Visual graphs for activities like transport, diet, energy, and waste

### 📝 Activity Tracker  
Record daily activities including:
- 🚗 Transportation emissions  
- ⚡ Energy usage  
- 🍽 Diet & food choices  
- 🗑 Waste generation

### 🎯 Goals & Achievements  
- Set eco-goals & track progress  
- Earn badges for sustainable milestones

### 🏆 Leaderboard  
- Compare your sustainable score with others  
- Encourages community engagement

### 👤 Profile Management  
- Update personal info  
- Upload profile photos  
- Change password

### 🌍 Responsive UI  
- Tailwind CSS for modern design  
- Dark/Light mode support

---

## 🛠️ Tech Stack

### Frontend  
- React.js (Vite)  
- Tailwind CSS  
- Axios  
- Recharts  
- Framer Motion  
- React Router DOM

### Backend  
- Node.js & Express.js  
- MongoDB & Mongoose  
- Multer (image uploads)  
- bcrypt (secure passwords)  
- JWT (user authentication)

---

## 📁 Folder Structure

Carbon-tracker/
├── Carbon-frontend/
│ ├── public/
│ ├── src/
│ │ ├── assets/
│ │ ├── components/
│ │ ├── context/
│ │ ├── pages/
│ │ ├── App.jsx
│ │ └── main.jsx
│ ├── package.json
│ └── .env
│
└── Carbon-backend/
├── controllers/
├── models/
├── routes/
├── middleware/
├── uploads/
├── server.js
├── package.json
└── .env

yaml
Copy code

---

## ⚙️ Environment Variables

### Backend (`Carbon-backend/.env`)
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000

shell
Copy code

### Frontend (`Carbon-frontend/.env`)
VITE_API_URL=https://your-deployed-backend-url

yaml
Copy code

---

## 🚀 Installation & Running Locally

### 1. Clone the repository
```bash
git clone https://github.com/subhashree1407/Carbon-tracker.git
cd Carbon-tracker
2️⃣ Set up Backend
bash
Copy code
cd Carbon-backend
npm install
npm start
Backend runs on: http://localhost:5000

3️⃣ Set up Frontend
bash
Copy code
cd ../Carbon-frontend
npm install
npm run dev
Frontend runs on: http://localhost:5173

📦 Deployment
Backend Deployment
Deploy on Render / Railway

Set environment variables (MONGO_URL, JWT_SECRET)

Frontend Deployment
Deploy on Vercel / Netlify

Add environment variable:

ini
Copy code
VITE_API_URL=https://your-backend-url
💡 Project Vision
This project contributes to:
🌱 Renewable & Sustainable Energy awareness
🇮🇳 Swadeshi for Atmanirbhar Bharat — empowering individuals with homegrown innovation to measure and reduce carbon emissions
📊 Practical tools for environmental accountability and behavioral change

🤝 Contributing
Your contributions are welcome!
✔️ Submit issues
✔️ Open pull requests
✔️ Suggest features

Let’s build a sustainable future together!

📄 License
This project is licensed under the MIT License.

