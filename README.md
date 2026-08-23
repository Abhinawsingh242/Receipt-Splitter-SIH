# 🧾 Receipt Splitter

A web application that makes it easy to split receipts and shared expenses among multiple people — no more manual calculations or awkward "who owes what" conversations.

## 📌 Overview

Receipt Splitter helps groups of friends, roommates, or colleagues quickly divide the cost of a shared bill. Upload or enter a receipt, assign items to people, and instantly see who owes what.

## ✨ Features

- 📤 Upload or manually enter receipt details
- 👥 Split costs equally or by specific items among multiple people
- 💰 Automatic calculation of individual shares
- 📊 Clear summary of who owes what to whom
- 🔒 Secure environment variable handling for sensitive data

## 🗂️ Project Structure
Receipt-Splitter/

├── backend/ # Server-side code (API, business logic, database)

├── frontend/ # Client-side code (UI, components, pages)

├── .env # Environment variables (not tracked in git)

├── .gitignore # Files/folders excluded from git

└── README.md # Project documentation


## 🛠️ Tech Stack

| Layer      | Technology            |
|------------|------------------------|
| Frontend   | *(e.g. React, HTML/CSS/JS)* |
| Backend    | *(e.g. Node.js/Express, Python/Django/Flask)* |
| Database   | *(e.g. MongoDB, PostgreSQL)* |
| Other      | *(e.g. OCR API for receipt scanning)* |

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- Node.js (v16 or higher) / Python (v3.9 or higher)
- npm or pip
- Git

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

   Create a `.env` file in the `backend` folder and add:

   
### Running the App

**Start the backend server:**
```bash
cd backend
npm start
```

**Start the frontend (in a separate terminal):**
```bash
cd frontend
npm start
```

The app should now be running at `http://localhost:3000` (frontend) and `http://localhost:5000` (backend).

## 📖 Usage

1. Open the app in your browser
2. Enter or upload your receipt
3. Add the names of people splitting the bill
4. Assign items or split equally
5. View the final breakdown of who owes what

## 🧪 Running Tests

```bash
npm test
```

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m "Add some feature"`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 📧 Contact

Created by [Your Name] — feel free to reach out with questions or suggestions.
