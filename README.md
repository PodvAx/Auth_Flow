# 🔐 AuthFlow – Authentication & Authorization Server

A secure authentication and authorization server built with Node.js and Express. Supports both classic JWT-based authentication and social login via OAuth (Google, Facebook, GitHub). The project is designed to provide scalable and maintainable auth logic for web applications.

---

## 🛠 Technologies Used

- Node.js
- Express.js
- PostgreSQL
- Sequelize ORM
- JSON Web Token (JWT)
- bcrypt
- OAuth 2.0 (Google, Facebook, GitHub)
- dotenv
- CORS

---

## ⚙️ Getting Started

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/authflow.git
cd authflow
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Create a .env file in the root directory and add the following:
```env
PORT = 3000
CLIENT_URL=your_client_url
DB_PORT = your_db_port
DB_USER = your_db_user
DB_PASSWORD = your_db_password
DB_NAME = your_db_name
DB_HOST = your_db_host
GMAIL_APP_PASSWORD=your_gmail_app_password
GMAIL_EMAIL=your_gmail
JWT_ACCESS_KEY=your_jwt_access_key
JWT_REFRESH_KEY=your_jwt_refresh_key
JWT_RESET_KEY=your_jwt_reset_key
```
| ⚠️ Make sure you have your OAuth credentials set up in the respective platforms.

### 4. Run the Server
```bash
npm start
```
| The server will run on http://localhost:5000/ by default.

## ✨ Features
- 🔐 User registration and login using JWT
- 🔒 Secure password hashing with bcrypt
- 🔁 Token-based session management
- 📦 Clean, modular architecture for controllers and services
- 🌍 CORS configured for cross-origin requests
