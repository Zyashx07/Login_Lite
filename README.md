# 🔑 Login-Lite : Basic Flask Authentication  

[![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)](https://www.python.org/)   [![Flask](https://img.shields.io/badge/Flask-2.x-red.svg)](https://flask.palletsprojects.com/)   [![SQLite](https://img.shields.io/badge/SQLite-Database-blue.svg)](https://www.sqlite.org/)   [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

---

## 📌 Overview  
**Login_Lite** is a **lightweight authentication system** built with **Flask and SQLite**.  
It’s designed as a **beginner-friendly project** to understand secure login, registration, and session handling.  

This project is perfect for:  
- 🎓 Students learning backend development.  
- 🧑‍💻 Developers exploring Flask authentication.  
- 🔒 Anyone who wants a simple but secure login system.  

---

## ✨ Features  
- ✅ User Registration & Login  
- ✅ Password Hashing with Werkzeug  
- ✅ SQLite Database for storing users  
- ✅ Session Management (Login/Logout)  
- ✅ Clean & Simple UI with HTML/CSS  

---

## 🛠️ Tech Stack  
- **Backend:** Python (Flask)  
- **Database:** SQLite  
- **Frontend:** HTML, CSS (Jinja2 Templates)  
- **Security:** Werkzeug password hashing  

---

## 📂 Folder Structure  

| File/Folder        | Description |
|--------------------|-------------|
| `app.py`           | Main Flask application file |
| `templates/`       | Contains HTML template files |
| ├── `base.html`    | Base template (layout for other pages) |
| ├── `login.html`   | Login page template |
| ├── `register.html`| User registration template |
| └── `dashboard.html` | User dashboard after login |
| `database.db`      | SQLite database file |
| `requirements.txt` | Python dependencies |
| `.env.example`     | Example environment variables |
| `README.md`        | Project documentation |



---

## ⚡ Installation & Setup  

### 1. Clone the Repository  
bash
 -> git clone https://github.com/YOUR_USERNAME/Login_Lite.git
cd Login_Lite



### 2. Create & Activate Virtual Environment
 -> python -m venv venv
#### Windows
 -> venv\Scripts\activate
#### Linux/Mac
 -> source venv/bin/activate



### 3. Install Dependencies
 -> pip install -r requirements.txt



### 4. Set Up Environment Variables
 -> SECRET_KEY=your_secret_key_here
 -> DATABASE_URL=sqlite:///database.db



### 5. Run the App
 -> flask run



### 6. Open in Browser
 ->  http://127.0.0.1:5000/

---

### 🔐 Security Notes

Passwords are hashed, not stored in plain text.

Flask SECRET_KEY ensures session security.

Suitable for learning & small projects (not enterprise-ready).

---


### 🚀 Future Enhancements

📧 Email Verification

🔑 Password Reset

📲 Two-Factor Authentication (2FA)

---
### 📜 License

This project is licensed under the MIT License.
