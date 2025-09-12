# PingUp 🚀

A full-stack social media application where users can share posts, upload stories, follow each other, and chat in real time.  
This project is inspired by the **GreatStack YouTube tutorial**.

🌐 **Live Demo:** [PingUp](https://ping-up-silk.vercel.app)

---

## ✨ Features

- **Authentication & Profiles**
  - Secure login/signup with Clerk
  - Profile info: picture, bio, location, followers & following
  - Edit your profile details

- **Posts**
  - Create posts with text & images
  - Upload media via ImageKit
  - Like/unlike posts
  - Personalized feed showing posts from you + users you follow

- **Stories**
  - Create 24-hour stories (text, images, or videos)
  - View stories from people you follow

- **Messaging**
  - Real-time private chat (powered by Server-Sent Events)
  - Send text or image messages
  - Messages marked as seen once viewed

- **UI/UX**
  - Built with TailwindCSS for responsive design
  - Smooth gradients & modern look
  - Works on desktop & mobile

---

## 🛠️ Tech Stack

**Frontend:**
- React + Redux Toolkit
- Clerk (Authentication)
- Axios
- TailwindCSS + Lucide Icons
- Moment.js

**Backend:**
- Node.js + Express
- MongoDB + Mongoose
- Clerk middleware for auth
- Multer (file uploads)
- ImageKit (media hosting)
- Server-Sent Events (real-time chat)
