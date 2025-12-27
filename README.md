# 🔐 Firebase Auth REST Mini App

A lightweight front-end web application that demonstrates **Firebase Authentication using the REST API**.  
This project allows users to **register, log in, log out, and fetch protected profile data** using plain JavaScript—without Firebase SDKs.

---

## ✨ Features

- ✅ User Registration (Email & Password)
- ✅ User Login & Logout
- 🔒 Protected Profile Fetch (requires authentication token)
- 🌗 Light / Dark Theme Toggle
- ⚡ Firebase Authentication via REST API
- 🧩 Modular JavaScript (ES Modules)

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6 Modules)**
- **Firebase Authentication REST API**

---

## 📂 Project Structure
├── index.html # Main UI layout
├── style.css # Application styling
├── script.js # Core application logic
├── config.js # Firebase API configuration
└── README.md # Project documentation

---

## ⚙️ Configuration

Before running the project, configure your Firebase API key.

---

### `config.js`
```js
export const FIREBASE_API_KEY = "YOUR_FIREBASE_API_KEY";

---

⚠️ Important:
Do NOT commit real API keys to public repositories.
For production, use environment variables or .gitignore.
---

🚀 Getting Started

1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repo-name.git

---

2️⃣ Open the Application

Open index.html directly in your browser:

open index.html

or right-click → Open with Browser

🧪 How the Application Works

Uses Firebase Authentication REST endpoints:

signUp

signInWithPassword

lookup

Authentication tokens (idToken) are handled client-side

Protected actions require a valid authentication token

UI updates dynamically based on authentication state

---


👥 Project Roles & Contributions

Each member contributed specific responsibilities to ensure efficient development and clear task ownership.

JS Logic & Data Processing – Honeylee Bumanglag
Handles JavaScript logic, data validation, and client-side processing.

API & Authentication Handler – Mae Ann De Guzman
Implements Firebase Authentication using REST API, including registration, login, and protected requests.

UI & CSS Designer – Natasha Balbuena
Designs the user interface, layout, styling, and light/dark theme toggle.

GitHub & Documentation Manager – Arwien Estrada
Manages the GitHub repository, project documentation, and README structure.

---

📌 Use Cases

Learning Firebase Authentication without SDKs

Practicing REST API integration

Academic or school-based projects

Front-end authentication demos

---

🧑‍💻 Maintainer

Arwien Estrada
📍 Philippines
🎓 Information Technology Student
💡 Interested in Web Systems and Software Development

---

📄 License
You are free to use, modify, and distribute this project.
