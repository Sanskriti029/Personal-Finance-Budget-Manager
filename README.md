# 💰 Personal Finance & Budget Manager
A Java-based application to help users track expenses, income, budgets, financial insights, and monthly reports using OOP, Collections, JDBC, File I/O, Multithreading, and Exception Handling.

---

## 📌 Table of Contents
- Overview
- Features
- Technologies Used
- Project Architecture
- Installation & Setup
- Database Setup (JDBC)
- Running the Application
- Folder Structure
- Screenshots (optional)
- Future Enhancements

---

## 📖 Overview
Personal Finance & Budget Manager is a Java console application that helps users manage daily expenses, income, savings, and monthly budgets.

The system provides:
- Clean OOP design  
- Multithreading features (alerts & auto-backup)  
- Data persistence using JDBC  
- File export for monthly reports  

This project is designed according to VIT "Build Your Own Project" requirements.

---

## 🚀 Features
### ✅ Expense & Income Management
- Add / Edit / Delete transactions  
- View category-wise spending  
- Filter by date or type  

### ✅ Budget Monitoring
- Set monthly budget  
- Live remaining balance  
- Alerts when budget crosses limit (background thread)  

### ✅ Reports & Analysis
- Export monthly report (TXT/CSV)  
- Auto-backup service  
- Category-wise totals  

### ✅ Database (JDBC)
- Store & retrieve transactions  
- Update and delete entries  
- Maintain budget table  

---

## 🛠 Technologies Used
- **Java 8+**
- **OOP (Classes, Inheritance, Polymorphism)**
- **Collections (ArrayList, HashMap)**
- **Exception Handling**
- **Multithreading**
- **File I/O (BufferedWriter, Reader)**
- **MySQL with JDBC**
- **Maven (optional)**

---

## 🧩 Project Architecture
Main modules:
- `model` → User, Income, Expense  
- `manager` → BudgetManager, ReportManager  
- `threads` → BudgetAlertThread, AutoBackupThread  
- `exceptions` → Custom exceptions  
- `DatabaseManager` → MySQL operations  
- `FinanceApp` → Main entry point  

---

## ⚙️ Installation & Setup

### **1. Clone the repository**
git clone https://github.com/your-Sanskriti029/Personal-Finance-Budget-Manager.git

cd Personal-Finance-Budget-Manager

### **2. Install MySQL**
Create a database:
CREATE DATABASE finance_app;

### **3. Import tables**
Run:
database/schema.sql

### **4. Update JDBC config**
In `resources/config.properties`:
db.url=jdbc:mysql://localhost:3306/finance_app
db.username=root
db.password=yourpassword

---

## ▶️ Running the Application

### **Using Command Line**
javac -d bin src/main/java/com/financeapp/**/*.java
java -cp bin com.financeapp.FinanceApp

### **Using Maven**
mvn clean compile
mvn exec:java
---

## 📁 Folder Structure
(Short version — full version is in the main project)
src/
main/java/com/financeapp/
model/
manager/
exceptions/
threads/
FinanceApp.java
database/
docs/
README.md
statement.md

---

## 📸 Screenshots
(Add after finishing the UI or console output)

---

## 🔮 Future Enhancements
- Dynamic graphical charts  
- Android/desktop app version  
- Automatic bill recognition using OCR  
- Cloud backup  
- Multi-user login system  

---

## 📜 License
MIT License © 2025 Sanskriti Khandelwal


