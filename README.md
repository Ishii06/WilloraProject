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

## ⚙️ Setup  

### **1. Clone Repository**
```bash
git https://github.com/Ishii06/WilloraProject.git
cd WilloraProject
```
### **2. Install Dependencies**

### Frontend
```bash
cd frontend
npm install
```

### Backend
```bash
cd backend
npm install
```

## **3. Environment Variables**

Create a `.env` file inside `/backend` with:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
GOOGLE_GEN_AI_KEY=your_google_generative_ai_key
```
# 🚀 Run Application

### Backend
```bash
cd backend
npm run dev
```

```bash
cd frontend
npm run dev
```

# 🔄 Application Workflow

- **User Authentication** – Secure login/signup with JWT  
- **Private Journaling** – Users write diary entries securely
- **AI Emotional Analysis** – AI processes text to detect mood & emotions
- **Community Space** – Users share thoughts and engage respectfully
- **Wellness Resources** – Access curated mental health content
---

# 🌟 Future Enhancements

1. 📈 **Advanced emotion trend analytics** – Visualize emotional changes over weeks and months to identify recurring patterns
2. 🧘 **Personalized wellness recommendations** – AI-suggested self-care activities, articles, and mindfulness practices based on user mood and journaling patterns
3. 🌐 **Multi-Language Support** – Enable journaling and community interaction in multiple languages
4. 🤝 **Peer Support Circles** – Small, moderated groups for shared emotional experiences  
5. 🎙️ **Voice-to-Journal** – Convert voice notes into journal entries with emotion detection