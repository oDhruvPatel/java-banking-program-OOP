# 🏦 Banking Simulation System (Java OOP Project)

## 📌 Overview
This is a console-based Banking Simulation System built in Java.  
It demonstrates core **Object-Oriented Programming (OOP) concepts** such as inheritance, polymorphism, encapsulation, and method overriding through a simple banking workflow.

Users can:
- Create a bank account (Savings or Current)
- Deposit money
- Withdraw money (with rules based on account type)
- View balance
- Open a new account
- Exit the system

---

## 🚀 Features

### 👤 Account Creation
- Choose between:
  - Savings Account
  - Current Account (with overdraft limit)

### 💰 Transactions
- Deposit money
- Withdraw money with validation rules:
  - No negative or zero transactions
  - Savings account: minimum withdrawal rule (> 100)
  - Current account: overdraft support

### 📊 Account Management
- Display balance
- Create new account dynamically during runtime

---

## 🧠 OOP Concepts Used

### 1. Encapsulation
- Data members (`ownerName`, `balance`) are protected.
- Access is controlled via methods like `deposit()`, `withdraw()`, and `showBalance()`.

### 2. Inheritance
- `savingsAccount` and `currentAccount` extend `BankAccount`.

### 3. Polymorphism (Runtime)
- Parent class reference (`BankAccount account`) holds child objects.
- Method calls are resolved at runtime.

### 4. Method Overriding
- `withdraw()` is overridden in both child classes to apply different rules.

### 5. Abstraction (Conceptual)
- User interacts with simple methods without knowing internal logic.

---

## 🏗️ Class Structure
