# 🚗 RideX - Smart Ride-Sharing Platform

<div align="center">
  <img src="https://img.shields.io/badge/Next.js-15.5.4-black?style=for-the-badge&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/Node.js-18+-green?style=for-the-badge&logo=node.js" alt="Node.js" />
  <img src="https://img.shields.io/badge/MongoDB-6.0-green?style=for-the-badge&logo=mongodb" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Tailwind CSS" />
</div>

---

## 🌐 Project Links

- **Frontend Repository**: [GitHub - RideX Frontend](https://github.com/yourusername/ridex-frontend)
- **Backend Repository**: [GitHub - RideX Backend](https://github.com/yourusername/ridex-backend)
- **Live Demo**: [Coming Soon]

---

## 📋 Project Overview

**RideX** is a comprehensive ride-sharing platform that connects riders with drivers in real-time, providing a seamless transportation experience similar to Uber and Pathao. The platform supports multiple vehicle types including bikes, cars, and CNG vehicles, serving users across different regions.

Built with modern technologies, RideX offers a complete ecosystem with user authentication, real-time tracking, payment processing, chat functionality, and analytics dashboard.

## 🎯 Main Goals

- **Connect Users & Drivers**: Create a reliable platform for ride booking and driver matching
- **Real-time Tracking**: Provide live location tracking and route optimization
- **Seamless Payments**: Integrate secure payment processing with multiple options
- **User Experience**: Deliver an intuitive, responsive interface for all devices
- **Safety & Trust**: Implement rating systems and communication features

## 🚀 Key Features

### 🗺️ **Smart Ride Booking System**
- Interactive map integration with location selection
- Dynamic fare calculation based on distance and vehicle type
- Support for multiple vehicle options (Bike, Car, CNG)
- Location autocomplete with geocoding
- Road-following routes with OSRM integration

### 📍 **Live Tracking & Navigation**
- Real-time location updates with driver tracking
- Interactive map markers with custom vehicle icons
- ETA calculations for accurate arrival time predictions
- Route optimization for shortest path calculation

### 💳 **Advanced Payment System**
- Multiple payment methods support (Cash, Card, Digital wallets)
- Secure transaction processing with encryption
- Automatic receipt generation
- Complete payment history and analytics

### ⭐ **Review & Rating System**
- 5-star interactive rating system
- Comment functionality with character limits
- Driver performance analytics
- Review history tracking

### 💬 **Real-time Communication**
- In-app chat system between riders and passengers
- Support chat for user assistance
- Message notifications with real-time alerts
- Persistent chat history

### 📊 **Dynamic Analytics Dashboard**
- User dashboard with ride statistics and spending analytics
- Rider dashboard with earnings and performance metrics
- Admin dashboard with platform-wide statistics
- Interactive charts with data visualization

### 🔔 **Notification System**
- Ride status updates in real-time
- Message alerts with toast notifications
- Support notifications for important messages
- System announcements and alerts

### 🎨 **Modern UI/UX**
- Responsive design for all device sizes
- Dark/light theme switching capability
- Skeleton loading states for better UX
- Smooth animations and transitions
- Consistent design with modern components

## 🛠️ Technology Stack

### **Frontend** ([RideX-Frontend](https://github.com/yourusername/ridex-frontend))
- **Next.js 15.5.4** - React framework with App Router
- **React 19** - UI library with hooks and functional components
- **Tailwind CSS 4** - Utility-first CSS framework
- **Shadcn UI** - Modern component library
- **Leaflet** - Interactive map integration
- **Socket.IO Client** - Real-time WebSocket communication
- **Recharts** - Data visualization
- **Axios** - HTTP client for API requests

### **Backend** ([RideX-Backend](https://github.com/yourusername/ridex-backend))
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database for data storage
- **Mongoose** - MongoDB object modeling
- **Socket.IO** - Real-time bidirectional communication
- **JWT** - Authentication and authorization
- **Bcrypt** - Password hashing for security

## 🏗️ Project Structure

```
TEAM PROJECT/
├── RideX-Frontend/              # Next.js Frontend Application
│   ├── src/
│   │   ├── app/                 # App Router pages and layouts
│   │   ├── components/          # Reusable UI components
│   │   ├── utils/               # Utility functions and API instances
│   │   └── lib/                 # Library functions
│   ├── public/                  # Static assets
│   └── ...                      # Configuration files
│
└── ridex-backend/               # Node.js Backend API
    ├── controllers/             # Request handlers and business logic
    ├── routes/                  # API route definitions
    ├── models/                  # Mongoose data models
    ├── middleware/              # Custom middleware functions
    ├── config/                  # Configuration files
    ├── socket/                  # WebSocket event handlers
    └── utils/                   # Helper functions
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ installed
- MongoDB database (local or cloud)
- npm or yarn package manager

### Frontend Setup
```bash
# Navigate to frontend directory
cd RideX-Frontend

# Install dependencies
npm install

# Create environment file
cp .env.local.example .env.local
# Update environment variables as needed

# Run development server
npm run dev
```

### Backend Setup
```bash
# Navigate to backend directory
cd ridex-backend

# Install dependencies
npm install

# Create environment file
cp .env.example .env
# Update environment variables as needed

# Run development server
npm run dev
```

## 📱 Key Pages & Functionality

### User Side
- **Home Page** - Main landing page with featured services
- **Sign In / Register** - User authentication system
- **Dashboard** - User profile and ride management
- **Ride Booking** - Interactive map-based booking system
- **Payment Processing** - Secure payment handling
- **Ride History** - Past ride records and receipts
- **Reviews** - Rating and feedback system

### Rider Side
- **Become Rider** - Registration process for drivers
- **Rider Dashboard** - Earnings and ride management
- **Live Tracking** - Real-time location sharing
- **Earnings Analytics** - Income tracking and statistics

### Admin Panel
- **User Management** - Admin controls for user accounts
- **Rider Management** - Driver verification and management
- **Payment Management** - Transaction oversight
- **Analytics Dashboard** - Platform-wide statistics
- **Blog Management** - Content management system
- **Promotions** - Offer and discount management

## 🔐 Security Features

- **JWT Authentication** - Secure token-based authentication
- **Password Encryption** - Bcrypt hashing for secure storage
- **CORS Protection** - Controlled cross-origin requests
- **Input Validation** - Data sanitization and validation
- **Rate Limiting** - API abuse prevention
- **Environment Variables** - Secure configuration management

## 📈 Performance Optimization

- **Code Splitting** - Dynamic imports for faster loading
- **Caching Strategies** - Efficient data caching
- **Database Indexing** - Optimized MongoDB queries
- **Bundle Optimization** - Minified and compressed assets
- **Lazy Loading** - Component lazy loading for better UX

## 🤝 Contributing

We welcome contributions to the RideX platform! Here's how you can contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code follows our coding standards and includes appropriate tests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact & Support

For questions, issues, or support:
- **Email**: support@ridex.com
- **Documentation**: https://docs.ridex.com

---

<div align="center">
  <p>Built with ❤️ by the HexaDevs Team</p>
  <p>© 2025 RideX. All rights reserved.</p>
</div>