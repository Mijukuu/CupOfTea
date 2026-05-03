# Cup of Tea – Community Platform

Full-stack web application that connects neighbors to share resources, request help, and build local communities.

---

## 📋 Overview

Cup of Tea is a community-driven platform that allows users to:
- Offer or request help (childcare, goods, household tasks, etc.)
- Connect with local users
- Browse and filter posts by category
- Engage in a structured, role-based system (admin, moderator, user)

The project focuses on building a scalable backend, structured data models, and a user-centered interaction system.

---

## 🚀 Key Features

- User authentication and session management
- Create, browse, and filter community posts
- Category-based organization (food, goods, childcare, etc.)
- Role-based access (admin, moderator, user)
- Persistent storage using MongoDB
- Seeded test accounts for quick testing

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** Express-Session  
- **Frontend:** Handlebars  

---

## 👨‍💻 Contributions

This project was developed as part of a team collaboration.

My primary contributions included:
- Designing and implementing backend APIs using Express.js
- Structuring MongoDB schemas for users, posts, and interactions
- Building core application logic for post creation, filtering, and routing
- Implementing authentication and session handling
- Integrating major application components into a cohesive system

---

## ⚙️ Running the Application

### 1. Clone the Repository

```bash
git clone https://github.com/Mijukuu/CupOfTea.git
cd CupOfTea
```

---

### 2. Install Dependencies

```bash
npm install
```

---

### 3. Environment Setup

Create a `.env` file in the root directory:

```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/
MONGODB_DATABASE=group_3_cs546
NODE_ENV=development
```

---

### 4. Run the Application

```bash
npm run dev
```

The app will run at:

```
http://localhost:3000
```

---

### 5. Seed the Database (Optional)

```bash
npm run seed
```

---

## 👤 Test Accounts

All accounts use the same password:

```
Password123!
```

### Admin
- nick.fury@shield.gov

### Moderator
- maria.hill@shield.gov

### Users
- steve.rogers@avengers.com
- kamala.khan@gmail.com
- carol.danvers@usaf.mil
- jennifer.walters@law.com
- matt.murdock@nelsonmurdock.com
- peter.parker@empire.edu

---

## 📌 Notes

- This repository represents my primary working version of the project
- Development was completed collaboratively, with shared contributions across the team
