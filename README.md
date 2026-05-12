# ShopHub E-Commerce Platform

A modern e-commerce website built with React.js, Tailwind CSS, Node.js, Express, and MongoDB.

## Project Structure

- `frontend/` - React application with Tailwind CSS and routing
- `backend/` - Express API server with MongoDB schemas, authentication, and admin routes
- `.gitignore` - Repository ignore rules

## Features

- Professional homepage and product catalog
- Product categories, filters, and search
- Product detail and shopping cart
- Checkout flow with Stripe payment integration (placeholder)
- Order management
- JWT authentication and registration
- Admin dashboard for managing products, orders, and users
- Full admin product management (add, edit, delete products)
- Product reviews, wishlist, and stock management
- Email/contact form placeholder
- Dark/light mode toggle and responsive design
- API documentation in `backend/README.md`

## Setup

### Backend

1. Navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Copy the sample environment file:
   ```bash
   copy .env.example .env
   ```
4. Update `.env` with your MongoDB credentials, JWT secret, and Stripe secret key.
5. Seed the database:
   ```bash
   npm run seed
   ```
6. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend

1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Copy the sample environment file:
   ```bash
   copy .env.example .env
   ```
4. Update `.env` with your Stripe publishable key if needed.
5. Start the frontend app:
   ```bash
   npm start
   ```

## Running the App

- Frontend: `http://localhost:3000`
- Backend: `http://localhost:5000`

## Demo Accounts

- Admin: `admin@example.com` / `admin@123456`
- Customer: `john@example.com` / `customer@123`

## Deployment Guides

- Frontend: Vercel
- Backend: Render or Railway
- Database: MongoDB Atlas

For full backend API docs, see `backend/README.md`.
