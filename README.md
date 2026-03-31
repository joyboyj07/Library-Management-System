### 📌 Overview

The Library Management System (LMS) is a Python-based application developed using a Client-Server architecture with a graphical user interface.

The system is designed to efficiently manage library operations such as book records, issuing, returning, and tracking user activities. It integrates with a MySQL database to ensure reliable data storage and retrieval.

An optional notification system can be configured for real-time updates using external messaging services.

### ✨ Features
🔐 User Authentication System
📚 Add and Manage Books
🔄 Issue and Return Books
📋 Track Book Availability
🖥️ User-Friendly GUI Interface
🗄️ MySQL Database Integration
🔔 Optional Notification System Support
🛠️ Tech Stack

### Programming Language: 
Python
### GUI Framework: 
Tkinter / Custom GUI Components
### Database: 
MySQL
### Architecture: 
Client-Server Model

### 📁 Project Structure
```
Library-Management-System/
│
├── main.py              # Main application entry point
├── tele_server.py       # Notification server module
├── tele_creds.txt       # Credentials configuration file
├── config.sql           # Database setup script
├── requirements.txt     # Dependencies
│
├── images/              # GUI screenshots/assets
└── modules/             # Functional modules (if applicable)
```
### ⚙️ Installation & Setup
### 1️⃣ Clone the Repository
git clone https://github.com/your-username/library-management-system.git
cd library-management-system

### 2️⃣ Install Dependencies
pip install -r requirements.txt

### 3️⃣ Configure Database
Ensure MySQL server is running
Execute the SQL script:
source config.sql

This will automatically create required tables and structure.

### 4️⃣ Configure Credentials

### Edit the file:

tele_creds.txt

### Add:

MySQL username and password
Notification API token (if using messaging integration)

### 5️⃣ Start Notification Server (Optional)
python tele_server.py

(Can be deployed on a background system or startup service)

### 6️⃣ Run the Application
python main.py

### 🔑 Default Login Credentials
Username: root
Password: toor

(Can be changed in the database or configuration files)

### 🖼️ Screenshots
🏠 Home Screen
<img src="images/home_screen.png" width="450"/>
➕ Add Books
<img src="images/add_books.png" width="450"/>
🔄 Return Books
<img src="images/return_books.png" width="450"/>

### 🧠 Core Concepts Used
Client-Server Architecture
Object-Oriented Programming (OOP)
Database Management with MySQL
GUI Development in Python
Modular Code Design

### 📊 Functional Modules
Book Management
Add, update, and remove books
Issue System
Issue books to users
Return System
Manage returned books
User Authentication
Secure login system
Notification System (Optional)
Sends updates via external messaging services
🚀 Future Enhancements
🌐 Web-based version using Flask/Django
📱 Mobile application support
📊 Analytics dashboard for library usage
🔒 Advanced authentication system
☁️ Cloud deployment support
