🚀 How to Run This Application Using XAMPP
✅ Prerequisites
Make sure XAMPP is installed on your system.

Node.js and npm should also be installed to run frontend and backend services.

⚙️ Step-by-Step Setup
1. Start Required Services
Open XAMPP Control Panel.

Start the following services:

✅ Apache

✅ MySQL

2. Set Up the MySQL Database
Open phpMyAdmin or use MySQL CLI.

Run the following command to create the database:

sql

CREATE DATABASE tmp_db;
💡 This will be the default database used by the application. Make sure your .env file is configured accordingly.

3. Install Project Dependencies
Download both the Frontend and Backend project folders.

npm install
