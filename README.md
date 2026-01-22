# ✨ Chirp - Full Stack Realtime Chat App ✨

**🚀 Live Demo:** [https://twobit.onrender.com](https://twobit.onrender.com)

## Highlights

- ⚡ **Tech stack:** MERN + Socket.io + TailwindCSS + DaisyUI
- 🔐 **Authentication & Authorization** with JWT
- 💬 **Real-time messaging** with Socket.io
- 🟢 **Online user status** tracking
- 🎨 **Global state management** with Zustand
- 🎭 **Multiple theme** support (Light mode & Dark mode)
- 🖼️ **Image sharing** via Cloudinary
- 🚨 **Error handling** both on the server and on the client
- ⭐ **Free deployment** on Render
- 🔧 **And much more!**

## 🛠️ Tech Stack

**Frontend:**
- React 19
- Vite
- TailwindCSS + DaisyUI
- Zustand (State Management)
- Socket.io-client
- Axios
- React Router DOM
- React Hot Toast

**Backend:**
- Node.js + Express
- MongoDB + Mongoose
- Socket.io
- JWT Authentication
- Cloudinary (Image Storage)
- bcryptjs

## 🚀 Features

- **User Authentication**: Secure signup/login with JWT tokens
- **Real-time Messaging**: Instant message delivery with Socket.io
- **Online Status**: See who's online in real-time
- **Profile Management**: Update profile pictures with Cloudinary integration
- **Image Sharing**: Send images in conversations
- **Theme Switching**: Toggle between light and dark modes
- **Responsive Design**: Works seamlessly on desktop and mobile
- **Message History**: View all past conversations

## ⚙️ Setup .env file

Create a `.env` file in the `backend` folder with the following variables:

```env
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

## 📦 Build the app

Install dependencies for both frontend and backend:

```bash
npm run build
```

This will run:
- `npm install` in the backend folder
- `npm install` in the frontend folder
- Build the frontend production bundle

## 🎯 Start the app

### Development Mode

**Terminal 1 - Backend:**
```bash
cd backend
npm run dev
```

**Terminal 2 - Frontend:**
```bash
cd frontend
npm run dev
```

Frontend will be available at `http://localhost:5173`

### Production Mode

```bash
npm start
```

This will start the backend server which serves the built frontend from the `frontend/dist` folder.

## 🌐 Deployment

This app is deployed on [Render](https://render.com/). The deployment configuration:

1. Build Command: `npm run build`
2. Start Command: `npm start`
3. Environment Variables: Set all `.env` variables in Render dashboard
4. Auto-deploy: Enabled on push to main branch

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
Made with ❤️ by Ayush
</div>
