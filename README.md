# 📰 AI-Powered Blog App

An intelligent blog management system with AI-generated content, image optimization, and a powerful admin dashboard.  
Built using **Node.js, Express, MongoDB, ImageKit, and Google Gemini AI**.

---

## 🚀 Features

### 🔹 Public
- Browse published blogs with categories and rich media
- Read detailed blog pages
- Add comments (reviewed before publishing)
- Optimized blog images (auto-formatting, resizing, and compression)

### 🔹 Admin
- Secure admin login with JWT authentication
- Create, update, delete blogs with image uploads
- AI-powered blog content generation using Google Gemini
- Publish/unpublish blogs (draft support)
- Manage comments: approve/delete
- Dashboard with insights:
  - Total blogs, drafts, comments count
  - Recent 5 blogs
  - Pending comments

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB + Mongoose  
- **AI:** Google Gemini API  
- **Image Storage & Optimization:** ImageKit  
- **Auth:** JWT (JSON Web Tokens)  
- **Others:** CORS, Multer, FS  


# 🛠 Server Setup

📦 Install dependencies

cd server

npm install

# ⚙️ Environment Variables

Create a .env file in /server:

PORT=5000

MONGO_URI=your_mongodb_url

JWT_SECRET=your_secret_key

IMAGEKIT_PUBLIC=your_key

IMAGEKIT_PRIVATE=your_key

IMAGEKIT_URL_ENDPOINT=your_endpoint

GOOGLE_API_KEY=your_key

Start backend

npm run dev

Backend: http://localhost:5000

# 🖥️ Client Setup

📦 Install dependencies

cd client

npm install

🚀 Start development

npm run dev

http://localhost:5173

## screenshots




🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you want to update.

📄 License

This project is licensed under the ISC License.
