# 🚗 Car Rental System (C++)

A robust **Command Line Interface (CLI)** application designed to manage vehicle rentals. Built using **C++**, this project focuses on implementing Object-Oriented Programming (OOP) concepts to handle car inventory, customer transactions, and billing logic efficiently.

## 📖 Project Overview
This system provides a streamlined text-based interface for users to rent vehicles. It categorizes cars (e.g., MPV, SUV, Sport), calculates rental fees based on duration (hourly/daily), and generates a final transaction receipt directly in the console.

**Developed by:** Group 4 (CCIT-FTUI)
* **Gafrilatif Aviandi Putra Adnanta**
* **Muhamad Farhan Budiana**
* **Muhammad Zidan Satrio**

## 🛠️ Tech Stack
* **Language:** C++ (Standard 11 or higher recommended)
* **Libraries:**
    * `<iostream>` (I/O operations)
    * `<fstream>` (File handling for reading/writing logs)
    * `<string>` (Text manipulation)
    * `<windows.h>` (Used for `Sleep()` and `system("cls")` functions)

## ✨ Key Features
* **🚙 Multiple Car Categories:** Users can choose from different vehicle classes (MPV, SUV, Sport Cars), each with different pricing rates.
* **⏱️ Automated Billing:**
    * Input: Rental Duration (in hours/days).
    * Process: `Total = (Duration / Rate_Factor) * Price`.
    * Output: Instant cost calculation displayed to the user.
* **📂 File Handling:** Reads external text files (like `endtitle.txt`) to display custom headers or footers in the console.
* **🖥️ Interactive Menu:** A clean, loop-based menu system that allows users to navigate easily between "Rent", "View Info", and "Exit" without restarting the program.

## ⚙️ How It Works
The program utilizes a main loop to keep the application running:
1.  **Menu Display:** Shows available options using `cout`.
2.  **Selection:** Reads user input via `cin` to determine the car model (e.g., `model == 2` for SUV).
3.  **Processing:**
    * Asks for the rental duration.
    * Performs the math: `total = (jam / x) * b;`.
    * Displays the receipt.
4.  **Cleanup:** Uses `system("cls")` to clear the screen for the next transaction.

## 🚀 How to Run
1.  **Prerequisites:** You need a C++ compiler (like GCC) or an IDE (Visual Studio, Dev-C++, Code::Blocks).
2.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/YourUsername/Car-Rental-System-CPP.git](https://github.com/YourUsername/Car-Rental-System-CPP.git)
    ```
3.  **Compile & Run:**
    * **Using IDE:** Open the `.cpp` file and click "Build & Run".
    * **Using Terminal:**
      ```bash
      g++ main.cpp -o car_rental
      ./car_rental
      ```

## 📄 License
This project was submitted as an **Object-Oriented Programming (OOP)** assignment for the **CCIT-FTUI** program (April 2022).
