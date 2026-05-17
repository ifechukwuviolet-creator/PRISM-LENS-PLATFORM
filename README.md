# Prism Lens 🌐

Prism Lens is a digital marketplace ecosystem that empowers creators—writers, musicians, and digital artists—to publish, sell, and distribute their digital products directly to a global audience.

## 🚀 Features
- Creator storefronts
- Digital product uploads
- Secure payments system (future integration)
- Global audience reach
- Simple and clean UI

## 🎯 Purpose
To give creators full control over their content, earnings, and audience without relying heavily on third-party platforms.

Prism Lens is a digital marketplace where creators publish and sell music, ebooks, designs, videos, and other digital products directly to a global audience. Prism Lens is a digital ecosystem where creators publish, sell, and scale their work globally without middlemen.

Plain text
Powered by VSM (Violet Swings Music) under Violet Swings Glove - VSG LTD ecosystem.
✔ Website footer
Plain text
VSM × Prism Lens — Powered by VSG LTD
🚀 Simple Breakdown
Plain text
LICENSE → Ifechukwu Gift Morris only

Company → VSG LTD

Brand/Label → VSM (optional, marketing only)

Product → Prism Lens
## 🛠️ Tech Stack
- Frontend: (<h1>Prism Lens</h1>
- Next.js + React + Tailwind CSS
- client/
│
├── public/
│
├── src/
│   ├── app/
│   ├── components/
│   ├── pages/
│   ├── layouts/
│   ├── hooks/
│   ├── services/
│   ├── context/
│   ├── utils/
│   ├── styles/
│   └── assets/
│
├── package.json
└── next.config.js)

- Backend: (Node.js + Express.js
- server/
│
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
├── services/
├── uploads/
├── utils/
├── validations/
├── sockets/
│
├── server.js
├── app.js
└── package.json)

- Database: (MongoDB
- Users)
- 
Authentication:
JWT + bcrypt
Username + Password
        ↓
Backend verifies account
        ↓
User gets access

Storage:
Cloudinary / AWS S3
 { "title": "My Album",
  "fileUrl": "https://cloudinary.com/abc123"}
User uploads file
        ↓
Backend receives file
        ↓
Storage service saves it
        ↓
File URL is stored in database

server/
│
├── uploads/
├── services/
│   └── cloudinary.js
│
├── controllers/
│   └── uploadController.js

Creator uploads music
        ↓
Backend validates file
        ↓
Cloudinary / AWS stores file
        ↓
Database saves file URL
        ↓
Buyers stream/download file

Payments:
Paystack / Flutterwave
1. User selects product
2. Frontend sends payment request
3. Backend initializes payment
4. Paystack processes payment
5. Backend verifies transaction
6. Product unlocks for buyer
7. Creator earnings update
Deployment:
Vercel + Render
Frontend (UI)
+ Backend (logic)
+ Database (data)
+ Storage (media)
+ Payments (money)
+ Security
= Full Platform

## 📦 Getting Started
```bash
git clone https://github.com/Ifechukwuviolet/prism-lens.git
cd prism-lens
