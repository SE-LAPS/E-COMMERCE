# 🛒 E-Commerce MERN Stack Web Project

Welcome to the **E-Commerce MERN Stack Web Application**! This project is a full-stack web application built using the **MERN** stack (**MongoDB**, **Express.js**, **React.js**, and **Node.js**). The app allows users to browse products, add them to their cart, and proceed with checkout, offering a complete e-commerce experience. 🚀

---

## 🌟 Features

- **User Authentication & Authorization** 🔐  
  Users can register, log in, and manage their accounts with secure JWT authentication.

- **Product Management** 🛍️  
  Browse, search, and filter products by categories, price, and ratings.

- **Shopping Cart** 🛒  
  Add and remove products from the cart, update quantities, and view the total cost in real-time.

- **Order Processing** 📦  
  Place orders, view order history, and track order status.

- **Admin Dashboard** 🖥️  
  Manage products, users, and orders via a dedicated admin panel.

- **Responsive Design** 📱  
  Fully responsive UI optimized for desktop, tablet, and mobile devices.

---

## 🔧 Tech Stack

- **Frontend**:  
  - React.js ⚛️  
  - Redux for state management 🗂️  
  - Axios for API requests 🌐  
  - Bootstrap for UI design 🎨

- **Backend**:  
  - Node.js & Express.js 🚀  
  - MongoDB with Mongoose for database management 👌  
  - JWT & bcrypt for authentication 🔐

- **Other Tools**:  
  - Postman for API testing 📩  
  - Cloudinary for image uploads ☁️  
  - Stripe for payment integration 💳

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ecommerce-mern-stack.git
cd ecommerce-mern-stack
```

### 2. Install dependencies

#### Frontend:
```bash
cd frontend
npm install
```

#### Backend:
```bash
cd backend
npm install
```

### 3. Environment Variables

Create a `.env` file in the root of the backend directory and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
STRIPE_SECRET_KEY=your_stripe_secret_key
```

### 4. Run the application

#### Backend:
```bash
cd backend
npm run dev
```

#### Frontend:
```bash
cd frontend
npm start
```

The application should now be running at `http://localhost:3000` 🚀

---

## 📂 Project Structure

```
ecommerce-mern-stack/
├── backend/                # Backend code (Node.js, Express)
│   ├── controllers/        # Route controllers
│   ├── models/             # Mongoose models
│   ├── routes/             # Express routes
│   ├── utils/              # Utility functions
│   └── server.js           # Entry point
├── frontend/               # Frontend code (React.js)
│   ├── public/             # Static files
│   ├── src/                # React components & pages
│   ├── redux/              # Redux store & slices
│   └── index.js            # Entry point
└── README.md               # Documentation
```

---

## 🌐 Live Demo

Check out the live demo: [Live Demo Link](https://your-live-demo-link.com) 🌍

---

## 📸 Screenshots

### 🏠 Home Page
![1](https://github.com/user-attachments/assets/15bda380-e7db-49b1-b5be-ece5e905f7c9)


### 🛒 Product Page
![2](https://github.com/user-attachments/assets/eefb5fd5-434f-4776-9a81-99518b65bb0c)


### 📦 Cart Page
![3](https://github.com/user-attachments/assets/3bab34f1-2175-4eea-85a1-fab291d8075b)

---

## 🔧 API Endpoints

### **Authentication**

| Method | Endpoint        | Description              |
|--------|-----------------|--------------------------|
| POST   | `/api/auth/register` | Register a new user       |
| POST   | `/api/auth/login`    | Log in an existing user    |
| GET    | `/api/auth/profile`  | Get user profile details   |

### **Products**

| Method | Endpoint        | Description              |
|--------|-----------------|--------------------------|
| GET    | `/api/products`       | Get all products           |
| GET    | `/api/products/:id`   | Get product by ID          |
| POST   | `/api/products`       | Create a new product (admin)|

### **Orders**

| Method | Endpoint        | Description              |
|--------|-----------------|--------------------------|
| POST   | `/api/orders`         | Create a new order          |
| GET    | `/api/orders/:id`     | Get order by ID             |

---

## 🤝 Contributing

Contributions are always welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

---

## 🖍️ License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this project as you wish. See the `LICENSE` file for more details.

---

## 📩 Contact

If you have any questions or suggestions, feel free to reach out:

- **Email**: [CodeShow LpaZ](mailto:codeshowlapz@gmail.com)  

---

## 🔥 Support

If you like this project, please consider giving it a ⭐ on GitHub! It really helps to keep the project alive and growing. 😊

---



#MERNStack #ECommerceApp #ReactJS #NodeJS #MongoDB #ExpressJS #FullStackDevelopment #WebDevelopment #OpenSource #CodingProject 
