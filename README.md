Got it 👍 — I’ll simplify your README so it’s **clear, professional, and to the point**, without losing important setup or usage details. Here’s the cleaned-up version:

---

# 📈 Zeroda - Demo Trading Platform

A full-stack trading platform inspired by Zerodha, built with **React.js, Node.js, Express, and MongoDB**.
This is a demo project that simulates an end-to-end trading experience.

---

## 🌟 Features

* 🔐 Login/Signup with demo authentication
* 📊 Dashboard with account balance & portfolio summary
* 🔍 Stock search with autocomplete
* 📈 Watchlist with live prices and buy/sell actions
* 💰 Order placement (market/limit)
* 🏦 Portfolio tracking with P\&L calculations
* 📱 Responsive design with professional UI
* 🔌 Backend API with MongoDB integration

---

## 🏗️ Architecture

```
zeroda/
├── frontend/     # Landing page (React) - Port 3000
├── dashboard/    # Trading dashboard (React) - Port 3001
├── backend/      # API server (Node.js/Express) - Port 3002
```

---

## 🚀 Quick Start

### Prerequisites

* Node.js (v16+)
* npm (v8+)
* MongoDB Atlas connection string

### Installation

```bash
# Clone repo
git clone https://github.com/amangupta679/Deo-trading-platform.git
cd Deo-trading-platform

# Install dependencies
cd backend && npm install
cd ../frontend && npm install
cd ../dashboard && npm install
```

### Run Services

```bash
# Backend (Port 3002)
cd backend && npm start

# Frontend (Port 3000)
cd frontend && npm start

# Dashboard (Port 3001)
cd dashboard && npm start
```

---

## 🖥️ Usage

1. Open **[http://localhost:3000](http://localhost:3000)** → Landing Page
2. Login/Signup with any email & password

   * Quick Demo: Click **“🚀 Demo Login”**
3. Start trading on the Dashboard ([http://localhost:3001](http://localhost:3001))

Demo data:

* Starting balance: ₹1,00,000
* Pre-loaded watchlist: RELIANCE, TCS, INFY, HDFCBANK, SBIN

---

## 📊 API Endpoints

| Method | Endpoint        | Description             |
| ------ | --------------- | ----------------------- |
| GET    | `/allHoldings`  | Fetch stock holdings    |
| GET    | `/allPositions` | Fetch trading positions |
| POST   | `/newOrder`     | Place a new order       |

---

## 🛠️ Tech Stack

* **Frontend**: React.js, React Router, Axios
* **Backend**: Node.js, Express, MongoDB, Mongoose
* **Database**: MongoDB Atlas
* **Tools**: Git, npm, dotenv

---

## 📝 Environment Setup

**Backend (.env)**

```env
MONGO_URL=mongodb+srv://[credentials]/zeroda
PORT=3002
```

**Frontend (.env)**

```env
PORT=3000
```

**Dashboard (.env)**

```env
PORT=3001
```

---

## 👨‍💻 Author

**Aman Gupta**

* GitHub: [@amangupta679](https://github.com/amangupta679)

---

⚠️ **Disclaimer**: This is a demo project for educational purposes only. Not for real financial transactions.

---


