# Bank System Extension - C++

A robust, console-based banking system extension developed in C++. This project demonstrates foundational software engineering principles, clean code architecture, and efficient data handling without relying on external databases.

## 🚀 Features

- **Transactions Management:** Securely handle user deposits and withdrawals.
- **Data Persistence:** Read, write, and update client records dynamically using File I/O (`Clients.txt`).
- **Validation & Error Handling:** Strict input validation to prevent overdrafts, invalid transactions, and duplicate accounts.
- **Total Balances Calculation:** Aggregate and display overall system liquidity.
- **Clean Architecture:** Separation of concerns between the User Interface (Screens) and Business Logic (Transaction functions).

## 🧠 Technical Highlights

- Applied the **Single Responsibility Principle (SRP)** by isolating UI input/output from core logic functions.
- Ensured **Consistency** across functions (e.g., matching boolean return types for status handling).
- Used **Pass-by-Reference** to safely manipulate vectors in memory and prevent data loss.
- Avoided code duplication by utilizing modular functions and clear control flows.

## 🛠️ Technology Stack
- **Language:** C++ (Standard Library)
- **Concepts:** Structs, Vectors, Enums, File I/O, String Manipulation.

## 💡 How to Run
1. Clone this repository.
2. Compile the `Main.cpp` file using any standard C++ compiler (e.g., GCC, MSVC).
3. Run the executable. Ensure `Clients.txt` is in the same directory for data persistence.

---
*Developed as part of an advanced C++ problem-solving and algorithms track, focusing on writing clean, scalable, and memory-safe code.*
