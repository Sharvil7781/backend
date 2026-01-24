# YouTube Backend

A scalable backend API for a YouTube-like video streaming platform built using the MERN stack.
This backend handles authentication, video management, user interactions, and secure token-based authorization.

🚀 Features
🔐 Authentication & Authorization
JWT-based authentication (Access & Refresh Tokens)
Secure login & signup
Token rotation & reuse detection
Protected routes with middleware
Logout & session invalidation

👤 User Management
User registration & login
Profile management
Channel creation
Subscriber system

🎥 Video Management
Upload videos
Update & delete videos
Fetch videos by user/channel
Video views count
Like / dislike videos

💬 Engagement Features
Comments on videos
Like / dislike comments
Subscribe / unsubscribe channels

🛡 Security
HTTP-only cookies
Password hashing using bcrypt
Token expiry handling
Refresh token DB comparison
Centralized error handling

🧱 Tech Stack
Backend
Node.js
Express.js
MongoDB
Mongoose
Authentication
JWT (Access & Refresh Tokens)
bcrypt
Utilities
Cloudinary (media storage)
Multer (file uploads)
dotenv
cookie-parser
