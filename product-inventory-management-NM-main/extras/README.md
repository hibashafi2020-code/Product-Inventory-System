

# Product Inventory Management System

## Project Overview

This project is a **backend REST API** developed using **Node.js, Express.js, and MongoDB**.
The system allows users to manage product inventory through API requests. It includes authentication features and CRUD operations for product management.

The application demonstrates how backend services can be used to store, retrieve, update, and delete product information using a database.

---

## Features

* User Registration
* User Login
* Create Product
* View All Products
* Update Product Details
* Delete Product
* Secure API using JWT Authentication

---

## Technologies Used

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* Thunder Client (for API testing)

---

## Project Structure

```
server/
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   └── db/
│
├── server.js
├── package.json
└── package-lock.json
```

---

## API Endpoints

### Authentication

* **POST /api/v1/auth/register** – Register a new user
* **POST /api/v1/auth/login** – Login user and receive authentication token

### Product Management

* **POST /api/v1/products** – Create a new product
* **GET /api/v1/products** – Get all products
* **PUT /api/v1/products/:id** – Update product information
* **DELETE /api/v1/products/:id** – Delete a product

---

## How to Run the Project

1. Install dependencies

```
npm install
```

2. Start the server

```
npm run dev
```

3. Server will run on

```
http://localhost:5000
```

---

## Database

This project uses **MongoDB** as the database to store user information and product inventory data.

---

## Demo Video

[https://drive.google.com/file/d/1lt60FtEtbYsa1YTDc2wmisFEEXR41yco/view?usp=sharing](https://drive.google.com/file/d/1lt60FtEtbYsa1YTDc2wmisFEEXR41yco/view?usp=sharing)

---

## Author

Team ID: **SWTID-2026-9368**
Project: **Product Inventory Management System**

