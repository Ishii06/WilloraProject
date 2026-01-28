# 🌿 WILLORA – AI-Powered Journaling & Emotional Wellness Platform

## 🔍 About the Project

**WILLORA** is an AI-powered journaling web platform designed to help users express their thoughts freely while gaining **emotional insights and mood analysis** through AI.  
The platform promotes **self-awareness, mental well-being, and community support**, while maintaining strong privacy and security for personal reflections.

This project was developed as part of a **Web Development with MERN Stack Internship**.

---

## ✨ Key Features

- 📝 **AI-Driven Journaling**  
  Users can write personal diary entries and receive **AI-based emotional and mood analysis** to better understand their mental state.

- 🌍 **Community Interaction**  
  A public space where users can share thoughts **anonymously or with identity**, engage through **comments and upvotes**, and support others.

- 🌱 **Wellness Insights**  
  Curated mental health articles, peace-focused platforms, and self-care resources to encourage emotional well-being.

- 🔐 **Security & Privacy Focused**  
  Strong emphasis on data protection—**personal journal entries remain private and secure**.

---

## 🛠️ Tech Stack

### **Frontend**
- ⚛️ **React.js** – UI development  
- 🎨 **CSS / Utility Styling** – UI styling  
- 🌀 **Framer Motion** – Smooth animations  
- 🎥 **GSAP** – Advanced animations  
- 📅 **React Calendar** – Journal date tracking  
- 📊 **Recharts & Chart.js** – Mood & emotion visualization  
- 🎭 **React Icons** – Iconography  
- 🔑 **Google OAuth** – Authentication  
- 🔐 **JWT Decode** – Token handling  
- 📆 **date-fns** – Date utilities  
- 🧩 **clsx** – Conditional class handling  

### **Backend**
- 🟢 **Node.js** – Runtime environment  
- ⚡ **Express.js** – REST API  
- 🍃 **MongoDB + Mongoose** – Database  
- 🔐 **JWT (jsonwebtoken)** – Authentication  
- 🔒 **bcryptjs** – Password hashing  
- 📁 **Multer** – File handling  
- 🌐 **CORS** – Cross-origin handling  
- 🔧 **dotenv** – Environment configuration  

### **AI & APIs**
- 🤖 **OpenAI API** – Emotional analysis & AI insights  
- 🧠 **Google Generative AI (Gemini)** – Mood and sentiment understanding  

---

## ⚙️ Installation, Environment Setup & Running the Project

```bash
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/willora.git
cd willora

# 2️⃣ Install frontend dependencies
cd frontend
npm install

# 3️⃣ Install backend dependencies
cd ../backend
npm install

# 4️⃣ Create environment variables
# Create a .env file inside /backend and add:
# MONGO_URI=your_mongodb_connection_string
# JWT_SECRET=your_jwt_secret
# OPENAI_API_KEY=your_openai_api_key
# GOOGLE_GEN_AI_KEY=your_google_generative_ai_key

# 5️⃣ Start backend server
npm start

# 6️⃣ Start frontend server (open a new terminal)
cd ../frontend
npm run dev