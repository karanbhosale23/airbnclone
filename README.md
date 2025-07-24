
# Hotel Booking LMS

This project is a full-stack Hotel Booking Learning Management System (LMS) built with a React frontend and Node.js/Express backend. It allows users to search, book hotels, and manage bookings with authentication and MongoDB for data storage.

## Features
- User authentication (JWT-based)
- Hotel search and booking
- User profile management
- Comment and rating system
- Responsive UI with modern design
- RESTful API backend

## Tech Stack
- **Frontend:** React, Vite
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT

## Getting Started

### Prerequisites
- Node.js & npm
- MongoDB (local or cloud)

### Installation
1. Clone the repository:
   ```sh
   git clone <repo-url>
   ```
2. Install dependencies for both frontend and backend:
   ```sh
   cd hotelbooking/backend
   npm install
   cd ../frontend
   npm install
   ```
3. Set up environment variables in `backend/.env`:
   ```env
   MONGO_URI=mongodb://localhost:27017/LMShotel
   JWT_SECRET=<your_jwt_secret>
   PORT=5000
   ```

### Running the App
1. Start MongoDB server.
2. Start the backend server:
   ```sh
   cd hotelbooking/backend
   npm start
   ```
3. Start the frontend:
   ```sh
   cd hotelbooking/frontend
   npm run dev
   ```
4. Visit [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure
```
hotelbooking/
  backend/      # Node.js/Express API
  frontend/     # React app (Vite)
```

## Environment Variables
See `backend/.env` for MongoDB URI, JWT secret, and port configuration.

## License
This project is licensed under the MIT License.
