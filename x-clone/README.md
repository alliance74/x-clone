<h1 align="center">📱 React Native X Clone app 🚀</h1>

![Demo App](/mobile/assets/images/screenshot-for-readme.png)

Welcome to **X Clone**, a fully functional clone of the X (formerly Twitter) app built with React Native. This project features a complete frontend and backend, secure authentication, and cloud database integration—all designed to showcase modern app development best practices.

---

## 🧑‍🍳 App Features Overview

- 🔐 **Authentication** via Clerk (Google / Apple ID supported)
- 🏠 **Home Screen** to post text & images (from gallery or camera)
- ❤️ **Like & Comment** system with smooth modal interactions
- 🔔 **Notifications Tab** for likes & comments
- 📬 **Messages Tab** with chat history & long-press delete
- 👤 **Profile Tab** with editable profile modal
- 🔎 **Search Tab** for trending content
- 🚪 **Sign Out** that returns to login screen

---

## 🧠 What IT  COMBINES

- 🛠️REST API with Express.js & MongoDB
- 🔐 Implementing robust auth with **Clerk**
- ☁️ Uploading & serving images via **Cloudinary**
- 🛡️ Adding rate-limiting, bot detection & security with **Arcjet**
- 🧪 Using **Git & GitHub** in real-world team workflow (PRs & branches)
- 📦 Connecting everything in a real deployment setup

---

## 📁 .env Setup

### ⚙️ Backend (`/backend`)

```bash
PORT=5001
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

MONGO_URI=<your_mongodb_connection_uri>

ARCJET_ENV=development
ARCJET_KEY=<your_arcjet_api_key>

CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
```

### ⚙️ Mobile (`/mobile`)

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>

EXPO_PUBLIC_API_URL=<your_backend_api_url>
```

## ⚙️ Run the backend

```bash
cd backend
npm install
npm run dev

```

## 📱 Run the mobile

```bash
cd mobile
npm install
npx expo start
```
