# 🎓 Alumni Connect: Unites Alumni, Students & Admins Data Hub

## 📋 Overview
Alumni Connect is an innovative digital platform designed to centralize alumni data management and foster engagement among alumni, current students, and institutional administrators. It addresses the fragmentation of alumni records by providing a unified hub for profile management, networking, career opportunities, and knowledge sharing. 

Built with modern web technologies, the platform supports real-time collaboration and scalable features to enhance institutional relationships and professional growth.

> 🏆 This project was developed as part of a hackathon solution for the Smart India Hackathon 2025, targeting the problem of centralized alumni data management for the Government of Punjab's Department of Higher Education.

## ⭐ Key Features
- 🔐 **User Authentication:** Secure sign-up/login with JWT validation for three user roles
- 👤 **Profile Management:** Detailed profiles with skills, experiences, avatars, and updates
- 📊 **Admin Dashboard:** Batch-wise statistics, activity metrics, performance reports
- 💼 **Job Finder Module:** Skill-based job search with auto-apply functionality
- 📚 **Course Marketplace:** Alumni can create/sell courses; users can buy/subscribe
- 💬 **Community Engagement:** Real-time chats, team discussions, groups, and forums
- 🎯 **Engagement Enhancements:** Webinars, gamification, alumni spotlights
- ⚡ **Real-time Features:** Live code collaboration, notifications via Socket.io

## 🛠️ Tech Stack

### 🎨 Frontend
- ⚛️ React.js (Port: 3000)
- ⚡ Vite for fast development
- 🎭 Tailwind CSS
- 🔄 Axios
- 📝 Monaco Editor

### 🔧 Backend
- 🟢 Node.js + Express (Port: 5000)
- 🔒 JWT + bcrypt
- 🔌 Socket.io

### 🗄️ Database
- 🍃 MongoDB Atlas
- 📁 Collections: Users, Profiles, Chats & Events, Code Sessions, Jobs, Courses

### 🚀 Deployment
- Frontend: Vercel/Netlify
- Backend: Render/Heroku
- Database: MongoDB Atlas
- CDN: Cloudflare

## ⚙️ Installation

### 📋 Prerequisites
- Node.js (v18+)
- MongoDB Atlas account
- Git

### 🔨 Setup Steps

1. Clone the repository:
```bash
git clone https://github.com/yourusername/alumni-connect.git
cd alumni-connect
```

2. Install dependencies:
```bash
# Backend
cd backend
npm install

# Frontend
cd frontend
npm install
```

3. Configure environment:
```bash
# Create .env in backend
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Run the application:
```bash
# Backend
cd backend
npm start

# Frontend
cd frontend
npm run dev
```

🌐 Access at:
- Frontend: http://localhost:5173
- Backend: http://localhost:5000

## 🤝 Contributing
1. Fork the project
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
MIT License - see the [LICENSE](LICENSE) file

## 📫 Contact
- 👨‍💻 Project Lead: Shivam Singh Rawat
- 📧 Email: shivamsrawat7@gmail.com

## 🙏 Acknowledgments
- 🏆 Smart India Hackathon 2025
- 💻 Open-source libraries: React, Node.js, MongoDB, Socket.io

*Last Updated: October 07, 2025* 📅
