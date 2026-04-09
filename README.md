# 🗳️ Smart Voting System (JavaFX + MySQL)

## 📌 Overview

The **Smart Voting System** is a GUI-based application built using **JavaFX** and **MySQL**. It provides a secure and user-friendly platform where students can vote and admins can manage candidates and view results.

## 🚀 Features

### 👨‍🎓 Student Panel

* Login using Student ID and password
* View candidates in a GUI table
* Cast vote (only once)

### 👨‍💼 Admin Panel

* Secure admin login
* Add new candidates
* View live voting results

## 🛠️ Technologies Used

* Java (JavaFX for GUI)
* MySQL Database
* JDBC (Database Connectivity)

## 🗄️ Database

Database name: `smartvote`

Tables:

* `students (id, password, hasVoted)`
* `candidates (id, name, votes)`
* `admin (username, password)`


## ⚙️ Setup

1. Clone the repository

```bash
git clone https://github.com/your-username/smart-voting-system.git
```

2. Create MySQL database and tables (as per above structure)

3. Update database credentials in `DBConnection.java`

4. Run the project


## ▶️ How It Works

* User selects **Student** or **Admin**
* Student can vote once
* Admin can manage candidates and see results
* All operations are handled through GUI screens


## 🔒 Security

* Uses Prepared Statements (prevents SQL Injection)
* One user = one vote system


## 📈 Future Improvements

* Password encryption
* Charts for results
* Online deployment


