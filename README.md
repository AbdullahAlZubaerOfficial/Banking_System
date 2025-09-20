🏦 Banking System with Transaction History
Project Overview

This Banking System is a C++ OOP based project that I developed during my CSE lab course.
The main goal of this project was to implement all the major Object-Oriented Programming (OOP) concepts in a real-life example like Banking System.

The system allows:

Creating and managing bank accounts

Depositing and withdrawing money

Checking balance

Viewing transaction history

Saving data using file handling


OOP Features Covered:

This project is a complete demonstration of core OOP concepts:

Encapsulation – Bank data (account number, balance, etc.) is kept private and accessed only through public methods. 

Inheritance – Different account types (e.g., SavingsAccount, CurrentAccount) are inherited from a base BankAccount class. 🏦

Polymorphism – Virtual functions allow function overriding for account-specific behaviors. 

Function Overriding – Child classes redefine parent functions.

Constructor Overloading – Multiple constructors are implemented for flexible object creation. 

Friend Function – Used to access private data when needed. 

Inline Functions – Small functions like showing account details are declared inline for efficiency. 

Default Arguments – Some functions use default values for parameters.

File Handling – All account and transaction data is stored/retrieved from files. 

Transaction History – Every deposit/withdrawal is stored in transaction records. 

Operator Overloading (Extra Feature) – Overloaded operators for comparing balances between accounts. 

Abstraction – Hiding implementation details and exposing only necessary functions.

📂 File Structure
📁 Banking-System
 ┣ 📜 main.cpp
 ┣ 📜 BankAccount.h
 ┣ 📜 Transaction.h
 ┣ 📜 README.md
 ┣ 📜 data.txt              # stores account information
 ┣ 📜 transaction_log.txt   # stores transaction history

🛠️ Technologies Used

Language: C++

Concepts: OOP (Encapsulation, Inheritance, Polymorphism, etc.)

Storage: File Handling (text files)

Features Implemented

✔ Create new account (savings/current)
✔ Deposit and withdraw money
✔ Display account details (secured by encapsulation)
✔ Show full transaction history
✔ Store and retrieve account info from file
✔ Polymorphic behavior for different account types
✔ Operator overloading to compare account balances

📖 Example Flow

User creates a new account

User deposits/withdraws money

Every action is saved in transaction_log.txt

User can check balance and see history anytime

🏁 Conclusion

This project helped me practically apply all major OOP concepts in C++.
It was one of my favorite lab projects during my CSE studies because it not only covered theory but also showed how OOP can be applied in real-world systems like banking.
