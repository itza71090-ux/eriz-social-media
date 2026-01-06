# Eriz Social Media

A modern, feature-rich social media platform built with cutting-edge web technologies. Connect, share, and engage with a vibrant community.

## 📋 Project Overview

Eriz Social Media is a full-stack web application designed to provide users with a seamless social networking experience. The platform enables users to create profiles, share content, connect with others, and engage through comments, likes, and real-time interactions.

Whether you're looking to build a personal brand, connect with friends, or engage with a community, Eriz Social Media provides all the tools you need in a modern, intuitive interface.

## ✨ Features

- **User Authentication & Profiles**
  - Secure user registration and login
  - Customizable user profiles with profile pictures and bios
  - User discovery and search functionality

- **Content Sharing**
  - Create, edit, and delete posts
  - Support for text, images, and media uploads
  - Share posts with personalized captions and hashtags

- **Social Interactions**
  - Like and unlike posts
  - Comment on posts with real-time updates
  - Follow/unfollow users to customize your feed
  - Real-time notifications for user activities

- **Feed & Discovery**
  - Personalized home feed based on followed users
  - Trending hashtags and popular content
  - Search posts, users, and hashtags

- **Messaging**
  - Direct messaging between users
  - Real-time chat functionality
  - Message history and search

- **User Experience**
  - Responsive design for mobile and desktop
  - Dark/light theme support
  - Infinite scroll pagination
  - Fast and optimized performance

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI library for building interactive components
- **Redux/Context API** - State management
- **Axios** - HTTP client for API requests
- **Tailwind CSS / Material-UI** - Styling and UI components
- **React Router** - Client-side routing

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - ODM for MongoDB
- **JWT** - Authentication and authorization
- **Socket.io** - Real-time communication

### DevOps & Tools
- **Git** - Version control
- **Docker** - Containerization
- **Webpack** - Module bundler
- **Jest** - Testing framework
- **ESLint** - Code linting

## 🚀 Setup Instructions

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or cloud instance)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/itza71090-ux/eriz-social-media.git
   cd eriz-social-media
   ```

2. **Install dependencies**
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. **Environment Variables**

   Create a `.env` file in the `backend` directory:
   ```env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/eriz-social-media
   JWT_SECRET=your_jwt_secret_key_here
   NODE_ENV=development
   CORS_ORIGIN=http://localhost:3000
   ```

   Create a `.env` file in the `frontend` directory:
   ```env
   REACT_APP_API_URL=http://localhost:5000/api
   REACT_APP_SOCKET_URL=http://localhost:5000
   ```

4. **Start MongoDB**
   ```bash
   # If using local MongoDB
   mongod
   ```

5. **Start the backend server**
   ```bash
   cd backend
   npm start
   # Server runs on http://localhost:5000
   ```

6. **Start the frontend development server**
   ```bash
   cd frontend
   npm start
   # Application runs on http://localhost:3000
   ```

### Running Tests

```bash
# Run backend tests
cd backend
npm test

# Run frontend tests
cd frontend
npm test
```

### Building for Production

```bash
# Build the frontend
cd frontend
npm run build

# The backend is ready for deployment as-is
```

## 📁 Project Structure

```
eriz-social-media/
├── backend/
│   ├── src/
│   │   ├── models/        # Database schemas
│   │   ├── routes/        # API endpoints
│   │   ├── controllers/    # Business logic
│   │   ├── middleware/     # Custom middleware
│   │   ├── utils/          # Helper functions
│   │   └── server.js       # Main server file
│   ├── .env                # Environment variables
│   └── package.json        # Dependencies
├── frontend/
│   ├── src/
│   │   ├── components/     # Reusable components
│   │   ├── pages/          # Page components
│   │   ├── redux/          # Redux store and slices
│   │   ├── api/            # API service calls
│   │   ├── utils/          # Helper functions
│   │   └── App.js          # Main App component
│   ├── public/             # Static files
│   └── package.json        # Dependencies
├── docker-compose.yml      # Docker configuration
└── README.md               # This file
```

## 🤝 Contributing Guidelines

We welcome contributions from the community! To contribute to Eriz Social Media, please follow these guidelines:

### Getting Started

1. **Fork the repository**
   - Click the "Fork" button on the repository page

2. **Clone your fork**
   ```bash
   git clone https://github.com/your-username/eriz-social-media.git
   cd eriz-social-media
   ```

3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Development Workflow

1. **Make your changes**
   - Write clean, readable code
   - Follow the existing code style and conventions
   - Add comments for complex logic

2. **Test your changes**
   ```bash
   npm test
   ```

3. **Commit your changes**
   ```bash
   git commit -m "feat: add your feature description"
   ```
   Use conventional commit messages:
   - `feat:` for new features
   - `fix:` for bug fixes
   - `docs:` for documentation
   - `style:` for code style changes
   - `refactor:` for code refactoring
   - `test:` for adding tests

4. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Create a Pull Request**
   - Go to the original repository and click "New Pull Request"
   - Select your feature branch
   - Fill in the PR title and description
   - Link any related issues

### Pull Request Guidelines

- Keep PRs focused on a single feature or fix
- Provide a clear description of what your PR does
- Reference any related issues (e.g., "Fixes #123")
- Include screenshots or GIFs for UI changes
- Ensure all tests pass
- Update documentation if needed

### Code Style

- Follow ESLint rules configured in the project
- Use meaningful variable and function names
- Keep functions small and focused
- Add JSDoc comments for public APIs

### Reporting Issues

- Use GitHub Issues to report bugs
- Provide a clear title and description
- Include steps to reproduce
- Add screenshots or error logs if applicable
- Specify your environment (OS, Node version, etc.)

### Community Guidelines

- Be respectful and inclusive
- No harassment or discrimination
- Constructive criticism only
- Ask questions if you're unsure about anything

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 💬 Support

Have questions or need help? 

- Open an issue on GitHub
- Check existing issues and discussions
- Join our community chat (if available)

## 🙌 Acknowledgments

Thank you to all contributors who have helped make Eriz Social Media better!

---

**Happy coding! 🚀**

Last Updated: January 6, 2026
