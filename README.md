# ATM Simulation Project

## Overview
This project is an ATM (Automated Teller Machine) simulation developed using Object-Oriented Programming (OOP) principles in Java. The ATM allows users to perform basic banking operations such as checking account balance, depositing money, and withdrawing money.

## Features
- **Account Management**: Create, delete, and manage user accounts.
- **Authentication**: Secure login functionality for users using account numbers and PINs.
- **Balance Inquiry**: Check the current balance in the user's account.
- **Deposit Funds**: Add money to the user's account.
- **Withdraw Funds**: Withdraw money from the user's account with validation for available balance.

## Technologies Used
- **Java**: The core programming language used to develop the project.
- **Object-Oriented Programming**: The project is structured around key OOP concepts such as classes, objects, inheritance, polymorphism, encapsulation, and abstraction.

## OOP Concepts Implemented
- **Classes and Objects**: User, ATM, BankAccount, and Transaction classes are used to represent different entities.
- **Inheritance**: Specialized account types (e.g., SavingsAccount, CheckingAccount) may inherit from a base `BankAccount` class.
- **Polymorphism**: Different types of accounts may override methods for specific behavior.
- **Encapsulation**: Data within classes is protected and accessed through getter and setter methods.
- **Abstraction**: Complex operations are abstracted through interfaces and abstract classes.

## Project Structure
```plaintext
ATM-Simulation/
│
├── src/
│   ├── com/
│   │   ├── atm/
│   │   │   ├── ATM.java
│   │   │   ├── BankAccount.java
│   │   │   ├── CheckingAccount.java
│   │   │   ├── SavingsAccount.java
│   │   │   ├── User.java
│   │   │   └── Main.java
│   └──
├── README.md
└──
