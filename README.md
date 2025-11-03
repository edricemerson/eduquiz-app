# 🎓 EduQuiz — Fullstack Learning Game Platform

EduQuiz is a **fullstack web application** inspired by Kahoot, designed to make learning interactive and fun.  
Built using **Node.js**, **Express**, **Sequelize**, and **PostgreSQL** for the backend, and a lightweight **HTML/CSS/JavaScript** frontend.  

---

## 🧠 Overview

EduQuiz lets users:
- Register and log in securely
- Create or join quizzes in real time
- Answer multiple-choice questions in a fun, interactive interface
- Store results and progress in a PostgreSQL database

---

## ⚙️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML, CSS, JavaScript, Live Server |
| **Backend** | Node.js, Express.js |
| **Database** | PostgreSQL |
| **ORM** | Sequelize |
| **Tools** | Nodemon, Sequelize CLI, pgAdmin |

---

## 🛠️ Setup & Installation

### 1️⃣ Prerequisites
Make sure you have:
- [Node.js](https://nodejs.org/en/download/)
- [PostgreSQL](https://www.postgresql.org/download/)
- [npm](https://www.npmjs.com/)
- [Sequelize CLI](https://sequelize.org/)
- [VS Code Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

---

### 2️⃣ Database Setup

1. Start PostgreSQL  
2. Create a database (EduQuiz)  
3. Update your config file in Application/Project_Kahoot_Clone/config/config.json:
   
```bash
{
"development": {
 "username": "postgres",
 "password": "your_password", (Your password when you first download postgres)
 "database": "EduQuiz",
 "host": "127.0.0.1",
 "dialect": "postgres"
}
}
```

4. Open terminal in VSC and change directory to the
backend setup (cd Application/Project_Kahoot_Clone)

 ```bash
npx sequelize-cli db:create
npx sequelize-cli db:migrate
```
## & Do

 ```bash
cd Application/Project_Kahoot_Clone
npm install
npx nodemon app
```

If terminal write this then you successfully connect
your backend to the environment

```bash
[nodemon] 3.1.10
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,cjs,json
[nodemon] starting `node app.js`

Example app listening on port 3000
```

5. Go to Application/SoftengProject
Search for html file named either loginpage.html or registerpage.html and run Live Server
if you have the plugin or do

```bash
npx live-server
```

