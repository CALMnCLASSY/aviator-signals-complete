# Aviator Signals - Complete Project Repository

This repository contains the complete Aviator Signals project with all components and services.

## Project Structure

```
├── Avsite 3.0/           # Frontend application (React/HTML)
├── aviator-backend/       # Backend API server (Node.js/Express)
├── casino/               # Casino game implementations
├── guide/                # User guides and documentation
├── spribe/               # Spribe-specific implementations
├── SECURITY_RECOMMENDATIONS.md
├── TAWK_INTEGRATION_SUMMARY.md
└── README.md
```

## Components

### 🎯 Frontend (Avsite 3.0)
- **Repository**: [aviator-frontend](https://github.com/CALMnCLASSY/aviator-frontend.git)
- **Technology**: HTML5, CSS3, JavaScript
- **Features**: 
  - User authentication and dashboard
  - Payment integration
  - Real-time predictions display
  - WhatsApp contact popup
  - Responsive design

### 🚀 Backend (aviator-backend)
- **Repository**: [aviator-backend](https://github.com/CALMnCLASSY/aviator-backend)
- **Technology**: Node.js, Express, MongoDB
- **Features**:
  - User management and authentication
  - Payment processing (Selar, M-Pesa)
  - Telegram bot integration
  - Prediction generation
  - CORS configuration for multiple domains

### 🎰 Casino Components
- Aviator betting game clone
- Game logic and interfaces
- Integration templates

### 📚 Documentation
- Security recommendations
- Tawk.to chat integration guide
- Setup and deployment instructions

## Quick Start

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd "Avsite n"
   ```

2. **Initialize submodules** (if configured)
   ```bash
   git submodule update --init --recursive
   ```

3. **Setup Backend**
   ```bash
   cd aviator-backend
   npm install
   cp .env.example .env  # Configure your environment variables
   npm start
   ```

4. **Setup Frontend**
   ```bash
   cd "Avsite 3.0"
   # Deploy to your preferred hosting (Netlify, Vercel, etc.)
   ```

## Features

- ✅ Multi-domain support (avisignals.com, aviatorhub.xyz)
- ✅ WhatsApp integration for customer support
- ✅ Payment verification system
- ✅ Telegram notifications
- ✅ Real-time predictions
- ✅ Responsive design
- ✅ Security headers and CORS configuration

## Deployment

### Frontend
- Deployed on Netlify/Vercel
- CDN optimized for global access
- SSL/TLS encryption

### Backend
- Deployed on Render/Railway
- Environment variables configured
- Database connections secured

## Support

For support and inquiries, contact via WhatsApp: +254788020107

## License

Private project - All rights reserved
