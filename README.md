# 🛒 Amazon Clone - E-Commerce Platform

A full-stack e-commerce web application inspired by Amazon, built using React, Node.js, Express, and PostgreSQL. The app allows users to browse products, manage cart items, and place orders with a smooth user experience.

---

## 🚀 Tech Stack

* **Frontend:** React.js
* **Backend:** Node.js + Express.js
* **Database:** PostgreSQL
* **State Management:** React Context API
* **API Handling:** Axios

---

## ✨ Features

### ✅ Core Features

* Product listing with grid layout
* Search products by name
* Filter products by category
* Product detail page with image carousel
* Add to cart / Buy now functionality
* Shopping cart (update quantity, remove items)
* Checkout with shipping form
* Order placement with database transaction
* Order confirmation page

### ⭐ Bonus Features

* Order history page (view past orders)
* Session-based user handling (no login required)

---

## 📂 Project Structure

```
amazon-clone/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── seed/
│   ├── server.js
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── api/
│   │   ├── App.js
│   │   └── index.js
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 🔧 Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```
PORT=5000
DB_USER=postgres
DB_HOST=localhost
DB_NAME=amazon_clone
DB_PASSWORD=your_password
DB_PORT=5432
```

Run:

```bash
npm run seed
npm run dev
```

---

### ⚛️ Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 🗃️ Database

* PostgreSQL database with relational schema
* Tables:

  * Products
  * Categories
  * Cart
  * Orders
  * Order Items

---

## 📌 Assumptions

* Default user handled using `session_id`
* No authentication required (as per assignment)
* Flat shipping charge applied
* Sample data seeded for testing

---

## 🎯 Future Improvements

* User authentication (JWT)
* Payment integration (Razorpay/Stripe)
* Admin dashboard
* Order tracking system
* Wishlist feature
* Deployment (Vercel + Render)


