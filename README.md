
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
- **Frontend:** React js, vanila CSS
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
  PORT=your_port
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

- Home Page
 ![Home Page](https://github.com/user-attachments/assets/3da7f5f6-475c-44d4-886b-d64e104e34d3)

- Show Listing in Detail
 ![Listing Detail Page](https://github.com/user-attachments/assets/4bc453ea-9c16-4827-b42a-a302e9651f71)

- Sign up 
![Sign up Page](https://github.com/user-attachments/assets/8e06ff9a-05c0-4c98-8760-f57a98de3d0a)

- Message Interface(Guests)
![Message Interface(Guests)](https://github.com/user-attachments/assets/58b35679-0388-4921-b6d4-0ab89e3e4159)

- Chat Page(Host)
![Chat Page(Host)](https://github.com/user-attachments/assets/800d935a-0507-464f-9d59-fac1015404ee)

## 📌 Future Enhancements
- Booking and Payment integration (e.g. Razorpay or Stripe)
- Save listings (wishlist)
- Admin panel for hosts

## 🌐 Deployed Project
- **Live Demo of StayEasy** : [View Frontend on Vercel](https://stay-easy-one.vercel.app)


## 🙋‍♂️ Authors

- [@jainPlk](https://github.com/Jainplk)

