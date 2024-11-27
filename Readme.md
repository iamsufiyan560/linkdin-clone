# LinkedIn Clone - Full Stack Social Networking Application

## 📝 Project Overview

This is a full-stack LinkedIn clone built using the MERN (MongoDB, Express.js, React.js, Node.js) stack, designed to replicate core professional networking features with modern web technologies.

## 🚀 Features

### Authentication

- User registration and login
- JWT-based authentication
- Secure password hashing
- Cookie-based authentication management

### User Profile

- Create and edit professional profiles
- Upload profile pictures
- Add work experience
- Include educational background
- Skills and endorsements

### Connections

- Send and accept connection requests
- View and manage professional network
- Suggested connections based on profile

### Posts

- Create text and image posts
- Like and comment on posts
- Real-time feed updates
- Post privacy settings

### Notifications

- Real-time notifications for:
  - Connection requests
  - Post interactions
  - Profile view alerts

## 🛠 Tech Stack

### Frontend

- React.js
- React Router
- Tailwind CSS
- React Query
- Axios for API calls

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose ODM
- JSON Web Tokens (JWT)
- bcrypt for password encryption

### State Management

- Context API
- React Hooks

### Additional Libraries

- cookie-parser
- dotenv
- cors

## 📦 Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB

## 🔧 Installation

1. Clone the repository

```bash
git clone https://github.com/iamsufiyan560/linkdin-clone.git
cd linkedin-clone
```

2. Install backend dependencies

```bash
cd backend
npm install
```

3. Install frontend dependencies

```bash
cd frontend
npm install
```

4. Create .env file in backend directory

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

5. Run the application

```bash
# Run backend (from backend directory)
npm run dev

# Run frontend (from frontend directory)
npm run dev
```

## 🌐 Deployment

- Backend deployed on render/heroku
- Frontend deployed on vercel/netlify
- Database hosted on MongoDB Atlas

## 🔒 Security Features

- Password encryption
- JWT authentication
- Protected routes
- CORS configuration
- Input validation
- Environment-based configuration

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Contact

SUFIYAN CHAUDHARI - msufiyanhusen@gmail.com

Project Link: [https://github.com/iamsufiyan560/linkdin-clone.git](https://github.com/iamsufiyan560/linkdin-clone.git)
