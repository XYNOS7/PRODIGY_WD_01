# 🔐 Prodigy Auth – Secure User Authentication System



> A secure, modern user authentication system built with **Flask**, featuring a clean glassmorphism UI, animated transitions, and SQLite backend. Designed for projects like login/registration systems, dashboard protection, and user role management foundations.

---

## 🚀 Features

- ✅ User Registration with Full Name, Username, Password & Confirm Password
- ✅ Secure Password Hashing using `werkzeug.security`
- ✅ Login Authentication with Session Handling
- ✅ Protected Dashboard Route with Session-based Access Control
- ✅ SQLite Database Integration
- ✅ User-friendly Error Handling
- ✅ Modern, Animated UI using Glassmorphism + Responsive Design
- ✅ View User Database via `database.html`

---

## 🖥️ Screenshots

| Login | Register | Dashboard |
|-------|----------|-----------|
| ![Login](https://i.postimg.cc/P5NdxNqR/Screenshot-2025-08-03-210351.png) | ![Register](https://i.postimg.cc/pTQH7F0p/Screenshot-2025-08-03-210417.png) | ![Dashboard](https://i.postimg.cc/J4YW9mQc/Screenshot-2025-08-03-210451.png) |

---

## ⚙️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML5, CSS3 (Glassmorphism + Animations)
- **Database**: SQLite3
- **Security**: Werkzeug password hashing
- **Session Management**: Flask sessions

---

## 📁 Project Structure

<pre>

flask-auth-app/
│
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── database.html
│
├── users.db
├── app.py
├── requirements.txt
└── README.md
</pre>


---

## ✅ Prerequisites

- Python 3.8+
- `pip` installed

---

## 🔧 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/yourusername/flask-auth-app.git
cd flask-auth-app

# Create a virtual environment (optional but recommended)
python -m venv .venv
.venv\Scripts\activate       # On Windows
# source .venv/bin/activate  # On Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

```

---

🔗 Visit: http://127.0.0.1:5000/

## 🛠️ Admin/Dev Utilities
🌐 View all users via http://127.0.0.1:5000/database

🔐 Session managed routes using @login_required decorator

## 📝 Notes
Make sure users.db is writable and in the same directory as app.py.

On deployment, replace app.secret_key with a secure random key from environment variables.

Passwords are never stored in plain text — always hashed securely.

For production, consider PostgreSQL + Flask-Login or JWT Auth.

## 🧠 Credits & Inspiration
Design inspired by Glassmorphism trends

Auth flow built on top of Flask's lightweight core

## 📄 License
This project is licensed under the MIT License.

## ⭐️ Show Your Support
If you liked this project:

Give it a ⭐️ on GitHub

Share it with your peers

Fork & build your own features!


---

## ✅ Next Steps You Can Take

- Replace screenshot links with your **own UI images** from the app (hosted on Imgur or GitHub assets).
- Add a `LICENSE` file (MIT or your choice).
- Push it to GitHub using:

```bash
git init
git add .
git commit -m "Initial commit - Prodigy Auth System"
git remote add origin https://github.com/yourusername/flask-auth-app.git
git push -u origin main
