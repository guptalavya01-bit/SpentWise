# SpendWise — Personal Finance Tracker

SpendWise is a full stack expense tracking web application that helps users manage their personal finances by tracking income and expenses, visualizing spending patterns, and staying on top of their financial health.

## Live Demo

[spendwise-lavya.vercel.app
]()


## Features

- **Secure Authentication** — Sign up and login with JWT based authentication, with a Remember Me option for persistent sessions.
- **Income & Expense Tracking** — Add, edit, delete, and categorize income and expense entries.
- **Interactive Dashboard** — Visual overview of total balance, income, and expenses with charts.
- **Category-wise Breakdown** — Track spending across different categories to understand where money goes.
- **Search & Filter** — Real time search to quickly find specific transactions by description.
- **Profile Management** — Update personal details and account information.
- **Responsive Design** — Clean, mobile friendly UI built with Tailwind CSS.

## Tech Stack

**Frontend:** React, Vite, Tailwind CSS
**Backend:** Node.js, Express.js
**Database:** MongoDB (Mongoose)
**Authentication:** JWT (JSON Web Tokens), bcrypt for password hashing

## Project Structure

```
SpendWise/
├── frontend/          # React + Vite client
│   ├── src/
│   │   ├── components/    # Sidebar, Navbar, Login, Signup, etc.
│   │   ├── pages/          # Dashboard, Income, Expense, Profile
│   │   └── assets/
└── backend/           # Express + MongoDB server
    ├── controllers/
    ├── models/         # User, Income, Expense schemas
    ├── routes/
    └── middleware/      # JWT auth middleware
```

## Getting Started

### Prerequisites
- Node.js installed
- MongoDB Atlas account (or local MongoDB)

### Backend Setup
```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=4000
```

Run the server:
```bash
npm start
```

### Frontend Setup
```bash
cd frontend
npm install
```

Run the development server:
```bash
npm run dev
```

## How It Works

1. Users sign up and log in securely using JWT authentication.
2. Income and expenses are added with description, amount, category, and date.
3. The dashboard aggregates this data to show total balance, income, and expense summaries with charts.
4. Users can search, filter, edit, or delete any transaction at any time.

## Author

Built by Lavya Gupta as part of a full stack development portfolio project.
