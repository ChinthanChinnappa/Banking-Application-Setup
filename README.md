# 🏦 Banking Application (Java Console System)

A **Java-based console banking system** that allows users to register customers, create bank accounts, perform transactions, and manage customer information.

This project demonstrates **Object-Oriented Programming concepts, file handling, and data structures in Java**.

---

# 🚀 Features

### 👤 Customer Management

* Register new customers
* Store customer details

  * Name
  * Gender
  * Address
  * Phone number
* Automatic customer ID generation

---

### 💳 Account Management

* Create savings accounts for customers
* List all accounts belonging to a customer

---

### 💰 Banking Transactions

* Deposit money
* Withdraw money
* Perform account-based transactions

---

### 📋 Customer Information

* Display complete customer details
* View customer account information

---

### 💾 File Storage

Customer data can be exported to a file:

```
D://customers.txt
```

This demonstrates **Java file handling using BufferedWriter and FileWriter**.

---

# 🛠️ Tech Stack

Language:

* Java

Concepts Used:

* Object-Oriented Programming (OOP)
* LinkedList
* ArrayList
* File Handling
* Input Validation
* Exception Handling

Tools:

* IntelliJ IDEA

---

# 🏗️ System Architecture

```
User (Console Input)
        │
        ▼
Main.java (Banking Menu)
        │
        ▼
Customer Class
        │
        ▼
SavingsAccount Class
        │
        ▼
Data Storage (LinkedList)
```

---

# 📂 Project Structure

```
Banking-Application-Setup
│
├── src
│   └── com/mite/app
│       ├── Customer.java
│       ├── SavingsAccount.java
│
├── Main.java
├── Cds.java
└── README.md
```

---

# ⚙️ How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/ChinthanChinnappa/Banking-Application-Setup.git
```

---

### 2️⃣ Open in IntelliJ IDEA

Import the project and ensure the **Java SDK is configured**.

---

### 3️⃣ Run the Main Class

Run:

```
Main.java
```

---

# 📋 Banking Menu

When the program runs, the user will see the following options:

```
Banking Menu

1. Register Customer
2. Create Account
3. List Customer Accounts
4. Transactions
5. Display Customer Details
6. Exit
```

Users interact with the system through the console.

---

# 📊 Example Workflow

Example:

1️⃣ Register a new customer

```
Enter name: John
Enter gender: Male
Enter address: Bangalore
Enter phone number: 9876543210
```

2️⃣ Create an account

```
Enter customer ID: 1
```

3️⃣ Perform transactions

```
Deposit / Withdraw funds
```

---

# 📈 Future Improvements

Possible enhancements:

* Add database support (MySQL / PostgreSQL)
* Add login authentication
* Implement GUI using JavaFX
* Add transaction history
* Improve error handling
* Implement persistent storage

---

# 👨‍💻 Author

**Chinthan Chinnappa Pattada**

Computer Science Engineering Student
Interested in:

* Backend Systems
* Data Engineering
* Software Development

---

If you want, I can also show you **how to turn this banking project into a MUCH stronger project** (with database, REST API, and Spring Boot) so it actually helps you get placements.
