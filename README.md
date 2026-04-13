# Social Media Backend API

A production-style social media backend built with Node.js, Express, MongoDB, and JWT Authentication.

## Features
- User Registration & Login
- JWT Protected Routes
- Follow / Unfollow Users
- Create Posts
- Like Posts
- Comment on Posts
- MongoDB Database Integration
- Modular MVC Architecture

## Tech Stack
- Node.js
- Express.js
- MongoDB / Mongoose
- JWT Authentication
- bcryptjs

## Installation
```bash
git clone <your-repo-url>
cd social-media-backend
npm install
```

## Environment Variables
Create `.env` file:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
```

## Run Project
```bash
npm run dev
```

## API Endpoints

### Auth Routes
#### Register User
`POST /api/auth/register`
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "123456"
}
```

#### Login User
`POST /api/auth/login`
```json
