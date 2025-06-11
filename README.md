# ⚡ TeslaminePool

**TeslaminePool** is a simulated Coinbase-style crypto wallet built as a research tool. It features login functionality, transaction simulation, and user activity tracking — designed for educational, security testing, and awareness purposes.

---

## 🚀 Features

- 🔐 User registration and login (Flask-Login)
- 📊 Simulated crypto wallet (BTC & ETH)
- 🧾 Transaction history with fake balances
- 🧠 User activity logs (logins, transactions, etc.)
- 📈 Research-friendly architecture
- 🌐 Deployable on platforms like Render, Railway, or VPS

---

## 🧱 Project Structure

```
TeslaminePool/
├── app.py
├── requirements.txt
├── data/
│   └── schema.sql
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── activity.html
```

---

## 🛠 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/TeslaminePool.git
   cd TeslaminePool
   ```

2. **Create virtual environment & install dependencies**
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   python app.py
   ```

4. Open `http://localhost:5000` in your browser.

---

## 📡 Deployment (Render)

1. Push code to GitHub
2. Go to [https://render.com](https://render.com) → New Web Service
3. Connect your GitHub repo
4. Build Command:
   ```bash
   pip install -r requirements.txt
   ```
5. Start Command:
   ```bash
   python app.py
   ```

---

## 🧪 Research Use Only

This is a simulation. No real cryptocurrency is transferred. Use it for training, awareness, and research analysis.

---

## 📬 License

MIT License — free to use, modify, and share.