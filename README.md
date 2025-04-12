
# 🏠 stayEasy - Your Travel Companion!

StayEasy is a full-stack MERN (MongoDB, Express, React, Node.js) web application inspired by Airbnb, designed for users to discover and manage property listings. It supports user authentication and real-time communication between users and hosts.

## 🔑 Key Features
- User authentication & authorization using JWT(Sign up / Login)
- Create, update, and delete listings with image support (Cloudinary)
- Maps location with coordinates
- Real-time chat between guest and host using Socket.io
- Location-based search
- Leave and manage reviews for listings
- RESTful API (Node.js + Express)
- OTP & Email Verification
- Live sync of listing actions via Socket.io events
- Clean UI with React

## 💻 Tech Stack
- **Frontend:** React, vanila CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT (JSON Web Token)
- **Real-Time Communication:** Socket.io
- **Email Services:** Nodemailer
- **Deployment:** Render (Backend), Vercel (Frontend)
- **State Management & Routing:** React Router, useState/useEffect hooks

## ⚙️ Installation & Setup

#### 1. Clone the repo
```bash
 git clone https://github.com/Jainplk/stayEasy.git  
 cd StayEasy
```
#### 2. Install dependencies
Backend:
```bash
  cd backend
  npm install
```

Frontend:
```bash
cd frontend
npm install
```
#### 3.  Set up Environment Variables
Create a .env file in the backend folder:

```bash
  PORT=5000
  MONGO_URL=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret_key
  CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
  CLOUDINARY_API_KEY=your_cloudinary_api_key
  CLOUDINARY_API_SECRET=your_cloudinary_api_secret
  EMAIL_USER=your_email_address
  EMAIL_PASS=your_email_password
```
#### 📝 Replace the placeholder values (your_...) with your actual credentials.

#### 4. Start the server

Backend:
```bash
  cd backend
  npm install
  nodemon app.js
```

Frontend:
```bash
  cd frontend
  npm install
  npm run dev
```
## 📸 Screenshots

- ![Home Page](https://github.com/user-attachments/assets/961df3cb-0afb-4f45-9be9-f253301f883d)

- ![Listing Detail Page](https://github.com/user-attachments/assets/b7802e54-b9b0-474e-b937-b49e77298ede)

- ![Sign up Page](https://github.com/user-attachments/assets/48452e78-d1d2-481c-a84d-b22ef45e05c6)

- ![Message Interface(Guests)](https://github.com/user-attachments/assets/8bc283a6-60ee-45f9-a3b1-d38838e8b215)

- ![Chat Page(Host)](https://github.com/user-attachments/assets/862b40d4-7f5f-41b2-b0a2-f4c15e4c4450)

## 📌 Future Enhancements
- Booking and Payment integration (e.g. Razorpay or Stripe)
- Save listings (wishlist)
- Admin panel for hosts

## 🌐 Deployed Project
- Frontend: View Frontend on Vercel

- Backend:  View Backend API on Render

## 🙋‍♂️ Authors

- [@jainPlk](https://github.com/Jainplk)

