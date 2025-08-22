# Courier-Management-System
A MERN stack Courier Management System where users can book couriers, track packages, and admins can assign deliveries to agents. Includes role-based dashboards and real-time status updates.
# 🚚 Courier Management System (MERN)

A full-stack **Courier Management System** built with **MERN stack (MongoDB, Express, React, Node.js)**.  
This project allows **Users** to book and track couriers, **Admins** to manage shipments and agents, and **Delivery Agents** to update delivery status in real time.

---

## 📌 Features

### 👤 User
- Register & Login
- Book courier (pickup & delivery details, package weight, etc.)
- Get a unique **Tracking ID**
- Track courier status
- View booking history

### 🛠 Admin
- Manage all couriers
- Assign couriers to delivery agents
- Update courier status
- View analytics (daily orders, completed deliveries)

### 🚴 Delivery Agent
- View assigned deliveries
- Update delivery progress (Picked, In Transit, Delivered, Cancelled)

---

## 🗄 Database Models (MongoDB)

**User**
json
{
  "name": "Ray",
  "email": "ray@example.com",
  "password": "hashed",
  "role": "customer | admin | agent"
}
---------------------------------------------------
⚙️ Tech Stack

Frontend: React, Tailwind CSS (or Bootstrap/Material UI)

Backend: Node.js, Express

Database: MongoDB, Mongoose

Authentication: JWT, bcrypt

Optional: Google Maps API, Email/SMS notifications
-------------------------------------------------------
📊 Roadmap
......................
 Step1 : User dashboard

 Step2 : Admin panel

 Step3 : Agent panel

 Step4 : Tracking page

 Step5 : Authentication

 Step6 : Notifications (Email/SMS)

 Step6 : Analytics dashboard
