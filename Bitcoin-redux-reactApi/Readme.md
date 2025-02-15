# 🚀 Bitcoin Market Tracker

A modern **Bitcoin Market Tracker** built with **React, Redux, Redux Toolkit, and CoinGecko API**, providing real-time cryptocurrency data.

## 🛠️ Tech Stack
- **React** - Component-based UI
- **Redux Toolkit** - State management
- **Redux Thunk** - Async API calls
- **CoinGecko API** - Fetching live market data
- **Parcel** - Bundling
- **CSS (Modern UI)** - Styled with glassmorphism

## 📌 Features
✅ Fetches live Bitcoin & crypto prices from **CoinGecko API**  
✅ Uses **Redux Toolkit & Async Thunks** for state management  
✅ Displays **loading and error states** elegantly  
✅ Beautiful **glassmorphic UI with hover effects**  
✅ **Responsive design** for all screen sizes

## ⚙️ Setup & Installation
1️⃣ Clone the repository:
```sh
  git clone https://github.com/yourusername/bitcoin-redux-dashboard.git
  cd bitcoin-redux-dashboard
```
2️⃣ Install dependencies:
```sh
  npm install
```
3️⃣ Start development server:
```sh
  npm start
```

## 📦 Production Build
To build for production:
```sh
  npm run build
```

## 📂 Folder Structure
```
📦 bitcoin-redux-dashboard
 ┣ 📂 src
 ┃ ┣ 📜 App.js
 ┃ ┣ 📜 BitcoinCard.js
 ┃ ┣ 📜 Bitcoincreate.js
 ┃ ┣ 📜 slicer1.js (Redux slice for API calls)
 ┃ ┣ 📜 stores.js (Redux store setup)
 ┃ ┣ 📜 styles.css (Modern UI styles)
 ┗ 📜 index.js (Main entry point)
```

## 🎯 API Reference
- **Endpoint:** `https://api.coingecko.com/api/v3/coins/markets`
- **Query Params:**
  - `vs_currency=usd`
  - `order=market_cap_desc`
  - `per_page=20`

## 🌟 Contributions
Feel free to **fork & contribute** to improve the project!

## 📜 License
This project is licensed under the **MIT License**.

🚀 Happy Coding! 🎉

