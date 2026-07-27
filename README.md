🏦 Bank Account Management System

A C++ console-based banking application developed using Object-Oriented Programming (OOP) principles. The system allows users to create and manage bank accounts, perform transactions, transfer funds, calculate interest, and maintain transaction history through a menu-driven interface.

🎯 What It Does
Account Management — Create and manage Savings and Current accounts.
Banking Operations — Deposit, withdraw, transfer funds, and check balances.
Transaction History — Track all account transactions.
Interest & Overdraft — Calculate interest for Savings accounts and provide overdraft for Current accounts.
Menu-Driven Interface — Easy-to-use console application with input validation.
🛠️ Tech Stack
Technology	Purpose
C++	Application development
OOP	Inheritance, Polymorphism, Encapsulation, Abstraction
STL	Data structures and utilities
Smart Pointers	Dynamic memory management
Visual Studio Code / CodeBlocks	Development environment
📁 Project Structure
Bank-Account-Management-System/
├── Account.h
├── Account.cpp
├── SavingsAccount.h
├── SavingsAccount.cpp
├── CurrentAccount.h
├── CurrentAccount.cpp
├── Transaction.h
├── Transaction.cpp
├── Bank.h
├── Bank.cpp
├── main.cpp
├── README.md
└── screenshots/
🚀 Getting Started
Prerequisites
C++17 compatible compiler
Visual Studio Code / CodeBlocks / g++
Installation

Clone the repository

git clone https://github.com/<your-username>/Bank-Account-Management-System.git
cd Bank-Account-Management-System

Compile the project

g++ *.cpp -o BankSystem

Run the application

./BankSystem
📊 Features
Feature	Description
Account Creation	Create Savings and Current accounts
Deposit	Add money securely
Withdrawal	Withdraw money with validation
Fund Transfer	Transfer money between accounts
Balance Inquiry	Display current account balance
Interest Calculation	Calculate Savings account interest
Overdraft	Current account overdraft facility
Transaction History	View complete transaction records
💻 OOP Concepts Used
Encapsulation
Inheritance
Polymorphism
Abstraction
Dynamic Memory Management (Smart Pointers)
