# Flight Reservation Platform with Fair-Queue Booking Engine

A **full-stack flight discovery and reservation system** that ensures **fair, race-free seat allocation** using a **queue-based booking engine**. Built with the **MERN stack**, this project demonstrates scalable architecture, secure authentication, and real-time concurrency control.


## ✨ Key Features

- **Secure User Authentication** – JWT-based registration & login with protected routes  
- **Smart Flight Search** – Filter by origin, destination, and departure date  
- **Fair-Queue Booking System** – Serializes concurrent bookings to prevent overbooking  
- **User Dashboard** – View and manage all confirmed flight reservations  
- **Responsive Design** – Mobile-first UI with React + Tailwind CSS (optional)  
- **Modular MERN Architecture** – Clean separation of frontend and backend



---

## 🛠 Tech Stack

| Layer      | Technology                          |
|-----------|-------------------------------------|
| Frontend  | React.js, Vite, Context API         |
| Backend   | Node.js, Express.js                 |
| Database  | MongoDB (Mongoose ODM)              |
| Auth      | JSON Web Tokens (JWT)               |
| Queue     | In-memory queue with persistence    |
| Styling   | CSS Modules / Tailwind (optional)   |

---

## 🚀 Full Installation & Run Commands

```bash
# 1. Clone your repository
git clone https://github.com/your-username/flight-reservation-platform.git
cd flight-reservation-platform

# 2. Install backend dependencies
cd backend
npm install

# 3. Install frontend dependencies
cd ../frontend
npm install

# 4. Set up environment variables (backend)
cd ../backend
cp .env.example .env

Start Both Servers
Terminal 1 – Backend
cd backend
npm run dev

Server runs on: http://localhost:5000

Terminal 2 – Frontend
cd frontend
npm run dev

App runs on: http://localhost:5173
```
How to Use

Open http://localhost:5173
.Register a new account or log in
.Use Search Flights to find available routes
.Click "Book Now" — your request enters the fair queue
.Receive instant confirmation when seat is reserved
.Go to My Flights to view all bookings


Multiple users booking the same seat? Only one wins — fairly and transparently.

