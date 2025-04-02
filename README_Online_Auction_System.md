# 🛒 Online Auction System – MERN Stack

A real-time web application that enables users to participate in online auctions, create auction listings, and place live bids using the MERN stack with Socket.IO.

---

## 🚀 Features

- 🧑‍💼 Role-based login (User, Seller, Admin)
- 📦 Sellers can post products for auction
- ⏱ Live countdown timers for each auction
- 💸 Real-time bidding system with Socket.IO
- 🏆 Winner selection at auction end
- 🔐 JWT authentication and route protection
- ☁️ Image uploads via Cloudinary
- 📩 Email notifications (Forgot Password)
- 📊 Admin dashboard with analytics (Top sellers/cities)

---

## 🧱 Tech Stack

| Layer      | Tech         |
|------------|--------------|
| Frontend   | React.js     |
| Backend    | Node.js, Express.js |
| Database   | MongoDB + Mongoose |
| Realtime   | Socket.IO    |
| Auth       | JWT + bcrypt |
| Image Hosting | Cloudinary |
| Email      | Nodemailer   |

---

## 📂 Folder Structure

```
├── backend
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middlewares/
│   │   └── socketio/
├── frontend
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── store/
│   │   └── socket.js
```

---

## 🧑‍💻 Installation

1. **Clone the repo**

```bash
git clone https://github.com/YOUR_USERNAME/auction-website-MERN-Stack
cd auction-website-MERN-Stack
```

2. **Setup Backend**

```bash
cd backend
npm install
cp .env.example .env
# Add your MongoDB URI, JWT secret, and Cloudinary keys
npm start
```

3. **Setup Frontend**

```bash
cd frontend
npm install
npm start
```

---

## 🔑 Environment Variables (.env)

```env
MONGODB_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=1d
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
USER_EMAIL=your_gmail_for_reset
USER_PASSWORD=your_gmail_app_password
```

---

## 📸 Screenshots

(Add screenshots of Live Auction page, Bidding screen, Winner announcement, etc.)

---

## 📜 License

MIT License. Feel free to use, extend, or deploy.

---

## 🙌 Authors

- Rajkamal Ingle – [LinkedIn](https://linkedin.com/in/rajkamalingle)
- Group members: [Add your names here]

---

## 🔗 Project Submission Resources

📄 Project Report (DOCX)  
🎤 Viva Q&A Sheet (DOCX)  
📊 PowerPoint Slides

---
