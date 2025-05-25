# 🍛 Sudama Pohe Dapodi – Food Ordering Website

This repository hosts the complete source code for **Sudama Pohe Dapodi**, a dynamic and responsive food ordering web application built using the **MERN Stack** (MongoDB, Express, React, Node.js). It provides a seamless food ordering experience with real-time features, secure authentication, and role-based dashboards.

---

## 🔗 Live Demo

- **User Panel:** [https://food-delivery-frontend-w90g.onrender.com/](https://food-delivery-frontend-w90g.onrender.com/)

---

## ✨ Features

- 🔐 JWT Authentication & Role-based Access
- 🔒 Password Hashing with Bcrypt
- 💳 Stripe Payment Integration
- 👥 Login / Signup / Logout
- 🛒 Add to Cart & Place Orders
- 📦 Order & Product Management (Admin Panel)
- 📊 Role-based User/Admin Dashboards
- 🔎 Product Filtering & Searching
- ⚙️ Authenticated REST APIs
- 🎨 Beautiful Alerts and Responsive UI

---

## 📸 Screenshots

### 🔻 Hero Section
![Hero Section](https://github.com/user-attachments/assets/cecabdc6-2cb8-48d8-84d4-b32ad4fb5c82)

### 🔻 Products Section
![Products](https://github.com/user-attachments/assets/cd5c5b7a-85a0-4779-8889-e0a56edf8302)

### 🔻 Cart Page
![Cart](https://github.com/user-attachments/assets/26c6f79e-bd7c-4725-bc15-fa5b78239fd3)

### 🔻 Login
![Login](https://github.com/user-attachments/assets/cadddbf3-92ad-4248-a49b-a3c3e3839a9b)

---

## 🚀 Run Locally

Go to the project directory

```bash
    cd food-delivery
```
Install dependencies (frontend)

```bash
    cd frontend
    npm install
```
Install dependencies (admin)

```bash
    cd admin
    npm install
```
Install dependencies (backend)

```bash
    cd backend
    npm install
```
Setup Environment Vaiables

```Make .env file in "backend" folder and store environment Variables
  JWT_SECRET=YOUR_SECRET_TEXT
  SALT=YOUR_SALT_VALUE
  MONGO_URL=YOUR_DATABASE_URL
  STRIPE_SECRET_KEY=YOUR_KEY
 ```

Setup the Frontend and Backend URL
   - App.jsx in Admin folder
      const url = YOUR_BACKEND_URL
     
  - StoreContext.js in Frontend folder
      const url = YOUR_BACKEND_URL

  - orderController in Backend folder
      const frontend_url = YOUR_FRONTEND_URL 

Start the Frontend server

```bash
    npm run dev
```

Start the Admin server

```bash
    npm run dev
```

Start the Backend server

```bash
    npm run server
```
## 🧰 Tech Stack
* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/en)
* [Express.js](https://expressjs.com/)
* [Mongodb](https://www.mongodb.com/)
* [Stripe](https://stripe.com/)
* [JWT-Authentication](https://jwt.io/introduction)
* [Multer](https://www.npmjs.com/package/multer)

## 🚢 DeploymentDeployment

The application is deployed on Render.

## 🤝 Contributing

Contributions are always welcome!
Just raise an issue, and we will discuss it.

## 📫 Contact

For questions, feedback, or collaboration opportunities, feel free to connect with me:

- 🔗 [LinkedIn – Rohit Dhotre](https://www.linkedin.com/in/rohit-dhotre)
- 💻 [GitHub – Rdxdhotre](https://github.com/Rdxdhotre)

You can also open an issue in this repository for bugs, suggestions, or feature requests.

