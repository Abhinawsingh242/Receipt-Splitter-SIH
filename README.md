# 🧾 Receipt Splitter



**Split bills. Not friendships.**


A web application that makes it painless to split receipts and shared expenses among multiple people — no more manual math, no more awkward "wait, who ordered the extra fries?" conversations.

![Status](https://img.shields.io/badge/status-active-brightgreen)

---


## 📌 Overview


Splitting a group bill is simple in theory and chaotic in practice — someone forgets what they ordered, someone else did the math wrong, and tax/tip never seems to add up right. **Receipt Splitter** fixes that.

Upload or manually enter a receipt, assign items to the people who ordered them (or just split everything evenly), and get an instant, accurate breakdown of who owes what — down to the last cent of tax and tip.

Built for roommates settling monthly bills, friend groups after a dinner out, coworkers splitting a team lunch, or travelers pooling trip expenses.

---

## ✨ Features

- 📤 **Flexible input** — upload a receipt image/PDF or enter items manually
- 👥 **Multiple split modes** — split evenly across the group, or assign specific items to specific people
- 💰 **Automatic calculations** — itemized subtotals, tax, and tip are all proportionally distributed
- 📊 **Clear settlement summary** — a simple "who owes whom, and how much" breakdown, minimizing the number of transactions needed to settle up
- 🧮 **Handles shared items** — split a single item (like an appetizer) across only the people who had it
- 🔒 **Secure by design** — environment variables and sensitive config are never committed to git
- 📱 **Responsive UI** — works cleanly on desktop and mobile

### 🔜 Planned / Nice-to-have
- 🔍 OCR-based receipt scanning for automatic itemization
- 💳 Payment integration (Venmo/PayPal deep links) to settle up directly from the summary
- 🌍 Multi-currency support
- 📁 Group history — save past splits and revisit them later

---

## 🗂️ Project Structure



```
Receipt-Splitter/
├── backend/          # Server-side code (API, business logic, database)
├── frontend/         # Client-side code (UI, components, pages)
├── .env              # Environment variables (not tracked in git)
├── .gitignore        # Files/folders excluded from git
└── README.md         # Project documentation
```



---

## 🛠️ Tech Stack

| Layer      | Technology                                  |
|------------|----------------------------------------------|
| Frontend   | React / HTML, CSS, JS                        |
| Backend    | Node.js + Express / Python (Django or Flask) |
| Database   | MongoDB / PostgreSQL                         |
| Other      | OCR API for receipt scanning (planned)       |

> Replace these with your actual stack once finalized — keeping this table accurate helps contributors ramp up fast.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- **Node.js** (v16 or higher) *or* **Python** (v3.9 or higher), depending on your backend
- **npm** or **pip**
- **Git**

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Receipt-Splitter.git
   cd Receipt-Splitter
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Set up environment variables**

   Create a `.env` file inside the `backend/` folder:
   ```env
   PORT=5000
   DATABASE_URL=your_database_connection_string
   OCR_API_KEY=your_ocr_api_key_here
   ```
   > Never commit your `.env` file — it's already excluded via `.gitignore`.

### Running the App

Start the backend server:
```bash
cd backend
npm start
```

Start the frontend (in a separate terminal):
```bash
cd frontend
npm start
```

The app should now be running at:
- Frontend → `http://localhost:3000`
- Backend → `http://localhost:5000`

---

## 📖 Usage

1. Open the app in your browser
2. Enter or upload your receipt
3. Add the names of everyone splitting the bill
4. Assign items to people, or choose to split evenly
5. View the final breakdown of who owes what — settle up and move on with your life

---

## 🤝 Contributing

Contributions are welcome! If you'd like to help improve Receipt Splitter:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m "Add: your feature"`)
4. Push to your branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

Please open an issue first for major changes so we can discuss the approach.

---


## 👤 Author

**Abhinaw Singh**
GitHub: [@Abhinawsingh242](https://github.com/Abhinawsingh242)

---

⭐ If you find this project useful, consider giving it a star on GitHub — it helps others discover it too.

---


