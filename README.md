# 📈 Zeroda - Complete Trading Platform

A full-stack, professional trading platform inspired by Zerodha, built with React.js, Node.js, Express, and MongoDB. This is a demo trading application that provides a complete end-to-end trading experience.

![Zeroda Platform](https://img.shields.io/badge/Trading-Platform-blue) ![React](https://img.shields.io/badge/React-18.x-blue) ![Node.js](https://img.shields.io/badge/Node.js-16.x-green) ![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green)

## 🌟 Features

### ✅ **Completed Features**
- **🔐 Authentication System**: Login/Signup with demo user management
- **📊 Trading Dashboard**: Professional sidebar, account balance, portfolio summary
- **🔍 Stock Search**: Real-time search with autocomplete functionality
- **📈 Watchlist**: Live stock prices with buy/sell buttons
- **💰 Order Placement**: Advanced order modal with market/limit orders
- **🏦 Portfolio Tracking**: Real-time balance updates and P&L calculations
- **📱 Responsive Design**: Modern, professional UI inspired by leading trading apps
- **🔌 Backend Integration**: Full API integration with MongoDB

### 🚧 **In Development**
- Order Book/Basket with order status tracking
- Enhanced Portfolio page with detailed analytics
- Order History with transaction records
- Advanced Account management

## 🏗️ Architecture

```
zeroda/
├── frontend/          # Marketing website (React) - Port 3000
├── dashboard/         # Trading dashboard (React) - Port 3001
├── backend/          # API server (Node.js/Express) - Port 3002
└── README.md
```

## 🚀 Quick Start

### Prerequisites
- Node.js (v16.x or higher)
- npm (v8.x or higher)
- MongoDB Atlas account (connection string provided)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/amangupta679/Deo-trading-platform.git
   cd Deo-trading-platform
   ```

2. **Install dependencies for all modules**
   ```bash
   # Install backend dependencies
   cd backend
   npm install
   
   # Install frontend dependencies
   cd ../frontend
   npm install
   
   # Install dashboard dependencies
   cd ../dashboard
   npm install
   ```

3. **Start all services**
   
   **Terminal 1 - Backend API (Port 3002)**
   ```bash
   cd backend
   npm start
   ```
   
   **Terminal 2 - Frontend Website (Port 3000)**
   ```bash
   cd frontend
   npm start
   ```
   
   **Terminal 3 - Trading Dashboard (Port 3001)**
   ```bash
   cd dashboard
   npm start
   ```

## 🖥️ Usage

### 1. **Visit the Landing Page**
Open http://localhost:3000 in your browser to see the professional marketing website.

### 2. **Login/Signup**
- Click "Login" or "Sign Up" 
- Use **any email/password** (demo authentication)
- **Quick Demo**: Click "🚀 Demo Login (Skip Registration)" button

### 3. **Start Trading**
- **Search Stocks**: Type "RELIANCE", "TCS", "INFY" in the search bar
- **Place Orders**: Click BUY/SELL buttons, enter quantity, confirm
- **Track Portfolio**: Monitor your ₹1,00,000 demo balance and P&L

## 📱 User Journey

1. **Homepage** → Professional landing page with call-to-action
2. **Authentication** → Simple login/signup (any credentials work)
3. **Dashboard** → Trading interface with balance, watchlist, search
4. **Order Placement** → Buy/sell stocks with real-time validation
5. **Portfolio Management** → Track holdings, P&L, and account balance

## 🔧 Technical Details

### Frontend (React.js)
- **React Router** for navigation
- **Axios** for API calls
- **Modern CSS Grid/Flexbox** for responsive design
- **Professional UI components** with animations

### Dashboard (React.js)
- **Advanced trading interface** with sidebar navigation
- **Real-time stock search** with autocomplete
- **Order management system** with validation
- **Portfolio tracking** with P&L calculations

### Backend (Node.js/Express)
- **RESTful API** design
- **MongoDB integration** with Mongoose
- **CORS enabled** for cross-origin requests
- **Environment variables** for configuration

### Database (MongoDB Atlas)
- **Collections**: Holdings, Positions, Orders
- **Real-time data** synchronization
- **Cloud-hosted** MongoDB Atlas instance

## 📊 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/allHoldings` | Fetch user's stock holdings |
| GET | `/allPositions` | Fetch user's trading positions |
| POST | `/newOrder` | Place a new buy/sell order |

## 🔑 Demo Credentials

**No registration required!** Use any of these options:

### Option 1: One-Click Demo
- Visit http://localhost:3000/login
- Click "🚀 Demo Login (Skip Registration)"

### Option 2: Manual Login
- **Email**: `demo@zeroda.com` (or any email)
- **Password**: `password123` (or any password)

### Option 3: Direct Access
- Visit http://localhost:3001 directly (auto-authentication)

## 💰 Demo Data

- **Starting Balance**: ₹1,00,000
- **Pre-loaded Watchlist**: RELIANCE, TCS, INFY, HDFCBANK, SBIN
- **Real-time Price Simulation**: Live market-like data
- **Order Execution**: Instant order processing with balance updates

## 🎨 Design Philosophy

- **Professional Trading UI**: Inspired by Zerodha Kite and Groww
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Modern Color Scheme**: Blue gradients with green/red for P&L
- **Smooth Animations**: Hover effects and transitions
- **Clean Typography**: Easy-to-read fonts and spacing

## 🔒 Security Features

- **Demo Authentication**: Secure localStorage-based sessions
- **Input Validation**: Form validation and error handling
- **CORS Protection**: Proper cross-origin resource sharing
- **Environment Variables**: Sensitive data protection

## 📈 Performance

- **Fast Loading**: Optimized React components
- **Real-time Updates**: Instant balance and portfolio sync
- **Responsive UI**: Smooth interactions on all devices
- **Efficient API Calls**: Minimal network requests

## 🚧 Development Roadmap

### Phase 1 (✅ Completed)
- [x] Authentication system
- [x] Trading dashboard
- [x] Stock search and watchlist
- [x] Order placement system
- [x] Backend integration
- [x] Professional UI/UX

### Phase 2 (🚧 In Progress)
- [ ] Order Book with status tracking
- [ ] Enhanced Portfolio analytics
- [ ] Order History with filters
- [ ] Advanced Account management
- [ ] Charts and technical analysis
- [ ] Real-time market data integration

### Phase 3 (📋 Planned)
- [ ] Mobile app (React Native)
- [ ] Advanced order types (Stop-loss, etc.)
- [ ] News and research integration
- [ ] Social trading features
- [ ] Performance analytics
- [ ] Export/reporting features

## 🛠️ Tech Stack

### Frontend
- **React.js 18.x** - Modern UI library
- **React Router DOM** - Client-side routing
- **Axios** - HTTP client for API calls
- **CSS Grid/Flexbox** - Responsive layouts

### Backend
- **Node.js 16.x** - Server runtime
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variable management

### Tools & Services
- **MongoDB Atlas** - Cloud database
- **Create React App** - React application setup
- **npm** - Package management
- **Git** - Version control

## 📝 Environment Setup

### Backend Environment Variables
```env
MONGO_URL=mongodb+srv://[credentials]/zeroda?retryWrites=true&w=majority
PORT=3002
```

### Frontend Configuration
```env
PORT=3000
```

### Dashboard Configuration
```env
PORT=3001
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Aman Gupta**
- GitHub: [@amangupta679](https://github.com/amangupta679)
- Project: [Deo Trading Platform](https://github.com/amangupta679/Deo-trading-platform)

## 🙏 Acknowledgments

- **Zerodha Kite** - UI/UX inspiration
- **React Community** - Excellent documentation and resources
- **MongoDB Atlas** - Reliable cloud database service
- **Node.js Community** - Robust backend ecosystem

## 📞 Support

If you encounter any issues or have questions:

1. **Check the Issues**: Look through existing [GitHub Issues](https://github.com/amangupta679/Deo-trading-platform/issues)
2. **Create New Issue**: Submit detailed bug reports or feature requests
3. **Documentation**: Refer to this README for setup instructions

## 🎯 Demo Links

Once the application is running:

- **Landing Page**: http://localhost:3000
- **Trading Dashboard**: http://localhost:3001  
- **Backend API**: http://localhost:3002

---

**⚠️ Disclaimer**: This is a demo trading platform for educational purposes only. Not intended for real financial transactions.

**🚀 Start your trading journey today with Zeroda!**#   D e o - t r a d i n g - p l a t f o r m  
 