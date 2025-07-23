# Velvet & Whisk 

**Velvet & Whisk** is a sleek and modern e-commerce platform built with **React** and powered by **Firebase**. Designed to provide a premium and seamless shopping experience, it combines elegant UI/UX with robust functionality.

---

## ✨ Features

- **Shopping Cart** (CartTab) – Persistent cart powered by **Redux**
- **Product Detail Pages** – Detailed views with clean layout
- **Secure Payments** – Integrated with **Razorpay** for fast and secure checkout
- **Firebase Backend** – User authentication, product database, and order management
- **React Router** – Smooth navigation across product listings and other pages
- **Responsive Design** – Optimized for both desktop and mobile users
- **State Management** – Efficient global state with **Redux Toolkit**

---

## 🛠️ Tech Stack

- **Frontend:** React, Redux, React Router, SCSS / CSS Modules
- **Backend:** Firebase (Firestore, Authentication)
- **Payments:** Razorpay Integration
- **Deployment:** Firebase Hosting / Vercel / Netlify

---

## 🚀 Getting Started

### 1. Clone the Repository

git clone https://github.com/your-username/velvet-whisk.git
cd velvet-whisk

### 2. Install Dependencies

npm install --legacy-peer-deps


### 3. Set Up Firebase

- Go to the [Firebase Console](https://console.firebase.google.com/)
- **Create a new project**
- In Project Settings, **Register your web app**
- **Enable Firestore** and **Authentication** (under 'Build' in the left menu)
- Copy your Firebase configuration object

Create a `.env` file in your project root and add:

+ REACT_APP_FIREBASE_API_KEY=your_api_key
+ REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
+ REACT_APP_FIREBASE_PROJECT_ID=your_project_id
+ REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
+ REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
+ REACT_APP_FIREBASE_APP_ID=your_app_id

> **Note:** Ensure `.env` is included in your `.gitignore` to protect sensitive data.

### 4. Run the App


npm start

Visit http://localhost:3000 in your browser.

## Build for Production

npm run build
