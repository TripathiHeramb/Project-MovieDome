# MovieDome 🎬

MovieDome is a modern, full-stack movie application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides users with a seamless experience to explore, search, and interact with movie information.

## 🌟 Features

- User authentication and authorization
- Browse extensive movie catalog
- Search movies by title, genre, or cast
- View detailed movie information
- Save favorite movies
- Rate and review movies
- Responsive design for all devices

## 🛠️ Technology Stack

### Frontend
- React.js - A JavaScript library for building user interfaces
- Redux - State management
- Material-UI - Modern UI components
- Axios - HTTP client for API requests

### Backend
- Node.js - JavaScript runtime environment
- Express.js - Web application framework
- MongoDB - NoSQL database
- JWT - Authentication mechanism

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn package manager

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/MovieDome.git
cd MovieDome
```

2. Install dependencies for backend
```bash
cd backend
npm install
```

3. Install dependencies for frontend
```bash
cd ../frontend
npm install
```

4. Create a .env file in the backend directory with the following variables:
```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

5. Start the development servers

For backend:
```bash
cd backend
npm run dev
```

For frontend:
```bash
cd frontend
npm start
```

## 🏗️ Project Structure

```
MovieDome/
├── backend/
│   ├── controllers/    # Request handlers
│   ├── models/        # Database models
│   ├── routes/        # API routes
│   ├── middleware/    # Custom middleware
│   └── server.js      # Entry point
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/    # Reusable components
│       ├── pages/        # Page components
│       ├── redux/        # State management
│       ├── services/     # API services
│       └── App.js        # Root component
```

## 🔄 API Endpoints

### Authentication
- POST /api/auth/register - Register new user
- POST /api/auth/login - User login

### Movies
- GET /api/movies - Get all movies
- GET /api/movies/:id - Get movie by ID
- POST /api/movies/search - Search movies
- POST /api/movies/favorite - Add to favorites
- DELETE /api/movies/favorite/:id - Remove from favorites

## 👥 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- [The Movie Database (TMDb)](https://www.themoviedb.org/) for movie data
- All contributors who have helped this project grow

