📘 ApnaBank - .NET Banking Application
🏦 Overview

ApnaBank is a desktop-based banking application developed using .NET (C# Windows Forms).
It simulates core banking operations like account management, transactions, bill payments, and user authentication.

This project demonstrates concepts of:

Object-Oriented Programming (OOP)
Database handling
GUI-based application development
Layered architecture (UI + Business Logic + Data Access)
🚀 Features
🔐 Authentication
User Sign Up
Login system
Session management
👤 Account Management
View account details
Update user information
Change password
💰 Transactions
Deposit money
Withdraw money
Transfer funds
Transaction history (Statement)
💡 Utilities
Mobile/DTH Recharges
Gas bill payment
Bill payment system
🧱 Project Structure
ApnaBank/
│
├── 📁 AppData/                # Application data storage
├── 📁 bin/                    # Compiled binaries
├── 📁 obj/                    # Build files
├── 📁 Properties/             # Project settings
├── 📁 Resources/              # UI resources
│
├── 📄 Program.cs              # Entry point
├── 📄 App.config              # Configuration file
│
├── 📄 LoginForm.cs            # User login
├── 📄 SignUp.cs               # New user registration
├── 📄 Home.cs                 # Dashboard
│
├── 📄 AccountDetails.cs       # Account information
├── 📄 ChangePassword.cs       # Password update
│
├── 📄 AddMoney.cs             # Deposit functionality
├── 📄 Withdraw.cs             # Withdraw functionality
├── 📄 Transfer.cs             # Fund transfer
├── 📄 Statement.cs            # Transaction history
│
├── 📄 PayBill.cs              # Bill payments
├── 📄 PayGas.cs               # Gas payments
├── 📄 Recharges.cs            # Recharge system
│
├── 📄 Users_DB.cs             # User database operations
├── 📄 Account_DB.cs           # Account database handling
├── 📄 Transaction_DB.cs       # Transaction handling
│
├── 📄 BusinessLogic.cs        # Core business logic layer
│
├── 📄 ApnaBankDataSet.xsd     # Dataset schema
├── 📄 ApnaBank.accdb         # MS Access Database
🛠️ Technologies Used
Language: C#
Framework: .NET (Windows Forms)
Database: Microsoft Access (.accdb)
IDE: Visual Studio
⚙️ How to Run the Project
Open Visual Studio
Click on Open Project

Select:

ApnaBank.csproj

Build the solution:

Ctrl + Shift + B

Run the application:

F5
🗄️ Database Details
Database file: ApnaBank.accdb
Used for:
User records
Account details
Transactions

Make sure:

The database path is correctly set in App.config
🧠 Architecture

The project follows a 3-layer architecture:

Presentation Layer (UI)
Forms like Login, Home, Transfer, etc.
Business Logic Layer
BusinessLogic.cs
Data Access Layer
Files like:
Users_DB.cs
Transaction_DB.cs
Account_DB.cs
📌 Key Learning Outcomes
Building real-world desktop applications
Handling database operations in C#
Implementing authentication systems
Managing transactions safely
Designing modular and maintainable code
📷 Future Improvements
Add encryption for passwords
Improve UI/UX
Migrate database to SQL Server/MySQL
Add admin panel
Add logging & error handling
👨‍💻 Author

Kartik Raj
B.Tech Computer Science
Aspiring Software Developer (Java / Quant / ML)

⭐ If you like this project

Give it a ⭐ on GitHub and feel free to contribute!
