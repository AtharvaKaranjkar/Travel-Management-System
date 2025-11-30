Travel Management System

A Java-based Travel Management desktop application built using Swing, JDBC, and MySQL.
This project allows users to book destinations, view packages, make payments, and manage travel information through an interactive graphical interface.

🚀 Features
✓ User Authentication

Login & signup system

User-specific dashboard

✓ Destinations & Packages

View destination images

Browse travel packages

Auto-slideshow feature

Manual navigation

✓ Booking System

Select package

Confirm booking

Store booking data in database

✓ Payment Integration

Displays QR code for payment

Payment confirmation window

✓ Profile & Management

View account details

Edit profile

Delete account

✓ Admin (Optional)

View all users

View all bookings

🛠️ Tech Stack
Frontend

Java Swing

AWT

Images / Icons for UI

Backend

Java

JDBC (MySQL Connector JAR)

Database

MySQL

Tables such as:

account

customer

bookpackage

bookhotel (optional)

📁 Project Structure
Travel-Management-System/
│
├── src/                 # All .java source code
├── lib/                 # JDBC JARs (MySQL Connector)
├── icons/               # All icons, images, backgrounds
├── .vscode/             # VS Code config
├── .gitignore           # Ignore class files + build folders
└── README.md            # This file

⚙️ How to Run
1. Install Requirements

Java JDK 8+

MySQL Server

VS Code or IntelliJ

2. Add Database

Create a database:

CREATE DATABASE travelmanagement;


Import tables manually or create them using SQL files (if included).

3. Add JDBC Connector

Place the MySQL Connector JAR in the lib/ folder.

4. Compile and Run

If using VS Code:

Open project

Make sure .vscode/settings.json includes JAR in classpath

Run the main class (usually Main.java or Splash.java)

✨ Screenshots (Optional)

You can add screenshots later:

![Login](icons/login.png)
![Dashboard](icons/dashboard.png)

📌 Future Enhancements

Add PDF invoice generation

Add hotel booking module

Add user analytics

Add email notification system

🧑‍💻 Author

Atharva Karanjkar
Travel Management System – Java Project

📜 License

This project is for educational purposes.
You may modify or expand it as needed.
