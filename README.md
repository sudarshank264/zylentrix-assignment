# 🛠️ User Management REST API

A simple **RESTful API** built with **Node.js and Express** that provides CRUD (Create, Read, Update, Delete) operations for managing users. This API allows you to create, retrieve, update, and delete users stored in a **MongoDB database**.

## 🚀 Features

✅ Create a new user  
✅ Retrieve all users  
✅ Get details of a specific user by ID  
✅ Update user details  
✅ Delete a user  
✅ Proper error handling  
✅ Clean and structured code  

---

## 🏗️ Tech Stack

- **Backend:** Node.js, Express.js
- **Dependencies:** cors, dotenv, mongoose, morgan,nodemon
- **Database:** MongoDB (Mongoose ORM)   
- **Development Tools:** Postman, Nodemon  

---

**Install Dependencies**
npm install

**Configure Environment Variables**

PORT=4000

MONGO_URI=your_mongodb_connection_string

**Start the Server**

npm run dev

**The API will be running at**

http://localhost:4000/api/users

📌 **API Endpoints**

1️⃣ **Create a User**

Method: POST

URL: /api/users

2️⃣ **Retrieve All Users**

Method: GET

URL: /api/users

3️⃣ **Retrieve a Single User by ID**

Method: GET

URL: /api/users/:id

Example: /api/users/67db32fa7d1182ee2aec216b

4️⃣ **Update a User**

Method: PUT

URL: /api/users/:id

Example: /api/users/67db32fa7d1182ee2aec216b

5️⃣ **Delete a User**

Method: DELETE

URL: /api/users/:id

Example: /api/users/67db1841cb31dc78f1517708

🛠️ **Tools Required**

Node.js

MongoDB (for database)

Postman (for API testing)

📧 Contact

👨‍💻 Sudarshan Kumar

📧 Email: sudarshank264@gmail.com

🔗 LinkedIn:https://www.linkedin.com/in/sudarshank264/







