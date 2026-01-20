🛍️ Fashion Store E-Commerce Website

A full-stack fashion e-commerce web application built using React, Node.js (Express), and MySQL. The platform provides a complete online shopping experience with secure authentication, product browsing, cart management, order processing, and online payments via Stripe. An admin dashboard is included for managing products and orders.

🚀 Features

👤 User Features

User registration and authentication (login/signup)

Browse fashion products with details

Add and remove products from the shopping cart

Place orders and view order history

Secure online payments using Stripe

Fully responsive UI for mobile, tablet, and desktop

🛠️ Admin Features

Admin authentication

Add, update, and delete products

Manage orders and order status

View customer and product data from the dashboard

🧱 Tech Stack
Frontend

React.js

HTML5

CSS3

JavaScript (ES6+)

Backend

Node.js

Express.js

Database

MySQL

Payment Gateway

Stripe

Project Structure Fashion-store-ecommerce/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   └── public/
│
├── .gitignore
└── README.md

⚙️ Installation & Setup
Prerequisites

Node.js (v16 or later)

MySQL

Stripe account (for payment integration)

1️⃣ Clone the Repository
git clone https://github.com/Prishita17/Fashion-store-ecommerce.git
cd Fashion-store-ecommerce

2️⃣ Backend Setup
cd backend
npm install

Create a .env file in the backend directory and add:
DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=your_database_name
STRIPE_SECRET_KEY=your_stripe_secret_key

Start the backend server:
npm start

3️⃣ Frontend Setup
cd frontend
npm install
npm start

The frontend will run at:
http://localhost:3000

🔐 Security & Best Practices

Password hashing for user security

Environment variables for sensitive data

Protected routes for admin access

Secure payment handling via Stripe

📌 Future Enhancements

Product search and filtering

Wishlist functionality

User profile management

Order tracking

Email notifications

Deployment using Docker / AWS

🎯 Purpose of the Project

This project was built to demonstrate:

Full-stack web development skills

REST API design

Secure authentication and payments

Real-world e-commerce workflow

Clean project structure and scalability


Application Screen 
Login Page

<img width="334" height="565" alt="Login" src="https://github.com/user-attachments/assets/2363165e-a5cf-44d4-9b12-f2a599efa7e4" />

Register Page

<img width="299" height="624" alt="Register Page" src="https://github.com/user-attachments/assets/92bf2715-2050-4600-9768-54a75c34b4c9" />

Admin Add new Products

<img width="830" height="410" alt="Screenshot 2026-01-20 at 7 40 58 PM" src="https://github.com/user-attachments/assets/b9bc8f02-af75-416b-b3b5-0ff8c4a9c049" />

Order Details & Product in Order

<img width="831" height="409" alt="Screenshot 2026-01-20 at 10 02 30 PM" src="https://github.com/user-attachments/assets/e32ecdf6-d780-4260-811a-a1d466452bbf" />

Order List Page

<img width="827" height="186" alt="Screenshot 2026-01-20 at 10 04 19 PM" src="https://github.com/user-attachments/assets/1fe5ab16-c1a9-45d6-ad36-977887c66d23" />


Customer Past Orders

<img width="828" height="335" alt="Screenshot 2026-01-20 at 10 40 10 PM" src="https://github.com/user-attachments/assets/85903992-32a5-427f-8d2f-958c29baff9a" />


Customer Product List Page

<img width="831" height="403" alt="Screenshot 2026-01-20 at 10 08 36 PM" src="https://github.com/user-attachments/assets/c88ebbdf-27dc-4481-b8ed-08886bf3e72f" />

Shopping Cart

<img width="832" height="121" alt="Screenshot 2026-01-20 at 10 09 44 PM" src="https://github.com/user-attachments/assets/586847d4-e542-46ab-9613-4ef35c48d05e" />



## Acknowledgement

This project was developed for learning purposes and is inspired by open-source
e-commerce projects available on GitHub


👩‍💻 Author

Prishita Singh
GitHub: Prishita17


