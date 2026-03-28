# 🚀 QuickGPT - AI SaaS Platform with Credit System

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,100:243B55&height=200&section=header&text=QuickGPT&fontSize=40&fontColor=ffffff&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://quick-gpt-chi-dusky.vercel.app">
    <img src="https://img.shields.io/badge/Live-Demo-green?style=for-the-badge&logo=vercel" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=00F7FF&size=28&center=true&vCenter=true&width=700&lines=AI+SaaS+Platform;Stripe+Integration;Credit+Based+System;Built+with+MERN" />
</p>

---

## 🌟 Features

* 🔐 User Authentication (JWT-based)
* 💬 Real-time Chat System
* ⚡ AI Text & Image Generation (Gemini API)
* 💳 Stripe Payment Integration
* 🎯 Credit-Based Usage System
* 🔄 Webhook-Based Payment Verification
* 📊 Transaction Tracking
* 🌙 Dark Mode + Fully Responsive UI

---

## 📱 Responsiveness

✔ Mobile Friendly
✔ Tablet Optimized
✔ Desktop Optimized

> Built with responsive design principles using Tailwind CSS.

---

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,tailwind,nodejs,express,mongodb,javascript" />
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=stripe,git,github,vscode" />
</p>

---

## 📸 Project Screenshots

### 🏠 Home Page

<img src="./assests/home.png" />

### 💬 Chat Interface

<img src="./assests/chat.png" />

### 💳 Payment Page

<img src="./assests/payment.png" />

### 🌙 Dark Mode

<img src="./assests/darkmode.png" />

---

## 🏗️ Project Structure

```
/client
  /components
  /pages
  /context

/server
  /controllers
  /models
  /routes
  /middlewares
  /configs
```

---

## ⚙️ Environment Variables

Create a `.env` file:

```
JWT_SECRET=your_secret
MONGODB_URI=your_uri
GEMINI_API_KEY=your_key

IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_url

STRIPE_PUBLISHABLE_KEY=your_key
STRIPE_SECRET_KEY=your_key
STRIPE_WEBHOOK_SECRET=your_secret
```

---

## 🚀 Installation

### Clone Repo

```
git clone https://github.com/your-username/quickgpt.git
cd quickgpt
```

### Install Dependencies

```
cd server && npm install
cd ../client && npm install
```

### Run App

```
# backend
cd server
npm run dev

# frontend
cd client
npm run dev
```

---

## 💳 Stripe Webhook Setup

```
stripe listen --forward-to localhost:3000/api/stripe
```

Copy the webhook secret into `.env`.

---

## 🔄 Payment Flow

1. Select plan
2. Stripe checkout
3. Payment success
4. Webhook triggered
5. Credits updated

---

## 🧠 Credit System

* Users purchase credits
* Credits deducted per usage
* Prevents overuse

---

## 🔐 Security

* JWT Authentication
* Webhook Signature Verification
* Environment Variable Protection

---

## 🚀 Future Improvements

* 📊 Dashboard analytics
* 💳 Subscription plans
* 🔔 Notifications
* 🌐 Deployment

---

## 🤝 Contributing

Pull requests are welcome!

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Vedant Patil

---

## ⭐ Support

Give a ⭐ if you like this project!
