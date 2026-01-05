# Ride Hailing System 

A full-stack ride hailing web application inspired by platforms like Uber, built using the MERN stack.  
The system supports user and captain authentication, protected routes, and real-time ride flow management.

---

##  Features

- User & Captain authentication (signup/login/logout)
- Role-based protected routes
- Ride booking and ride state management
- Separate user and captain dashboards
- Responsive UI built with Tailwind CSS
- Modular and scalable frontend architecture

---

##  Tech Stack

**Frontend**
- React (Vite)
- Tailwind CSS
- React Router

**Backend**
- Node.js
- Express.js
- MongoDB

**Other**
- RESTful APIs
- JWT-based authentication

---

##  Project Structure

```
ride-hailing/
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   └── utils/
│   └── tailwind.config.js
├── backend/
│   ├── routes/
│   ├── controllers/
│   └── models/
└── README.md
```

---

##  Getting Started

### Prerequisites
- Node.js
- npm
- MongoDB

---

### Installation

Clone the repository:
```bash
git clone https://github.com/shinhanucaha/ride-hailing.git
cd ride-hailing
```

Install dependencies:

```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
```

---

### Run the application

```bash
# Backend
npm start

# Frontend
npm run dev
```

---

##  Environment Variables

Create a `.env` file in the backend directory and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

##  Future Improvements

- Real-time location tracking
- Socket-based live ride updates
- Payment gateway integration
- Admin dashboard

---

##  Author

**Pawan Yadav**  
Final-year undergraduate | Aspiring Software Engineer

