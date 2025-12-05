### 🌐🚀 Crypto Tracker — Real-Time Cryptocurrency Dashboard

A modern, responsive, beautifully animated Next.js + TypeScript + TailwindCSS Crypto Tracker powered by CoinGecko API, featuring real-time prices, search, market stats, and a full coin-details modal with 7-day price history.

## 📸 Screenshots 

<img src="https://github.com/greatasmi/crypto-nextjs16-app/blob/master/unnamed%20(2).jpg" alt="App Screenshot" />

<img src="https://github.com/greatasmi/crypto-nextjs16-app/blob/master/unnamed%20(3).jpg" alt="App Screenshot" />

<img src="https://github.com/greatasmi/crypto-nextjs16-app/blob/master/unnamed%20(4).jpg" alt="App Screenshot" />

<img src="https://github.com/greatasmi/crypto-nextjs16-app/blob/master/unnamed%20(5).jpg" alt="App Screenshot" />

<img src="https://github.com/greatasmi/crypto-nextjs16-app/blob/master/d1a1d1aa-1e8d-4c1e-b10e-c0201df585f6.png" alt="App Screenshot" />


### ✨ Features at a Glance
Feature	Description
-  🔍 Live Search	Search by coin name or symbol instantly.
-  📊 Real-Time Market Data	Fetch top cryptocurrencies with price, volume, market cap & change %.
-  📈 7-Day Price History	Displays daily closing prices using CoinGecko /market_chart.
-  🪙 Detailed Coin Stats	See rank, high/low, 24h % change, and price indicators.
-  🌙 Modern UI / UX	Gradient backgrounds, glass-blur cards, smooth transitions.
-  ⚡ Fast & Optimized	Built with useCallback, API batching, and TypeScript safety.
-  📱 Fully Responsive	Beautiful layout for mobile → desktop.
-  🛠️ Tech Stack
-  ⚛️ Next.js 16 / React 19
-  🟦 TypeScript
-  🎨 TailwindCSS
-  📡 CoinGecko Public API
-  🎯 Lucide-React Icons
-  ⚡ Hooks & Optimized Fetching
-  📦 Project Setup


## ✔️ Clone Repo
git clone https://github.com/greatasmi/crypto-tracker.git
cd crypto-tracker

## ✔️ Install Dependencies
npm install

## ✔️ Run Development Server
npm run dev

## 🔌 API Used
Endpoint	Purpose
/coins/markets	Main coin list displayed in table
/coins/{id}	Detailed coin information
/coins/{id}/market_chart	7-day historical price data

No API key required — CoinGecko is free to use 🚀

# 🖥️ UI Preview (Features)
## ▶️ Home Screen

-  🔍Search bar
-  ➡️Refresh button
-  📱List of 100 top coins
-  🪙Price, volume, 24h % change
-  🚀Rank badges

# ▶️ Coin Details Modal

-    Coin name 
-    symbol 
-    rank
-    Price (live)
-    24h high / low
-    24h percentage change
-    7-day price history
-    Scrollable history list
-    Close button
### 📁 Component Overview

Your entire project uses 1 main component:

CryptoTracker.tsx
```
│
├── Fetch top 100 coins
├── Search functionality
├── Fetch coin details
├── Fetch historical price data
├── Modal with complete stats
└── Responsive table layout
```
# 🔧 Core Functions
🔹 Fetch coins
const fetchCoins = async () => { ... }

🔹 Fetch price history
const fetchPriceHistory = async (coinId: string) => { ... }

🔹 Fetch full details
const fetchCoinDetails = async (id: string) => { ... }

## 🎨 UI Technologies Used

-  #### Tailwind gradients
-    Glassmorphism
-    Smooth transitions
-    Lucide React icons
-    Responsive grids
-    Custom scrollbars

## 🚀 Deployment

### ▲ Vercel (recommended)

### 🌐 Netlify

### 🤝 Contributing

Pull requests are welcome!

### 📜 License

# MIT License © AsmaArain

# 💛 Show Support

If this project helped you, don't forget to ⭐ star the repo!


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
