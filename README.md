# 🛺 Apni Riksha - Auto Rickshaw Booking System

[![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue)](https://mern.io/)
[![React](https://img.shields.io/badge/React-18.2.0-blue)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18.x-green)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-7.x-green)](https://www.mongodb.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, real-time auto rickshaw booking system built with the MERN stack, designed to connect passengers with drivers efficiently through seamless booking and live tracking.

## 📋 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Screenshots](#-screenshots)
- [Demo Video](#-demo-video)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

## 🔥 Features

- **Seamless Ride Booking**: Intuitive interface for quick and easy ride requests
- **Real-Time Tracking**: Leaflet-powered live location tracking for both users and drivers
- **Secure Authentication**: JWT-based authentication system for users and drivers
- **Driver Management**: Comprehensive system for drivers to accept/reject ride requests
- **Emergency Support**: Priority booking for urgent situations
- **Responsive Design**: Mobile-first UI built with React.js and Tailwind CSS
- **Real-Time Communication**: Socket.io integration for instant updates

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI library for building user interfaces
- **Tailwind CSS** - Utility-first CSS framework
- **React Leaflet** - Interactive maps for location services
- **Vite** - Fast build tool and development server

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Socket.io** - Real-time bidirectional communication

### Additional Tools
- **JWT** - JSON Web Tokens for authentication
- **Axios** - HTTP client for API requests
- **bcrypt** - Password hashing
- **Nodemon** - Development utility for auto-restarting server

## 📸 Screenshots

### Home Page
![Home Page](./images/image.png)

### User Interface
![User Login](./images/image-1.png)
![Map View](./images/image-2.png)
![Fare Estimation](./images/image-3.png)
![Ride Confirmation](./images/image-4.png)
![Looking for Driver](./images/image-8.png)
![Driver Details](./images/image-7.png)
![Ride Complete](./images/image-5.png)

### Driver (Saarthi) Interface
![Driver Registration](./images/rimage.png)
![Driver Login](./images/rimage1.png)
![Ride Request Popup](./images/rimage-2.png)
![Ride Details](./images/rimage%203.png)
![Ride Completion](./images/rimage%204.png)
![Earnings](./images/rimage%205.png)

## 🎥 Demo Video

<video width="100%" controls>
  <source src="./video/demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

*Watch the full demo video showcasing the application's features and user experience.*

## 🚀 Installation

### Prerequisites
- Node.js (v18 or higher)
- MongoDB (local or cloud instance)
- Git

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/kaustav3071/Apni-Riksha.git
   cd Apni-Riksha
   ```

2. **Install Dependencies**
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. **Environment Configuration**
   ```bash
   # Create .env files in both backend and frontend directories
   # Refer to .env.example files for required variables
   ```

4. **Start the Application**
   ```bash
   # Start backend server (from backend directory)
   npm start

   # Start frontend development server (from frontend directory)
   npm run dev
   ```

5. **Access the Application**
   - Frontend: http://localhost:5173
   - Backend API: http://localhost:4000

## 🏗️ Project Structure

```
Apni-Riksha/
├── frontend/                 # React.js frontend application
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/           # Application pages/routes
│   │   ├── context/         # React context providers
│   │   └── assets/          # Static assets
│   ├── public/              # Public static files
│   └── package.json
├── backend/                  # Node.js backend application
│   ├── controllers/         # Route controllers
│   ├── models/             # MongoDB models
│   ├── routes/             # API routes
│   ├── services/           # Business logic services
│   ├── middlewares/        # Custom middlewares
│   └── package.json
├── images/                  # Screenshots and images
├── video/                   # Demo videos
├── README.md               # Project documentation
└── LICENSE                 # MIT License
```

## 🤝 Contributing

We welcome contributions from the community! Here's how you can contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contributors

| Name | GitHub Profile | Role |
|------|----------------|------|
| **Kaustav Das** | [@kaustav3071](https://github.com/kaustav3071) | Backend, Frontend & Database |
| **Kuresh Garbada** | [@Kuresh-Garbada](https://github.com/Kuresh-Garbada) | Backend |
| **Bhavya Godhaviya** | [@Bhavya-Godhaviya](https://github.com/Bhavya-Godhaviya) | Diagrams |
| **Harsh Goswami** | [@Harshgoswamigiri](https://github.com/Harshgoswamigiri) | Documentation |

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

**Kaustav Das**
- 📧 Email: kaustavdas2027@gmail.com
- 🔗 LinkedIn: [kaustavdas1703](https://www.linkedin.com/in/kaustavdas1703/)
- 🌐 Portfolio: [kaustavdas.up.railway.app](https://kaustavdas.up.railway.app/)
- 📱 GitHub: [@kaustav3071](https://github.com/kaustav3071)

---

⭐ **Star this repository** if you found it helpful!

