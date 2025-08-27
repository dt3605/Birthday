# 🎂 Birthdays

This is one of the projects from the **CS50x — Introduction to Computer Science** course.  
The goal is to build a simple web application that stores and displays people's birthdays using **Flask** and **SQLite**.


## 📌 What it does
- Allows users to **add a birthday** by entering:
  - Name
  - Month
  - Day
- Displays a list of all birthdays stored in the database.
- Saves the data in a persistent **SQLite database**.


## 🛠️ Technologies
- **Python 3**
- **Flask** (web framework)
- **SQLite3** (database)
- **HTML + CSS** (frontend)


## 📂 Project structure
birthdays/
│── app.py # Main Flask application
│── birthdays.db # SQLite database
│── schema.sql # Script to create the table
│── templates/
│ └── index.html # Main page
│── static/
│ └── styles.css # Page styling


## ⚙️ How to use
1. Clone or download this repository.
2. Create the database (if it does not exist yet):
   ```bash
   sqlite3 birthdays.db < schema.sql
Run the Flask server:

flask run
Open your browser and go to:

http://127.0.0.1:5000/

🗄️ Database structure

Table used: birthdays

📖 About

This project is part of the CS50x curriculum to practice:
Building web applications with Flask
Persisting data using SQLite
Handling forms and user input in HTML

<img width="1392" height="834" alt="birthdays" src="https://github.com/user-attachments/assets/ae9f35ab-270c-418b-b0d9-4dbb4607ea40" />

👨‍💻 Project by Davi Teodoro
