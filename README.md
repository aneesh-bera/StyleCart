# StyleCart — Full-Stack E-Commerce Platform

StyleCart is a full-stack e-commerce web application built using the MERN stack. It allows customers to browse products, filter and search products, manage their shopping cart, place orders, and make payments. An admin panel is included for managing products and orders.

## Features

### Customer

* User registration and login
* Browse products
* Product category and type filtering
* Product search
* Price sorting
* Product details
* Add products to cart
* Increase or decrease product quantity
* Remove products from cart
* Checkout and order placement
* Stripe and Razorpay payments
* Cash on Delivery
* View orders

### Admin

* Admin authentication
* Add products
* Manage products
* View orders
* Manage order information

## Tech Stack

* **Frontend:** React.js, React Hooks
* **Backend:** Node.js, Express.js
* **Database:** MongoDB, MongoDB Atlas
* **Authentication:** JWT, bcrypt
* **Payments:** Stripe, Razorpay
* **Other:** REST APIs, Cloudinary, Multer

## Project Structure

```text
StyleCart/
├── admin/
├── frontend/
├── backend/
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd StyleCart
```

### 2. Install dependencies

Install the dependencies inside the frontend, backend, and admin directories.

```bash
npm install
```

### 3. Environment Variables

Create the required `.env` files and configure your MongoDB, JWT, Stripe, Razorpay, and other application credentials.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
```

Never commit `.env` files or secret credentials to the repository.

### 4. Run the Application

Start the backend:

```bash
npm run server
```

Start the frontend:

```bash
npm run dev
```

Run the admin panel using its configured development command.

## Authentication

JWT is used for authentication, while bcrypt is used for password hashing.

## Payments

Customers can place orders using:

* Stripe
* Razorpay
* Cash on Delivery

## Database

MongoDB is used as the application's database, with MongoDB Atlas used for database hosting.

## Author

**Aneesh Bera**

MCA Student | Full-Stack Developer | MERN Stack

