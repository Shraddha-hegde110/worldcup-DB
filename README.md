# World Cup Database Project

This project is part of the [freeCodeCamp](https://www.freecodecamp.org/) Relational Database certification. It uses **PostgreSQL** and **Bash scripting** to set up and query a relational database with data related to the FIFA World Cup.

## 📁 Project Structure

worldcup-DB-main/
├── insert_data.sh # Script to insert data from CSV files into the database
├── queries.sh # Bash script to execute SQL queries and display output
└── worldcup.sql # SQL schema to create the database tables


## 📝 Overview

This project sets up a PostgreSQL database with information about World Cup games and teams. After creating and populating the database, it runs a series of SQL queries to retrieve interesting statistics, such as:

- Total number of goals
- Average goals per game
- Winning teams and champions
- List of teams who played in specific rounds

## ⚙️ Technologies Used

- **PostgreSQL**
- **Bash**
- **SQL**

## 🚀 Setup Instructions

1. **Install PostgreSQL** (if not already installed):
   ```bash
   sudo apt update
   sudo apt install postgresql postgresql-contrib

2. Start the PostgreSQL service:
sudo service postgresql start

3. Create the database and tables:
psql -U postgres -f worldcup.sql

4.Insert the data:
./insert_data.sh

5. Run queries to see the results:
./queries.sh


🧠 Learning Objectives
Writing CREATE TABLE, INSERT, JOIN, GROUP BY, and SELECT queries

Using Bash to execute SQL commands

Understanding relational database concepts

📌 Author
This project was developed by A Shraddha's as part of freeCodeCamp’s Relational Database Certification.


