# Login-Form-using-flet

# 🔐 Login Form using Flet, FastAPI & SQLite

A simple and modern authentication system built with **Flet** for the frontend, **FastAPI** for the backend API, and **SQLite** for the database.
The app includes **Login**, **Register**, and **Dashboard** screens for user authentication and navigation.

---

## 🚀 Features

* **Login Form:**
  Secure user login using FastAPI and SQLite.

* **Registration Form:**
  Allows new users to create an account with validation.

* **Dashboard Screen:**
  Displays user information after successful login.

* **Database Integration:**
  Uses SQLite for storing and retrieving user credentials.

* **API Communication:**
  FastAPI backend handles registration and authentication requests.

* **Responsive UI:**
  Built with Flet for a smooth and interactive desktop/web interface.

---

## 🛠️ Tech Stack

| Component | Technology                 |
| --------- | -------------------------- |
| Frontend  | Flet (Python UI Framework) |
| Backend   | FastAPI                    |
| Database  | SQLite                     |
| Language  | Python 3                   |

---

## 📁 Project Structure

```
login-app/
│
├── main.py               # Flet frontend (UI)
├── api/
│   ├── server.py         # FastAPI backend
│   └── database.db       # SQLite database file
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/maryam745/Login-Form-using-Flet.git
cd Login-Form-using-Flet
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate      # For Windows
source venv/bin/activate   # For macOS/Linux
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the FastAPI Server

```bash
uvicorn api.server:app --reload
```

### 5️⃣ Run the Flet App

```bash
python main.py
```

Then open the app in your browser or desktop window.

---

## 🧠 How It Works

1. The **Register Form** collects user details and sends them to the FastAPI backend to store in the SQLite database.
2. The **Login Form** verifies credentials via API calls to FastAPI.
3. Upon successful login, the user is redirected to the **Dashboard** screen.
4. FastAPI handles all authentication logic, while Flet manages the interface.

---

## ✨ Future Improvements

* Add password encryption (e.g., using bcrypt).
* Implement session management.
* Add forgot password and profile update features.

---

## 🙋‍♀️ Author

**Maryam Nazar**
Built with ❤️ using Python, Flet, and FastAPI.

