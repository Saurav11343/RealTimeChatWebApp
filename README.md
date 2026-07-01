# RealTime Chat Web App

A MERN-based real-time chat application. This project currently includes
a basic full-stack setup with a React frontend and an Express backend
deployed online.

## Current Status

-   ✅ React + Vite frontend
-   ✅ Tailwind CSS setup
-   ✅ shadcn/ui initialized
-   ✅ Express backend
-   ✅ Separate `app.js` and `server.js`
-   ✅ Environment configuration
-   ✅ Simple API route and controller
-   ✅ Frontend ↔ Backend communication with Axios
-   ✅ GitHub integration
-   ✅ Frontend deployed on Vercel
-   ✅ Backend deployed on Railway

## Tech Stack

### Frontend

-   React
-   Vite
-   Tailwind CSS
-   shadcn/ui
-   Axios
-   React Router DOM
-   Lucide React
-   React Hook Form *(planned)*
-   Zod *(planned)*

### Backend

-   Node.js
-   Express.js
-   CORS
-   dotenv

### Deployment

-   Frontend: Vercel
-   Backend: Railway
-   Source Control: GitHub

## Project Structure

```txt
RealTimeChatWebApp/
│
├── frontend/
│   ├── src/
│   │   ├── api/
│   │   │   └── axios.js
│   │   │
│   │   ├── components/
│   │   │   └── ui/
│   │   │
│   │   ├── pages/
│   │   │   ├── Welcome.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   └── Chat.jsx
│   │   │
│   │   ├── routes/
│   │   │   └── AppRoutes.jsx
│   │   │
│   │   ├── validations/
│   │   │   └── auth.validation.js
│   │   │
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   ├── .env
│   └── package.json
│
├── backend/
│   ├── config/
│   │   └── env.js
│   │
│   ├── controllers/
│   │   └── name.controller.js
│   │
│   ├── routes/
│   │   └── name.route.js
│   │
│   ├── app.js
│   ├── server.js
│   ├── .env
│   └── package.json
```
## Current Demo

The frontend sends a user-entered name to the backend using Axios.

Example request:

``` json
{
  "name": "Saurav"
}
```

Example response:

``` json
{
  "success": true,
  "message": "Hello Saurav, your backend is working!"
}
```

## Upcoming Features

-   Authentication (Register/Login)
-   React Hook Form + Zod validation
-   JWT Authentication
-   Protected Routes
-   User Profiles
-   One-to-One Chat
-   Socket.io
-   Online Status
-   Typing Indicator
-   Read Receipts
-   Group Chat
-   Image & File Uploads
-   Cloudinary Integration

## Goal

Build a modern, scalable WhatsApp-inspired real-time chat application
using the MERN stack and Socket.io as a portfolio and master's project.
