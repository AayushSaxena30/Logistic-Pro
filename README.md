# Logistic-Pro
Logistics Pro Advanced: A full-stack logistics system with real-time fleet tracking, warehouse and inventory management, shipment automation, and an integrated AI assistant. Modern UI, secure backend, and scalable design for efficient supply chain operations.

**📌 Overview**

This system was developed with the objective of bringing clarity and control to warehouse workflows.
It focuses on reliability, modularity, and ease of maintenance. Each component — from authentication to inventory — is organized with a clean separation of responsibilities.

LogisticPro enables teams to:

Manage warehouse items and stock levels

Track shipments and operational activities

Maintain secure, role-based user access

Streamline day-to-day logistics tasks

**🛠 System Features
Authentication & Authorization**

Secure JWT-based login

Role-based access control

Middleware-based request validation

Warehouse & Inventory Module

Product creation, updates, and removal

Category-based organization

Real-time stock availability

Shipment Tracking

Creation and assignment of shipments

Status monitoring across workflow stages

Structured shipping data for transparency

**User Management**

Add/edit/remove users

Assign permission roles

Audit-friendly organization of user activity

Modular Backend Architecture

Controller-service-model structure

Scalable and easy to extend

Clean and predictable routing

**📁 Directory Structure**

LogisticPro/
│── server.js            # Entry point
│── package.json
│── .env
│── models/              # Mongoose schemas
│── controllers/         # Application logic
│── routes/              # API endpoints
│── services/            # Business services
│── middleware/          # Auth + security layers
│── public/              # Frontend UI

**🚀 Getting Started**

1. Install Dependencies
npm install

2. Configure Environment Variables

Create a .env file in the root directory:

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key

3. Run the Application
npm start


Server runs at:
http://localhost:5000

**🌐 API Summary**

Auth

POST /auth/login

POST /auth/register

Users

GET /users

PUT /users/:id

DELETE /users/:id

Warehouse

GET /warehouse

POST /warehouse

PUT /warehouse/:id

DELETE /warehouse/:id

Products

GET /products

POST /products

PUT /products/:id

DELETE /products/:id

**🧰 Technology Stack**

Node.js / Express — Backend framework

MongoDB / Mongoose — Database layer

HTML / CSS / JavaScript — Frontend

Security: Helmet, CORS, Rate Limiting, Compression

**📄 License**

This project is licensed under the MIT License.
