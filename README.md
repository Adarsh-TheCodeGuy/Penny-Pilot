# 💰 Penny Pilot

A modern **Expense Tracker** built with the **MERN Stack** that helps users manage their income and expenses, visualize spending patterns, and export financial data to Excel.

Designed with a clean, responsive interface and interactive charts, Penny Pilot makes personal finance tracking simple and efficient.

---

## 📸 Preview

### Dashboard

<img width="4004" height="3272" alt="dashboard" src="https://github.com/user-attachments/assets/0cd3f29e-eedf-4553-97d3-8f1d75601d72" />


### Income

<img width="4004" height="3144" alt="income" src="https://github.com/user-attachments/assets/8e9e12a7-8edb-411f-85fe-63c5515a223c" />


### Expenses

<img width="4004" height="3144" alt="expense" src="https://github.com/user-attachments/assets/ab046233-0a5f-4b0e-9d43-e87e87194951" />


---

## ✨ Features

### 🔐 Authentication

* Secure JWT Authentication
* User Registration & Login
* Protected Routes

### 💰 Income Management

* Add Income
* View Income History
* Delete Income
* Income Analytics
* Export Income to Excel

### 💸 Expense Management

* Add Expenses
* View Expense History
* Delete Expenses
* Expense Category Tracking
* Export Expenses to Excel

### 📊 Dashboard

* Total Balance
* Total Income
* Total Expenses
* Recent Transactions
* Financial Overview
* Interactive Charts

### 📈 Data Visualization

* Income Overview Chart
* Expense Category Pie Chart
* Last 30 Days Expense Chart

### 📱 User Experience

* Responsive Design
* Modern UI
* Fast Performance
* Easy Navigation

---

# 🛠 Tech Stack

## Frontend

* React
* Vite
* Tailwind CSS
* React Router
* Axios
* Recharts
* React Icons

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Multer
* XLSX

---

# 📂 Project Structure

```
Penny-Pilot/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── .env
│   ├── .gitignore
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   └── pennyPilot/
│       ├── public/
│       ├── src/
│       │   ├── assets/
│       │   ├── components/
│       │   │   ├── Cards/
│       │   │   ├── Charts/
│       │   │   ├── Dashboard/
│       │   │   ├── Expense/
│       │   │   ├── Income/
│       │   │   ├── Inputs/
│       │   │   ├── Layouts/
│       │   │   ├── DeleteAlert.jsx
│       │   │   ├── EmojiPickerPopup.jsx
│       │   │   └── Modal.jsx
│       │   ├── context/
│       │   ├── hooks/
│       │   ├── pages/
│       │   │   ├── Auth/
│       │   │   └── Dashboard/
│       │   ├── utils/
│       │   ├── App.jsx
│       │   ├── main.jsx
│       │   └── index.css
│       ├── .gitignore
│       ├── eslint.config.js
│       ├── index.html
│       ├── package.json
│       ├── package-lock.json
│       ├── README.md
│       └── vite.config.js
└── README.md
```

---

# 🚀 Installation

## 1. Clone the repository

```bash
https://github.com/Adarsh-TheCodeGuy/Penny-Pilot.git
cd penny-pilot
```

---

## 2. Install Frontend

```bash
cd frontend
cd pennyPilot
npm install
```

---

## 3. Install Backend

```bash
cd backend
npm install
```

---

## 4. Environment Variables

Create a `.env` file inside the **backend** folder.

```env
PORT=8000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

JWT_EXPIRES=7d
```

---

## 5. Run Backend

```bash
npm run dev
```

---

## 6. Run Frontend

```bash
npm run dev
```

---

# 📊 Charts Used

* Income Overview
* Expense Category Distribution
* Last 30 Days Expenses

---

# 📥 Excel Export

Users can export:

* Income Records
* Expense Records

into Excel spreadsheets with properly formatted dates.

---

# 🔒 Authentication

JWT-based authentication is used to secure protected routes.

Features include:

* User Registration
* User Login
* Token Verification
* Protected API Endpoints

---

# 📱 Responsive Design

The application is fully responsive and optimized for:

* Desktop
* Tablet
* Mobile

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push the branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Adarsh Kumar Singh**

* GitHub: https://github.com/Adarsh-TheCodeGuy

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates future improvements.
