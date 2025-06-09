# 🌟 Aurora Voyages - Complete Travel Tourism Platform

[![Node.js](https://img.shields.io/badge/Node.js-v16+-green.svg)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-v19.1.0-blue.svg)](https://reactjs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-v8.14.0-green.svg)](https://mongodb.com/)
[![Express.js](https://img.shields.io/badge/Express.js-v5.1.0-lightgrey.svg)](https://expressjs.com/)
[![Socket.IO](https://img.shields.io/badge/Socket.IO-v4.8.1-black.svg)](https://socket.io/)
[![Stripe](https://img.shields.io/badge/Stripe-v18.1.0-purple.svg)](https://stripe.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

Aurora Voyages is a comprehensive travel companion application designed specifically for Pakistani adventurers and global travelers. This full-stack application provides an end-to-end solution for travel planning, booking, and management with advanced features including real-time weather integration, interactive maps, AR navigation, VR experiences, and social community features.

## 📋 Table of Contents

- [🌟 Features](#-features)
- [🏗️ Architecture](#️-architecture)
- [🚀 Quick Start](#-quick-start)
- [⚙️ Installation](#️-installation)
- [🔧 Configuration](#-configuration)
- [📱 Frontend](#-frontend)
- [🖥️ Backend](#️-backend)
- [🗄️ Database](#️-database)
- [🔐 Authentication](#-authentication)
- [💳 Payment Integration](#-payment-integration)
- [🌤️ Weather Integration](#️-weather-integration)
- [🗺️ Maps & Navigation](#️-maps--navigation)
- [📡 Real-time Features](#-real-time-features)
- [🎯 AR/VR Features](#-arvr-features)
- [🌍 Cultural & Travel Information](#-cultural--travel-information)
- [📊 Analytics & Reporting](#-analytics--reporting)
- [📱 Mobile Features](#-mobile-features)
- [🔒 Security Features](#-security-features)
- [🧪 Testing](#-testing)
- [🚀 Deployment](#-deployment)
- [📚 API Documentation](#-api-documentation)
- [🤝 Contributing](#-contributing)
- [🐛 Troubleshooting](#-troubleshooting)
- [📄 License](#-license)

## 🌟 Features

### Core Features
- **User Management**: Registration, authentication, profile management
- **Destination Discovery**: Browse and explore travel destinations
- **Vacation Packages**: Complete tour packages with detailed itineraries
- **Booking System**: End-to-end booking with payment processing
- **Tour Guide Platform**: Tour guide registration and package management
- **Admin Dashboard**: Comprehensive admin panel for platform management

### Advanced Features
- **Real-time Weather**: AccuWeather API integration for destination weather
- **Interactive Maps**: Google Maps integration with offline capabilities
- **AR Navigation**: Augmented reality navigation features
- **VR Experience**: Virtual reality destination previews using Cesium
- **Social Forum**: Community discussions and travel tips
- **Cultural Information**: Local customs and cultural insights
- **Travel Requirements**: Visa, permit, and documentation guidance
- **Itinerary Planner**: Custom trip planning with drag-and-drop interface
- **Transport Booking**: Integrated transportation booking
- **Notification System**: Real-time notifications via Socket.IO
- **Offline Maps**: Download maps for offline use
- **PDF Generation**: Trip itineraries and booking confirmations
- **Multi-language Support**: Multiple language options
- **QR Code Integration**: QR codes for bookings and check-ins
- **Chart Analytics**: Data visualization with Chart.js
- **File Upload System**: Cloudinary integration for image management
- **Email Services**: Multiple email providers (Gmail, SendinBlue, Ethereal)
- **Geographic Information**: Comprehensive location data
- **National Parks Guide**: Detailed park information and regulations
- **Scenic Routes**: Curated scenic driving routes
- **Safe Travel Tips**: Safety guidelines and emergency information

## 🏗️ Architecture

```
AuroraVoyages/
├── frontend/          # React.js frontend application
├── backend/           # Node.js/Express.js backend API
```

### Technology Stack

**Frontend:**
- React.js 19.1.0 with React DOM 19.1.0
- Tailwind CSS 3.4.17 for styling with plugins (@tailwindcss/forms, @tailwindcss/typography, @tailwindcss/aspect-ratio)
- React Router DOM 7.5.3 for navigation
- Axios 1.9.0 for API communication
- Socket.IO Client 4.8.1 for real-time features
- Google Maps API integration (@react-google-maps/api 2.20.6)
- Stripe 18.1.0 for payments (@stripe/react-stripe-js, @stripe/stripe-js)
- Chart.js 4.4.9 for analytics (react-chartjs-2 5.3.0)
- Cesium 1.129.0 for 3D maps (resium 1.19.0-beta.1)
- React PDF 9.2.1 for document generation
- Leaflet 1.9.4 for lightweight mapping
- MapLibre GL 3.6.2 for vector maps
- DND Kit for drag-and-drop functionality
- Headless UI 2.2.2 for accessible components
- Heroicons 2.2.0 for icons
- QR Code React 4.2.0 for QR code generation
- React Toastify 11.0.5 for notifications
- HTML2Canvas 1.4.1 for screenshot generation
- jsPDF 3.0.1 for PDF creation
- Date-fns 4.1.0 for date manipulation

**Backend:**
- Node.js with Express.js 5.1.0
- MongoDB with Mongoose ODM 8.14.0
- JWT (jsonwebtoken 9.0.2) for authentication
- Socket.IO 4.8.1 for real-time communication
- Multer 1.4.5-lts.2 for file uploads
- Cloudinary 2.6.0 for image management
- Stripe 18.1.0 for payment processing
- Nodemailer 7.0.0 for email services
- AccuWeather API for weather data
- bcryptjs 3.0.2 for password hashing
- CORS 2.8.5 for cross-origin requests
- dotenv 16.5.0 for environment variables
- Google Auth Library 9.15.1 for OAuth
- SendinBlue Client 3.3.1 for email services
- Node Fetch 3.3.2 for HTTP requests
- Nodemon 3.1.10 for development

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- npm or yarn package manager

### Clone and Install
```bash
# Clone the repository
git clone https://github.com/M-Sarim/AuroraVoyages.git
cd AuroraVoyages

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### Environment Setup
Create `.env` files in both frontend and backend directories (see Configuration section).

### Start Development Servers
```bash
# Terminal 1: Start backend server
cd backend
npm start

# Terminal 2: Start frontend server
cd frontend
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5001

## ⚙️ Installation

### Backend Installation
```bash
cd backend
npm install
```

### Frontend Installation
```bash
cd frontend
npm install
```

## 🔧 Configuration

### Backend Environment Variables (.env)
```env
# Server Configuration
PORT=5001
NODE_ENV=development

# Database
MONGODB_URI=mongodb://localhost:27017/aurora-voyages

# JWT Secret
JWT_SECRET=your-super-secret-jwt-key

# Email Configuration
EMAIL_SERVICE=gmail
EMAIL_USER=your-email@gmail.com
EMAIL_PASSWORD=your-app-password

# SendinBlue/Brevo (Optional)
USE_SENDINBLUE=false
SENDINBLUE_API_KEY=your-sendinblue-api-key
SENDINBLUE_SMTP_USER=your-smtp-user
SENDINBLUE_SMTP_PASSWORD=your-smtp-password

# Payment (Stripe)
STRIPE_SECRET_KEY=sk_test_your-stripe-secret-key
STRIPE_PUBLISHABLE_KEY=pk_test_your-stripe-publishable-key

# Weather API
ACCUWEATHER_API_KEY=your-accuweather-api-key

# Maps
GOOGLE_MAPS_API_KEY=your-google-maps-api-key
LOCATIONIQ_API_KEY=your-locationiq-api-key

# Cloudinary (Image Upload)
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret

# OAuth (Optional)
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
```

### Frontend Environment Variables (.env)
```env
# API Configuration
REACT_APP_API_URL=http://localhost:5001/api

# Maps
REACT_APP_GOOGLE_MAPS_API_KEY=your-google-maps-api-key

# Payment
REACT_APP_STRIPE_PUBLISHABLE_KEY=pk_test_your-stripe-publishable-key

# OAuth
REACT_APP_GOOGLE_CLIENT_ID=your-google-client-id
```

## 📱 Frontend

The frontend is built with React.js and provides a modern, responsive user interface.

### Key Components
- **Authentication**: Login, register, password reset
- **Dashboard**: User and admin dashboards
- **Destinations**: Browse and search destinations
- **Packages**: View and book vacation packages
- **Booking**: Complete booking flow with payment
- **Maps**: Interactive maps with navigation
- **Weather**: Real-time weather information
- **Forum**: Community discussions
- **Profile**: User profile management

### Frontend Structure
```
frontend/src/
├── components/        # Reusable UI components
│   ├── ar/           # Augmented Reality components
│   ├── auth/         # Authentication components
│   ├── charts/       # Chart and analytics components
│   ├── culture/      # Cultural information components
│   ├── destinations/ # Destination-related components
│   ├── forum/        # Forum and community components
│   ├── inspiration/  # Travel inspiration components
│   ├── itinerary/    # Itinerary planning components
│   ├── layout/       # Layout components (Navbar, Footer)
│   ├── maps/         # Map-related components
│   ├── notifications/# Notification components
│   ├── packages/     # Vacation package components
│   ├── payment/      # Payment processing components
│   ├── pdf/          # PDF generation components
│   ├── regulations/  # Travel regulations components
│   ├── routing/      # Navigation routing components
│   ├── search/       # Search functionality components
│   ├── transport/    # Transportation components
│   ├── ui/           # UI/Design system components
│   ├── uploads/      # File upload components
│   ├── utils/        # Utility components
│   ├── vr/           # Virtual Reality components
│   └── weather/      # Weather components
├── pages/            # Page components
│   ├── admin/        # Admin dashboard pages
│   ├── forum/        # Forum pages
│   ├── inspiration/  # Inspiration pages
│   ├── tourGuide/    # Tour guide pages
│   └── [50+ pages]   # Individual page components
├── context/          # React context providers
│   └── AuthContext.js # Authentication context
├── services/         # API services
│   ├── __mocks__/    # Mock services for testing
│   └── mapService.js # Map-related API calls
├── utils/            # Utility functions
│   ├── api.js        # API configuration
│   ├── commentUtils.js # Comment utilities
│   ├── imageHelper.js # Image processing utilities
│   ├── indexedDB.js  # IndexedDB utilities
│   └── mapUtils.js   # Map utilities
├── App.js            # Main application component
├── App.css           # Application styles
├── index.js          # Application entry point
└── index.css         # Global styles
```

### Available Scripts
```bash
npm start          # Start development server
npm run build      # Build for production
npm test           # Run tests
npm run eject      # Eject from Create React App
```

## 🖥️ Backend

The backend is built with Node.js and Express.js, providing a robust REST API.

### API Endpoints

#### Authentication
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/auth/google` - Google OAuth login
- `POST /api/auth/forgot-password` - Password reset request
- `POST /api/auth/reset-password` - Password reset

#### Users
- `GET /api/users/profile` - Get user profile
- `PUT /api/users/profile` - Update user profile
- `GET /api/users` - Get all users (admin)

#### Destinations
- `GET /api/destinations` - Get all destinations
- `GET /api/destinations/:id` - Get destination by ID
- `POST /api/destinations` - Create destination (admin)
- `PUT /api/destinations/:id` - Update destination (admin)
- `DELETE /api/destinations/:id` - Delete destination (admin)

#### Vacation Packages
- `GET /api/vacations` - Get all vacation packages
- `GET /api/vacations/:id` - Get package by ID
- `POST /api/vacations` - Create package (tour guide)
- `PUT /api/vacations/:id` - Update package (tour guide)
- `DELETE /api/vacations/:id` - Delete package (tour guide/admin)

#### Bookings
- `GET /api/bookings` - Get user bookings
- `GET /api/bookings/:id` - Get booking by ID
- `POST /api/bookings` - Create booking
- `PUT /api/bookings/:id` - Update booking
- `DELETE /api/bookings/:id` - Cancel booking
- `POST /api/bookings/:id/approve` - Approve booking (tour guide)
- `POST /api/bookings/:id/reject` - Reject booking (tour guide)

#### Companies
- `GET /api/companies` - Get all companies
- `GET /api/companies/:id` - Get company by ID
- `POST /api/companies` - Create company (admin)
- `PUT /api/companies/:id` - Update company
- `DELETE /api/companies/:id` - Delete company (admin)

#### Tour Guides
- `GET /api/tourGuides` - Get all tour guides
- `GET /api/tourGuides/:id` - Get tour guide by ID
- `POST /api/tourGuides` - Register as tour guide
- `PUT /api/tourGuides/:id` - Update tour guide profile
- `POST /api/tourGuides/:id/approve` - Approve tour guide (admin)
- `POST /api/tourGuides/:id/reject` - Reject tour guide (admin)

#### Cultural Information
- `GET /api/culturalInfo` - Get cultural information
- `GET /api/culturalInfo/:destinationId` - Get cultural info for destination
- `POST /api/culturalInfo` - Add cultural information (admin)
- `PUT /api/culturalInfo/:id` - Update cultural information

#### Travel Requirements
- `GET /api/travelRequirements` - Get travel requirements
- `GET /api/travelRequirements/:country` - Get requirements for country
- `POST /api/travelRequirements` - Add requirements (admin)
- `PUT /api/travelRequirements/:id` - Update requirements

#### Transport
- `GET /api/transport` - Get transport options
- `GET /api/transport/:id` - Get transport by ID
- `POST /api/transport` - Add transport option
- `PUT /api/transport/:id` - Update transport
- `DELETE /api/transport/:id` - Delete transport

#### Itineraries
- `GET /api/itineraries` - Get user itineraries
- `GET /api/itineraries/:id` - Get itinerary by ID
- `POST /api/itineraries` - Create itinerary
- `PUT /api/itineraries/:id` - Update itinerary
- `DELETE /api/itineraries/:id` - Delete itinerary

#### Forum
- `GET /api/forum/posts` - Get forum posts
- `GET /api/forum/posts/:id` - Get post by ID
- `POST /api/forum/posts` - Create forum post
- `PUT /api/forum/posts/:id` - Update post
- `DELETE /api/forum/posts/:id` - Delete post
- `POST /api/forum/posts/:id/comments` - Add comment
- `POST /api/forum/posts/:id/vote` - Vote on post

#### Notifications
- `GET /api/notifications` - Get user notifications
- `PUT /api/notifications/:id/read` - Mark notification as read
- `DELETE /api/notifications/:id` - Delete notification

#### Payments
- `POST /api/payments/create-intent` - Create payment intent
- `POST /api/payments/confirm` - Confirm payment
- `POST /api/payments/refund` - Process refund

#### File Uploads
- `POST /api/uploads/image` - Upload image
- `POST /api/uploads/document` - Upload document
- `DELETE /api/uploads/:id` - Delete uploaded file

#### Weather
- `GET /api/weather/:locationKey` - Get weather data
- `GET /api/weather/forecast/:locationKey` - Get weather forecast
- `GET /api/weather/alerts/:locationKey` - Get weather alerts

#### Maps
- `GET /api/maps/destinations` - Get map data for destinations
- `GET /api/maps/route` - Get route information
- `GET /api/maps/offline` - Download offline maps
- `POST /api/maps/save-route` - Save custom route

#### Admin
- `GET /api/admin/dashboard` - Get admin dashboard data
- `GET /api/admin/users` - Get all users
- `GET /api/admin/bookings` - Get all bookings
- `GET /api/admin/analytics` - Get platform analytics
- `PUT /api/admin/users/:id/role` - Update user role
- `DELETE /api/admin/users/:id` - Delete user

#### Health Check
- `GET /api/health` - Health check endpoint

### Backend Structure
```
backend/
├── middleware/       # Custom middleware
│   ├── auth.js       # Authentication middleware
│   └── validation.js # Validation middleware
├── models/           # MongoDB models (Mongoose schemas)
│   ├── Booking.js    # Booking model
│   ├── Company.js    # Company model
│   ├── CulturalInfo.js # Cultural information model
│   ├── Destination.js # Destination model
│   ├── ForumComment.js # Forum comment model
│   ├── ForumPost.js  # Forum post model
│   ├── ForumVote.js  # Forum vote model
│   ├── Itinerary.js  # Itinerary model
│   ├── Notification.js # Notification model
│   ├── TourGuide.js  # Tour guide model
│   ├── Transport.js  # Transport model
│   ├── TravelRequirement.js # Travel requirement model
│   ├── User.js       # User model
│   └── VacationPackage.js # Vacation package model
├── routes/           # API routes
│   ├── admin.js      # Admin routes
│   ├── auth.js       # Authentication routes
│   ├── bookings.js   # Booking routes
│   ├── companies.js  # Company routes
│   ├── culturalInfo.js # Cultural information routes
│   ├── destinations.js # Destination routes
│   ├── forum.js      # Forum routes
│   ├── health.js     # Health check routes
│   ├── itineraries.js # Itinerary routes
│   ├── maps.js       # Map routes
│   ├── notifications.js # Notification routes
│   ├── payments.js   # Payment routes
│   ├── tourGuides.js # Tour guide routes
│   ├── transport.js  # Transport routes
│   ├── travelRequirements.js # Travel requirement routes
│   ├── uploads.js    # File upload routes
│   ├── users.js      # User routes
│   ├── vacations.js  # Vacation package routes
│   └── weather.js    # Weather routes
├── utils/            # Utility functions
│   ├── emailService.js # Email service utilities
│   ├── notificationHelpers.js # Notification utilities
│   ├── weatherCache.js # Weather caching utilities
│   └── weatherService.js # Weather service utilities
├── .env              # Environment variables
├── .env.example      # Environment variables template
├── package.json      # Dependencies and scripts
├── server.js         # Main server file
└── socket.js         # Socket.IO configuration
```

## 🗄️ Database

Aurora Voyages uses MongoDB as the primary database with the following collections:

### Data Models

#### User Model
```javascript
{
  name: String,
  email: String (unique),
  password: String (hashed),
  googleId: String (optional),
  role: ["user", "admin", "tourGuide", "pendingTourGuide"],
  tourGuideProfile: ObjectId (ref: TourGuide),
  language: ["english", "spanish", "french", "german", "chinese", "japanese"],
  authProvider: ["local", "google", "facebook"],
  createdAt: Date
}
```

#### Destination Model
```javascript
{
  name: String,
  country: String,
  description: String,
  images: [String],
  attractions: [String],
  bestVisitingMonths: [String],
  culturalTips: [String],
  type: ["beach", "mountain", "city", "countryside", "historical", "adventure"],
  coordinates: { latitude: Number, longitude: Number },
  weatherLocationKey: String,
  seasonalInfo: { winter: String, spring: String, summer: String, autumn: String },
  howToGetThere: String,
  popularity: Number,
  createdAt: Date
}
```

#### Vacation Package Model
```javascript
{
  name: String,
  description: String,
  company: ObjectId (ref: Company),
  tourGuide: ObjectId (ref: TourGuide),
  destinations: [ObjectId] (ref: Destination),
  duration: Number,
  price: Number,
  activities: [String],
  includedTransport: [String],
  includedHotels: [String],
  includedMeals: [String],
  schedule: [{ day: Number, morning: String, afternoon: String, evening: String }],
  status: ["pending", "approved", "rejected"],
  createdAt: Date
}
```

#### Booking Model
```javascript
{
  user: ObjectId (ref: User),
  vacationPackage: ObjectId (ref: VacationPackage),
  destination: ObjectId (ref: Destination),
  transport: [ObjectId] (ref: Transport),
  startDate: Date,
  endDate: Date,
  totalPrice: Number,
  status: ["pending", "confirmed", "cancelled", "completed"],
  tourGuideApproval: { status: String, reason: String, date: Date },
  paymentStatus: ["pending", "paid", "refunded"],
  travelerInfo: [{ name: String, email: String, phone: String }],
  createdAt: Date
}
```

#### Tour Guide Model
```javascript
{
  name: String,
  email: String (unique),
  phone: String,
  languages: [String],
  specialties: [String],
  experience: Number,
  rating: Number (0-5),
  availability: Boolean,
  status: ["pending", "approved", "rejected"],
  rejectionReason: String,
  image: String,
  bio: String,
  company: ObjectId (ref: Company),
  vacationPackages: [ObjectId] (ref: VacationPackage),
  createdAt: Date
}
```

#### Company Model
```javascript
{
  name: String,
  email: String (unique),
  phone: String,
  address: { street: String, city: String, state: String, country: String, zipCode: String },
  website: String,
  description: String,
  logo: String,
  rating: Number (0-5),
  tourGuides: [ObjectId] (ref: TourGuide),
  vacationPackages: [ObjectId] (ref: VacationPackage),
  createdAt: Date
}
```

## 🔐 Authentication

Aurora Voyages implements a comprehensive authentication system with multiple options:

### Authentication Methods
1. **Local Authentication**: Email/password with JWT tokens
2. **Google OAuth**: Google Sign-In integration
3. **Facebook OAuth**: Facebook Login integration

### Security Features
- **Password Hashing**: bcryptjs for secure password storage
- **JWT Tokens**: Stateless authentication with JSON Web Tokens
- **Role-based Access Control**: User, Tour Guide, and Admin roles
- **Password Reset**: Secure password reset via email
- **Token Validation**: Middleware for protected routes

### Authentication Flow
1. User registers/logs in
2. Server validates credentials
3. JWT token generated and returned
4. Token stored in localStorage (frontend)
5. Token included in API requests via Axios interceptor
6. Server validates token on protected routes

### Middleware
- `auth`: Basic authentication middleware
- `adminAuth`: Admin-only access middleware
- `tourGuideAuth`: Tour guide access middleware
- `adminOrTourGuideAuth`: Combined access middleware

## 💳 Payment Integration

Aurora Voyages integrates with Stripe for secure payment processing.

### Payment Features
- **Secure Payments**: PCI-compliant payment processing
- **Multiple Payment Methods**: Credit cards, debit cards
- **Payment Intent**: Secure payment confirmation
- **Refund Support**: Automated refund processing
- **Payment History**: Complete transaction records

### Payment Flow
1. User selects vacation package/service
2. Booking details calculated
3. Stripe Payment Intent created
4. User enters payment information
5. Payment processed securely
6. Booking confirmed upon successful payment
7. Email confirmation sent

### Stripe Configuration
```javascript
// Frontend
import { loadStripe } from '@stripe/stripe-js';
const stripePromise = loadStripe(process.env.REACT_APP_STRIPE_PUBLISHABLE_KEY);

// Backend
import Stripe from 'stripe';
const stripe = new Stripe(process.env.STRIPE_SECRET_KEY);
```

## 🌤️ Weather Integration

Real-time weather data powered by AccuWeather API.

### Weather Features
- **Current Weather**: Real-time weather conditions
- **5-Day Forecast**: Extended weather predictions
- **Location-based**: Weather for specific destinations
- **Weather Alerts**: Severe weather notifications
- **Historical Data**: Past weather patterns

### Weather API Endpoints
- `GET /api/weather/:locationKey` - Current weather
- `GET /api/weather/forecast/:locationKey` - Weather forecast
- `GET /api/weather/alerts/:locationKey` - Weather alerts

### Integration
```javascript
// Get weather data
const weatherData = await axios.get(`/api/weather/${locationKey}`);

// Weather component usage
<WeatherWidget locationKey={destination.weatherLocationKey} />
```

## 🗺️ Maps & Navigation

Comprehensive mapping solution with multiple providers and advanced features.

### Map Features
- **Interactive Maps**: Google Maps integration
- **Offline Maps**: Download maps for offline use
- **AR Navigation**: Augmented reality navigation
- **Turn-by-turn Directions**: GPS navigation
- **Points of Interest**: Attraction markers
- **Route Planning**: Custom route creation
- **3D Maps**: Cesium integration for 3D visualization

### Map Providers
- **Google Maps**: Primary mapping service
- **LocationIQ**: Alternative mapping provider
- **Cesium**: 3D globe and terrain visualization
- **Leaflet**: Lightweight mapping library

### Navigation Features
- **Real-time GPS**: Live location tracking
- **Offline Navigation**: Works without internet
- **Voice Guidance**: Audio navigation instructions
- **Route Optimization**: Best route calculation
- **Traffic Information**: Real-time traffic data

### Map API Endpoints
- `GET /api/maps/destinations` - Get map data for destinations
- `GET /api/maps/route` - Calculate routes
- `GET /api/maps/offline` - Download offline maps

## 📡 Real-time Features

Socket.IO powers real-time communication throughout the application.

### Real-time Capabilities
- **Live Notifications**: Instant notifications
- **Booking Updates**: Real-time booking status
- **Chat System**: Live messaging
- **Tour Guide Updates**: Status notifications
- **Admin Notifications**: System alerts
- **Forum Updates**: Real-time forum activity
- **Weather Alerts**: Live weather notifications
- **Payment Status**: Real-time payment updates

### Socket Events
```javascript
// Client-side
socket.on('notification', (data) => {
  showNotification(data);
});

socket.on('booking_update', (booking) => {
  updateBookingStatus(booking);
});

socket.on('forum_update', (post) => {
  updateForumPost(post);
});

socket.on('weather_alert', (alert) => {
  showWeatherAlert(alert);
});

// Server-side
io.emit('notification', notificationData);
io.to(userId).emit('booking_update', bookingData);
io.to('forum').emit('forum_update', postData);
```

### Socket.IO Configuration
```javascript
// Server
const io = new Server(server, {
  cors: {
    origin: ['http://localhost:3000'],
    methods: ['GET', 'POST'],
    credentials: true
  }
});

// Client
const socket = io('http://localhost:5001', {
  query: { userId: user.id }
});
```

## 🎯 AR/VR Features

Aurora Voyages includes cutting-edge Augmented Reality and Virtual Reality features for immersive travel experiences.

### AR Navigation Features
- **Real-time AR Navigation**: Overlay navigation instructions on camera view
- **POI Recognition**: Identify points of interest through camera
- **AR Compass**: Augmented reality compass for direction finding
- **Location Markers**: Virtual markers for destinations and attractions
- **AR Translation**: Real-time text translation through camera

### VR Experience Features
- **3D Destination Previews**: Virtual reality tours of destinations
- **Cesium Integration**: 3D globe visualization with terrain
- **Virtual Tours**: Immersive 360° destination experiences
- **VR Planning**: Plan trips in virtual environment
- **Interactive 3D Maps**: Navigate destinations in 3D space

### AR/VR Components
```javascript
// AR Navigation Component
import ARNavigation from './components/ar/ARNavigation';

// VR Experience Component
import VRExperience from './components/vr/VRExperience';

// Cesium 3D Globe
import { Viewer, Entity } from 'resium';
```

### AR/VR Pages
- **ARNavigation.js**: Main AR navigation interface
- **CesiumTest.js**: 3D globe testing and visualization
- **NavigationPage.js**: Navigation hub with AR/VR options
- **TurnByTurnNavigation.js**: AR-enhanced turn-by-turn directions

## 🌍 Cultural & Travel Information

Comprehensive cultural and travel information system to help travelers understand local customs and requirements.

### Cultural Information Features
- **Local Customs**: Detailed information about local traditions
- **Cultural Tips**: Practical advice for cultural interactions
- **Language Guides**: Basic phrases and communication tips
- **Etiquette Guidelines**: Social norms and behavioral expectations
- **Religious Information**: Religious sites and practices
- **Festival Calendar**: Local festivals and celebrations

### Travel Requirements
- **Visa Information**: Visa requirements by country
- **Documentation**: Required travel documents
- **Health Requirements**: Vaccination and health guidelines
- **Safety Guidelines**: Travel safety tips and warnings
- **Emergency Information**: Emergency contacts and procedures
- **Currency Information**: Local currency and exchange rates

### Geographic Information
- **National Parks**: Comprehensive national park guides
- **Scenic Routes**: Curated scenic driving routes
- **Geographic Features**: Mountains, rivers, and natural landmarks
- **Climate Information**: Regional climate patterns
- **Best Visit Times**: Optimal travel seasons

### Cultural API Endpoints
- `GET /api/culturalInfo/:destinationId` - Get cultural information
- `GET /api/travelRequirements/:country` - Get travel requirements
- `GET /api/geography/:region` - Get geographic information

## 📊 Analytics & Reporting

Advanced analytics and reporting features for users, tour guides, and administrators.

### User Analytics
- **Trip Statistics**: Personal travel statistics and history
- **Spending Analysis**: Travel expense tracking and analysis
- **Destination Preferences**: Preferred destination types and patterns
- **Booking History**: Complete booking history with insights
- **Travel Patterns**: Travel frequency and seasonal patterns

### Tour Guide Analytics
- **Performance Metrics**: Tour guide performance statistics
- **Booking Analytics**: Booking success rates and trends
- **Revenue Tracking**: Income and commission tracking
- **Customer Feedback**: Review and rating analytics
- **Package Performance**: Vacation package success metrics

### Admin Analytics
- **Platform Statistics**: Overall platform usage statistics
- **User Demographics**: User base analysis and demographics
- **Revenue Analytics**: Platform revenue and financial metrics
- **Popular Destinations**: Most popular destinations and trends
- **System Performance**: Technical performance metrics

### Chart Components
```javascript
import { Chart as ChartJS } from 'chart.js';
import { Line, Bar, Pie, Doughnut } from 'react-chartjs-2';

// Usage in components
<Line data={chartData} options={chartOptions} />
<Bar data={barData} options={barOptions} />
<Pie data={pieData} options={pieOptions} />
```

## 📱 Mobile Features

Mobile-optimized features and responsive design for seamless mobile experience.

### Mobile-Specific Features
- **Responsive Design**: Tailwind CSS responsive utilities
- **Touch Gestures**: Touch-friendly interface elements
- **Mobile Navigation**: Optimized mobile navigation patterns
- **Offline Functionality**: IndexedDB for offline data storage
- **GPS Integration**: Real-time location tracking
- **Camera Integration**: Photo capture and AR features

### Progressive Web App (PWA) Features
- **Offline Maps**: Download and use maps offline
- **Push Notifications**: Mobile push notifications
- **App-like Experience**: Native app-like interface
- **Background Sync**: Sync data when connection restored
- **Install Prompt**: Add to home screen functionality

### Mobile Optimization
- **Image Optimization**: Responsive images with fallbacks
- **Performance**: Optimized for mobile performance
- **Battery Efficiency**: Efficient resource usage
- **Data Usage**: Minimized data consumption
- **Accessibility**: Mobile accessibility features

## 🔒 Security Features

Comprehensive security measures to protect user data and ensure platform integrity.

### Authentication Security
- **Password Hashing**: bcryptjs with salt rounds
- **JWT Security**: Secure token generation and validation
- **OAuth Integration**: Secure third-party authentication
- **Session Management**: Secure session handling
- **Password Reset**: Secure password reset flow

### Data Protection
- **Input Validation**: Comprehensive input sanitization
- **SQL Injection Prevention**: Mongoose ODM protection
- **XSS Protection**: Cross-site scripting prevention
- **CSRF Protection**: Cross-site request forgery protection
- **Rate Limiting**: API rate limiting and throttling

### API Security
- **CORS Configuration**: Proper cross-origin resource sharing
- **HTTPS Enforcement**: SSL/TLS encryption
- **API Key Management**: Secure API key handling
- **Request Validation**: Middleware-based validation
- **Error Handling**: Secure error responses

### File Upload Security
- **File Type Validation**: Allowed file type restrictions
- **File Size Limits**: Maximum file size enforcement
- **Malware Scanning**: File security scanning
- **Secure Storage**: Cloudinary secure storage
- **Access Control**: File access permissions

## 🧪 Testing

### Frontend Testing
```bash
cd frontend
npm test                    # Run all tests
npm test -- --coverage     # Run tests with coverage
npm test -- --watchAll     # Run tests in watch mode
```

### Backend Testing
```bash
cd backend
npm test                    # Run API tests
npm run test:watch         # Run tests in watch mode
```

### Testing Stack
- **Frontend**: Jest, React Testing Library
- **Backend**: Jest, Supertest
- **E2E Testing**: Cypress (optional)

### Test Structure
```
frontend/src/tests/
├── components/           # Component tests
├── pages/               # Page tests
├── utils/               # Utility tests
└── __mocks__/           # Mock files

backend/tests/
├── routes/              # API route tests
├── models/              # Model tests
├── middleware/          # Middleware tests
└── utils/               # Utility tests
```

## 🚀 Deployment

### Production Build

#### Frontend
```bash
cd frontend
npm run build
```

#### Backend
```bash
cd backend
npm run build  # If using TypeScript
```

### Environment Setup
1. Set up production MongoDB database
2. Configure production environment variables
3. Set up SSL certificates
4. Configure reverse proxy (Nginx)

### Deployment Options

#### Option 1: Traditional Server
1. Deploy to VPS/dedicated server
2. Use PM2 for process management
3. Set up Nginx reverse proxy
4. Configure SSL with Let's Encrypt

#### Option 2: Cloud Platforms
- **Heroku**: Easy deployment with git
- **Vercel**: Frontend deployment
- **Railway**: Full-stack deployment
- **DigitalOcean App Platform**: Managed deployment

#### Option 3: Docker
```dockerfile
# Frontend Dockerfile
FROM node:16-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npm", "start"]

# Backend Dockerfile
FROM node:16-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5001
CMD ["npm", "start"]
```

### Production Environment Variables
Ensure all environment variables are properly configured for production:
- Database connection strings
- API keys for external services
- JWT secrets
- Email service credentials
- Payment gateway credentials

## 📚 API Documentation

### API Base URL
- Development: `http://localhost:5001/api`
- Production: `https://your-domain.com/api`

### Authentication
All protected endpoints require a JWT token in the Authorization header:
```
Authorization: Bearer <your-jwt-token>
```

### Response Format
All API responses follow this format:
```json
{
  "success": true,
  "data": {},
  "message": "Success message",
  "error": null
}
```

### Error Handling
Error responses include:
```json
{
  "success": false,
  "data": null,
  "message": "Error message",
  "error": {
    "code": "ERROR_CODE",
    "details": "Detailed error information"
  }
}
```

### Rate Limiting
- 100 requests per minute for authenticated users
- 20 requests per minute for unauthenticated users
- 1000 requests per hour for premium users

### API Versioning
Current API version: v1
Version header: `API-Version: v1`

## 🤝 Contributing

We welcome contributions to Aurora Voyages! Please follow these guidelines:

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Add tests for new functionality
5. Ensure all tests pass
6. Commit your changes (`git commit -m 'Add amazing feature'`)
7. Push to the branch (`git push origin feature/amazing-feature`)
8. Open a Pull Request

### Code Standards
- Follow ESLint configuration
- Use Prettier for code formatting
- Write meaningful commit messages
- Add JSDoc comments for functions
- Maintain test coverage above 80%
- Follow React best practices
- Use TypeScript for type safety (when applicable)
- Follow RESTful API conventions

### Pull Request Process
1. Update README.md with details of changes
2. Update version numbers following SemVer
3. Ensure CI/CD pipeline passes
4. Request review from maintainers
5. Address review feedback promptly
6. Ensure all tests pass before merging

### Development Setup
```bash
# Install dependencies
npm install

# Set up pre-commit hooks
npm run prepare

# Run linting
npm run lint

# Run tests
npm test

# Start development server
npm run dev
```

## 🐛 Troubleshooting

### Common Issues

#### Backend Issues

**MongoDB Connection Error**
```bash
Error: MongoNetworkError: failed to connect to server
```
Solution:
- Check MongoDB connection string in `.env`
- Ensure MongoDB service is running
- Verify network connectivity
- Check firewall settings

**JWT Token Error**
```bash
Error: JsonWebTokenError: invalid token
```
Solution:
- Check JWT_SECRET in `.env`
- Verify token format
- Check token expiration
- Clear localStorage and re-login

**Port Already in Use**
```bash
Error: listen EADDRINUSE: address already in use :::5001
```
Solution:
```bash
# Find process using port
netstat -ano | findstr :5001
# Kill process
taskkill /PID <process-id> /F
```

#### Frontend Issues

**Module Not Found Error**
```bash
Module not found: Can't resolve 'module-name'
```
Solution:
```bash
# Clear node_modules and reinstall
rm -rf node_modules package-lock.json
npm install
```

**CORS Error**
```bash
Access to fetch blocked by CORS policy
```
Solution:
- Check CORS_ORIGINS in backend `.env`
- Verify API URL in frontend `.env`
- Ensure backend is running

**Build Errors**
```bash
npm run build fails
```
Solution:
- Check for TypeScript errors
- Verify all imports are correct
- Check environment variables
- Clear build cache: `npm run build -- --reset-cache`

#### Environment Issues

**Missing Environment Variables**
```bash
Error: Required environment variable not found
```
Solution:
- Copy `.env.example` to `.env`
- Fill in all required values
- Restart the application

**API Key Issues**
```bash
Error: Invalid API key
```
Solution:
- Verify API keys in `.env`
- Check API key permissions
- Regenerate API keys if necessary
- Check API usage limits

### Performance Issues

**Slow Loading Times**
- Enable image optimization
- Implement lazy loading
- Use CDN for static assets
- Optimize bundle size

**Memory Leaks**
- Check for unclosed connections
- Implement proper cleanup in useEffect
- Monitor memory usage
- Use React DevTools Profiler

### Getting Help

1. **Check Documentation**: Review this README and inline comments
2. **Search Issues**: Look for similar issues on GitHub
3. **Create Issue**: If problem persists, create a detailed issue
4. **Contact Support**: Email auroravoyagesinfo@gmail.com
5. **Community Forum**: Join our community discussions

### Debug Mode

Enable debug mode for detailed logging:
```bash
# Backend
DEBUG_MODE=true
LOG_LEVEL=debug

# Frontend
REACT_APP_DEBUG=true
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

## 📞 Support & Community

### Getting Support
- 🐛 **Bug Reports**: [Create an issue](https://github.com/M-Sarim/AuroraVoyages/issues/new?template=bug_report.md)
- 💡 **Feature Requests**: [Request a feature](https://github.com/M-Sarim/AuroraVoyages/issues/new?template=feature_request.md)
- 📧 **Email Support**: auroravoyagesinfo@gmail.com
- 📚 **Documentation**: [Wiki](https://github.com/M-Sarim/AuroraVoyages/wiki)

### Response Times
- 🔴 **Critical Issues**: Within 24 hours
- 🟡 **Bug Reports**: Within 48 hours
- 🟢 **Feature Requests**: Within 1 week
- 🔵 **General Questions**: Within 72 hours

### Community Guidelines
- Be respectful and inclusive
- Provide detailed information when reporting issues
- Search existing issues before creating new ones
- Follow the code of conduct
- Help others when possible

## 🙏 Acknowledgments

### Third-Party Services
- **AccuWeather** - Weather data and forecasting
- **Google Maps** - Mapping and navigation services
- **Stripe** - Payment processing and financial services
- **MongoDB Atlas** - Cloud database services
- **Cloudinary** - Image and video management
- **SendinBlue/Brevo** - Email marketing services
- **LocationIQ** - Geocoding and mapping services

### Open Source Libraries
- **React.js** - Frontend framework
- **Express.js** - Backend framework
- **Mongoose** - MongoDB object modeling
- **Socket.IO** - Real-time communication
- **Tailwind CSS** - Utility-first CSS framework
- **Chart.js** - Data visualization
- **Cesium** - 3D globe and maps
- **Leaflet** - Interactive maps
- **JWT** - JSON Web Tokens

### Contributors
- 👨‍💻 **Development Team** - Core development and architecture
- 🎨 **Design Team** - UI/UX design and user experience
- 🧪 **QA Team** - Testing and quality assurance
- 📝 **Documentation Team** - Documentation and guides
- 🌍 **Community** - Feedback, testing, and contributions

### Special Thanks
- **Pakistani Travel Community** - Inspiration and feedback
- **Beta Testers** - Early testing and bug reports
- **Open Source Community** - Libraries and tools
- **Travel Industry Partners** - Domain expertise
- **Educational Institutions** - Research and development support

## 🚀 Future Roadmap

### Upcoming Features
- 🤖 **AI Travel Assistant** - Personalized travel recommendations
- 🎥 **Live Streaming** - Real-time destination streaming
- 🏪 **Marketplace** - Travel gear and souvenir marketplace
- 📱 **Mobile App** - Native iOS and Android applications
- 🌐 **Multi-language** - Support for Urdu, Arabic, and more languages
- 🎮 **Gamification** - Travel achievements and rewards system

### Technical Improvements
- ⚡ **Performance Optimization** - Faster loading and better caching
- 🔒 **Enhanced Security** - Advanced security measures
- 📊 **Advanced Analytics** - Machine learning insights
- 🌍 **Global Expansion** - Support for more countries
- 🔄 **API v2** - Enhanced API with GraphQL support
- 📱 **PWA Enhancement** - Better offline capabilities

### Version History
- **v1.0.0** - Initial release with core features
- **v1.1.0** - AR/VR features and enhanced maps
- **v1.2.0** - Forum and community features
- **v1.3.0** - Advanced analytics and reporting
- **v2.0.0** - (Planned) AI integration and mobile apps

---

<div align="center">

**Aurora Voyages** - Empowering Pakistani adventurers to explore the world! 🌍✈️

[![GitHub stars](https://img.shields.io/github/stars/M-Sarim/AuroraVoyages.svg?style=social&label=Star)](https://github.com/M-Sarim/AuroraVoyages)
[![GitHub forks](https://img.shields.io/github/forks/M-Sarim/AuroraVoyages.svg?style=social&label=Fork)](https://github.com/M-Sarim/AuroraVoyages/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/M-Sarim/AuroraVoyages.svg?style=social&label=Watch)](https://github.com/M-Sarim/AuroraVoyages)

Made with ❤️ by the [Aurora Voyages Team](https://github.com/M-Sarim)

**Team Members:**
- [M-Sarim](https://github.com/M-Sarim) - Lead Developer
- [usmanaamir01](https://github.com/usmanaamir01) - Full Stack Developer
- [boltbuttar](https://github.com/boltbuttar) - Frontend Developer

[GitHub Repository](https://github.com/M-Sarim/AuroraVoyages) • [Issues](https://github.com/M-Sarim/AuroraVoyages/issues) • [Discussions](https://github.com/M-Sarim/AuroraVoyages/discussions) • [Support](mailto:auroravoyagesinfo@gmail.com)

</div>
