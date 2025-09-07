# 📇 Contact Management App

A RESTful API built with **Node.js, Express, and MongoDB** that provides contact management with user authentication and authorization.  
This project was created as part of my backend development learning journey, following REST API best practices.

---

## ✨ Features
- 🔹 REST API with Express.js
- 🔹 CRUD operations for contacts
- 🔹 User registration & login
- 🔹 Password hashing with bcrypt
- 🔹 JWT authentication & route protection
- 🔹 Relationship between users and contacts
- 🔹 MongoDB with Mongoose for data persistence
- 🔹 Error handling middleware and async handlers

---

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT (JSON Web Tokens), bcrypt
- **Testing API:** Thunder Client / Postman

---

### 🔑 Auth
- `POST /api/users/register` → Register new user  
- `POST /api/users/login` → Login user & get JWT  
- `GET /api/users/current` → Get current logged-in user  

### 📇 Contacts
- `GET /api/contacts` → Get all contacts (user-specific)  
- `POST /api/contacts` → Create new contact  
- `GET /api/contacts/:id` → Get contact by ID  
- `PUT /api/contacts/:id` → Update contact  
- `DELETE /api/contacts/:id` → Delete contact  

---
## ⚙️ Installation & Setup
1. Clone the repository:
   git clone https://github.com/MateoGomez11/contacts-backend
2. Install dependencies:
   npm install
3. Create a .env file in the root directory:
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
4. Run the server:
   npm run dev
5. Test API with Thunder Client or Postman.

🧠 What I Learned
<ul>
  <li>How to structure a Node.js & Express backend project</li>
  <li>REST API conventions and route handling</li>
  <li>Middleware for error handling and authentication</li>
  <li>Using MongoDB & Mongoose for database design</li>
  <li>Implementing JWT authentication and securing routes</li>
  <li>Managing relationships between users and contacts</li>
</ul>









