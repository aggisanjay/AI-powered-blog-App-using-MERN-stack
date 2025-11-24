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

# Home

<img width="1272" height="1059" alt="image" src="https://github.com/user-attachments/assets/b1a94c5a-7994-4f58-9fd4-df40e86fce40" />

# Blog content

<img width="1126" height="1936" alt="image" src="https://github.com/user-attachments/assets/1db21b60-043b-4edd-b8e4-92031a68b466" />


# Admin Login

<img width="575" height="463" alt="image" src="https://github.com/user-attachments/assets/67c64670-db87-4363-8faf-fc0d62ba299c" />

# Dashboard

<img width="1338" height="564" alt="image" src="https://github.com/user-attachments/assets/063838dc-d3f2-47b7-84e6-b426e1dd19de" />

# Add Blogs

<img width="780" height="587" alt="image" src="https://github.com/user-attachments/assets/5db517d0-ad17-4363-8735-0525041af14d" />

# Blog lists

<img width="979" height="329" alt="image" src="https://github.com/user-attachments/assets/cb6c50ef-3631-4df6-a6b6-69378dbe5262" />

# comments

<img width="966" height="306" alt="image" src="https://github.com/user-attachments/assets/aa843432-ad22-4273-bcc5-1bae4e3b3eb6" />

🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you want to update.

📄 License

This project is licensed under the ISC License.
