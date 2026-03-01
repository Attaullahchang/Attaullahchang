


---

## 👨‍💻 About the Developer

Attualhha  
Frontend Developer with 2 Years of Professional Experience  

I specialize in building modern, user-focused web applications using React.js and JavaScript. I focus on clean UI design, optimized performance, maintainable code structure, and seamless backend API integration.

---

## 🌐 Project Overview

MuslimLogs is a custom-built private blockchain ecosystem.

This frontend application connects directly to the Node API and provides a complete explorer and wallet interface.

Users can:

- View blockchain network status
- Browse blocks and transactions
- Check wallet balances
- Send token transfers
- Monitor chain information in real time

---

## ✨ Key Features

- 📊 Blockchain Explorer Dashboard
- 🔎 Block & Transaction Detail Pages
- 💼 Wallet Balance Checker
- 💸 Send Token Interface
- 🔄 Real-Time API Integration
- 📱 Fully Responsive Design
- ⚡ Optimized React Performance
- 🎨 Clean and Professional UI Structure

---

## 🧩 Tech Stack

- React.js
- JavaScript (ES6+)
- Axios
- CSS3 / Tailwind CSS
- REST API Integration
- Git & GitHub

---

## 📁 Project Structure

muslimlogs-frontend/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── BlockList.js
│   │   ├── TransactionList.js
│   │   ├── WalletCard.js
│   │   └── Loader.js
│   │
│   ├── pages/
│   │   ├── Explorer.js
│   │   ├── BlockDetails.js
│   │   ├── TransactionDetails.js
│   │   └── WalletPage.js
│   │
│   ├── services/
│   │   └── api.js
│   │
│   ├── App.js
│   └── index.js
│
├── .env
├── package.json
└── README.md

---

## ⚙️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/yourusername/muslimlogs-frontend.git

cd muslimlogs-frontend

2️⃣ Install Dependencies

npm install

3️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

REACT_APP_API_URL=http://your-node-ip:8002

Example:

REACT_APP_API_URL=http://159.89.xxx.xxx:8002

4️⃣ Start Development Server

npm start

Application runs on:

http://localhost:3000

---

## 📡 API Endpoints Used

- /info → Node information
- /blocks → Fetch all blocks
- /transactions → Fetch transactions
- /balance/:address → Get wallet balance
- /send → Send signed transaction

---

## 🚀 Production Build

To create a production-ready build:

npm run build

Deploy the generated `build/` folder to:

- Nginx
- Apache
- VPS
- Cloud hosting platforms

---

## 🔐 Security Considerations

- No private keys stored in frontend
- Backend handles transaction verification
- Environment variables used for API configuration
- HTTPS recommended for production
- Rate limiting should be implemented on backend

---

## 📈 Future Improvements

- WebSocket-based real-time updates
- Advanced filtering and search system
- Wallet transaction history tracking
- Smart Contract Engine UI integration
- Multi-node dashboard system

---

## 📄 License

This project is developed as part of the MuslimLogs Blockchain Ecosystem.

---

⭐ Developed by Attualhha – Frontend Developer