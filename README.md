# 🚀 QuickAI – Full Stack AI SaaS Platform

QuickAI is a full‑stack AI SaaS platform offering powerful AI tools such as article generation, blog title suggestions, AI image creation, background removal, object removal, and résumé analysis.  
The application includes full authentication, subscription billing, history tracking, and a public community feed.

---

# 🌐 Live Links

### ✅ **Frontend (React + Vite + Tailwind)**  
🔗 https://quick-ai-full-stack-lemon.vercel.app/

### ✅ **Backend (Express + Node.js + Neon Postgres)**  
🔗 https://quick-ai-server-sand-five.vercel.app/

---

# ⚙️ Tech Stack

### **Frontend**
- React (Vite)
- TailwindCSS
- React Router
- Lucide Icons
- Clerk Authentication
- Axios

### **Backend**
- Node.js
- Express.js
- OpenAI API (AI generation)
- Neon PostgreSQL
- Multer (Uploads)
- Image Processing libraries
- CORS

### **Database**
- Neon Serverless PostgreSQL

### **Deployment**
- Vercel (Frontend + Backend)
- Neon (Database)

---

# 🧠 Features

### ✍️ **1. AI Article Generator**
Generates articles based on the topic & selected length.

### 📝 **2. Blog Title Generator**
SEO‑optimized title suggestions.

### 🎨 **3. AI Image Generator**
- Creates images from prompts  
- Styles: Realistic, 3D, Anime, Minimal, Moody  
- Option to publish images to community feed  

### ✂️ **4. Background Remover**
AI removes background instantly.

### 🧽 **5. Object Remover**
Remove selected objects from an image.

### 📄 **6. Resume Analyzer**
Upload a resume → get strengths, weaknesses, ATS score.

### 👥 **7. Community Page**
- Public gallery
- Like system

### 🔐 **8. Authentication & Billing**
- Clerk auth
- Google login
- Premium plan subscriptions

### 🧾 **9. User History**
Stores all AI creations inside Neon DB.

---

# 🏗️ Project Structure

```
quick-ai/
│
├── client/             # Frontend (React + Vite)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── assets/
│   │   └── App.jsx
│   └── index.html
│
└── server/             # Backend (Node + Express)
    ├── routes/
    ├── controllers/
    ├── middleware/
    ├── db/
    └── server.js
```

---

# 🔧 Installation & Setup

## 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR-USERNAME/quickai.git
cd quickai
```

## 2️⃣ Install Frontend Dependencies
```bash
cd client
npm install
```

## 3️⃣ Install Backend Dependencies
```bash
cd ../server
npm install
```

---

# 🔑 Environment Variables

### 🎯 Frontend – `/client/.env`
```
VITE_CLERK_PUBLISHABLE_KEY=your_key
VITE_API_URL=https://quick-ai-server-sand-five.vercel.app
```

### 🖥 Backend – `/server/.env`
```
OPENAI_API_KEY=your_key
DATABASE_URL=postgresql://username:password@host/dbname
CLERK_SECRET_KEY=your_key
```

---

# ▶️ Run Project Locally

### Frontend
```bash
cd client
npm run dev
```

### Backend
```bash
cd server
npm start
```

---

# 🚀 Deployment
- **Frontend**: Vercel  
- **Backend**: Vercel Serverless Functions  
- **Database**: Neon Postgres  

---

# ⭐ Support
If you like this project, please ⭐ the repo!

---

# 👨‍💻 Author
**Sanjay Singh Rawat**  
- GitHub: https://github.com/sanjayrawatt  
- LinkedIn: https://www.linkedin.com/in/sanjay-singh-rawat-2483471a6/  
- Portfolio: https://sanjay-singh-rawat-portfolio.netlify.app/
