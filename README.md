# 💸 Expense Tracker Web App

> A clean, modern, and user-friendly expense tracking application built using Flask — designed to help users manage money smarter with visual insights.

---

## 🚀 Live Demo

🌐 https://expense-tracker-redc.onrender.com

---

## ✨ Features

🔐 **Secure Authentication**

* User registration & login system
* Password hashing for security

💰 **Expense Management**

* Add, delete, and manage daily expenses
* Categorize into Food, Travel, Bills, Shopping, Entertainment

📊 **Data Visualization**

* Interactive pie chart for category-wise spending
* Clear financial insights at a glance

📈 **Dashboard Overview**

* Total expense summary
* Clean and minimal UI for better experience

👤 **User-Specific Data**

* Each user can only access their own expenses

---

## 🛠️ Tech Stack

| Layer      | Technology Used                              |
| ---------- | -------------------------------------------- |
| Backend    | Python, Flask, Flask-Login, Flask-SQLAlchemy |
| Database   | SQLite                                       |
| Frontend   | HTML, Bootstrap 5, Jinja2                    |
| Charts     | Chart.js                                     |
| Deployment | Render, Gunicorn                             |
| Versioning | Git, GitHub                                  |

---

## 📂 Project Structure

```bash
expense_tracker/
├── app.py              # Main Flask application
├── requirements.txt    # Dependencies
├── render.yaml         # Deployment config
├── templates/
│   ├── base.html
│   ├── dashboard.html
│   ├── login.html
│   └── register.html
└── instance/
    └── expenses.db
```

---

## ⚙️ How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/vanshiityagii/expense-tracker.git
cd expense-tracker
```

### 2️⃣ Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the app

```bash
python app.py
```

### 5️⃣ Open in browser

```
http://127.0.0.1:5000
```

---

## 📸 Screenshots

> Add screenshots like:

* Dashboard view <img width="1208" height="1446" alt="expense-tracker-redc onrender com_dashboard (1)" src="https://github.com/user-attachments/assets/af7d347a-decc-407e-8982-bfe16be8fd79" />

* Login/Register pages <img width="1228" height="710" alt="expense-tracker-redc onrender com_register" src="https://github.com/user-attachments/assets/5f37cae1-167b-40d0-a058-175d96c9d10b" />
<img width="1228" height="603" alt="expense-tracker-redc onrender com_login" src="https://github.com/user-attachments/assets/667c1dc8-bfa0-4ddf-8606-c87b06da42a2" />

  

---

## 🌟 Future Improvements

* Export expenses as CSV
* Monthly budget alerts
* Dark mode UI 🌙
* Mobile responsiveness improvements

---

## 🙋‍♀️ Author

**Vanshika Tyagi**

🔗 GitHub: https://github.com/vanshiityagii
🔗 LinkedIn: https://www.linkedin.com/in/vanshika-tyagi-7771b4322

---

## ⭐ Support

If you like this project:

* ⭐ Star the repo
* 🍴 Fork it
* 🧠 Contribute ideas

---

> “Track your money, control your future.” 💡
