

```markdown
# 💍 Jewellery E-Commerce Website

An online jewellery e-commerce platform where users can browse, search, and purchase jewellery items.  
Built with **MERN Stack** — MongoDB, Express.js, React.js, Node.js.

---

## ✨ Features

✅ User Registration and Login (JWT Authentication)  
✅ Jewellery Product Listing  
✅ Product Search & Filtering  
✅ Detailed Product Page  
✅ Shopping Cart  
✅ Checkout and Payment  
✅ Order History  
✅ Wishlist Management  
✅ Admin Panel to Add/Edit/Delete Products  
✅ Responsive UI (Mobile & Desktop)  
✅ RESTful API  

---

## 🛠️ Tech Stack

**Frontend**:
- React.js
- Bootstrap
- Context API

**Backend**:
- Node.js
- Express.js
- MongoDB (Atlas)
- Mongoose ODM
- JWT (Authentication)

---

## 📂 Project Structure

```

jew-backend/   → Node.js + Express + MongoDB (API Server)
jew-frontend/  → React.js (Client Side UI)

```

---

### 🔸 Backend Structure

```

jew-backend/
├── config/ (Environment Variables)
├── controllers/ (Business Logic)
├── data/ (Sample Data)
├── models/ (MongoDB Models)
├── routes/ (API Routes)
├── index.js (Entry Point)
├── package.json

```

**Key API Routes**:
- `/userRoutes.js`
- `/jewelleryRoutes.js`
- `/cartRoutes.js`
- `/orderRoutes.js`
- `/wishlistRoutes.js`
- `/paymentRoutes.js`

---

### 🔸 Frontend Structure

```

jew-frontend/
├── src/
│   ├── Components/
│   ├── contexts/
│   ├── data/
│   ├── Pages/
│   ├── App.jsx
│   ├── index.js
├── public/
├── package.json

````

**Main Pages**:
- Home
- Products
- Cart
- Checkout
- Orders
- Wishlist
- Add Jewellery (Admin)
- MerchantPage
- Login / Register
- Profile
- Privacy Policy
- FAQ / Terms & Conditions

---

## 🚀 Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Lalasa1501/jewellery-website.git
````

---

### 2️⃣ Backend Setup

```bash
cd jew-backend
npm install
```

Create `.env` file in `jew-backend/config/`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start backend server:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd ../jew-frontend
npm install
```

Start React frontend:

```bash
npm run dev
```

---

## 🌐 Running the App

1️⃣ Start Backend:

```bash
cd jew-backend
npm start
```

2️⃣ Start Frontend:

```bash
cd ../jew-frontend
npm run dev
```

3️⃣ Open browser:

```text
http://localhost:3000
```

---

