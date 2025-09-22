# CampusCircuit Backend

This is the backend for the CampusCircuit website.  
It provides APIs for:
- **College Data** (search, view details, add/edit/remove colleges)
- **Rank Prediction** (find colleges based on rank & category)
- **User Registrations** (store counseling service sign-ups)
- **Authentication** (admin login with JWT)

---

## 📦 Tech Stack
- **Node.js + Express** — server
- **MongoDB + Mongoose** — database
- **JWT** — authentication
- **bcrypt.js** — password hashing
- **dotenv** — environment variable management

---

## 📂 Project Structure
ChatGPT said:
Got it — let’s make a proper README.md so your backend project is self-documented.
This will help you (and anyone else) remember how to install, configure, and run it.

README.md
D:\webdevelopment\campuscircuit-backend\README.md

markdown
Copy code
# CampusCircuit Backend

This is the backend for the CampusCircuit website.  
It provides APIs for:
- **College Data** (search, view details, add/edit/remove colleges)
- **Rank Prediction** (find colleges based on rank & category)
- **User Registrations** (store counseling service sign-ups)
- **Authentication** (admin login with JWT)

---

## 📦 Tech Stack
- **Node.js + Express** — server
- **MongoDB + Mongoose** — database
- **JWT** — authentication
- **bcrypt.js** — password hashing
- **dotenv** — environment variable management

---

## 📂 Project Structure
campuscircuit-backend/
├── config/ # Database config
├── controllers/ # API logic
├── middleware/ # Middleware functions (auth)
├── models/ # Mongoose schemas
├── routes/ # API routes
├── seed/ # Seed scripts for initial data
├── .env.example # Example environment config
├── .gitignore # Ignored files for Git
├── package.json # Project metadata & dependencies
├── server.js # App entry point
└── README.md # This file
