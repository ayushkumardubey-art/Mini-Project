# 🧮 Menu-Driven Scientific Calculator (Mini-Project)

![Language](https://img.shields.io/badge/Language-C-blue?style=for-the-badge&logo=c)
![IDE](https://img.shields.io/badge/IDE-VS_Code-blueviolet?style=for-the-badge&logo=visual-studio-code)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 👤 Student Details
* **Name:** Ayush Kumar Dubey
* **ERP Number:** RU-25-11741
* **Course:** BCA
* **Subject:** C Programming Mini-Project

---

## 🚀 Project Overview
This project is a **Menu-Driven Scientific Calculator** developed in C language. It is designed to perform arithmetic and scientific operations based on user input. The program uses a modular approach with separate functions for UI display and calculation logic to ensure clean code structure.

### Key Features:
* **✅ Modular Design:** Uses `void showMenu()` to separate the interface from logic.
* **✅ Custom Algorithms:** Implements a custom `powerCalc` function using loops instead of relying solely on libraries.
* **✅ Continuous Execution:** Wrapped in a `while` loop so users can perform multiple calculations without restarting.
* **✅ Error Handling:** Includes checks to prevent "Division by Zero" crashes.
* **✅ Floating Point Precision:** Uses `float` data types to handle decimal values accurately.

---

## 🛠️ Technical Implementation

### Logic Used:
1.  **Control Flow:** Utilized an `if-else if` ladder to map user menu choices (1-8) to specific operations.
2.  **Iterative Logic:** Used a `for` loop inside the `powerCalc` function to mathematically calculate exponents ($x^y$).
3.  **Input Validation:** Implemented a buffer clear method `scanf(" %c", ...)` to fix common input skipping issues in C.

### Code Structure:
| Function | Purpose |
| :--- | :--- |
| `main()` | Handles the main execution loop and user input. |
| `showMenu()` | Prints the UI options to the console. |
| `powerCalc()` | Performs the scientific power calculation using iteration. |

---

## 💻 How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ayushkumardubey-art/ayush-RU-25-11741.git


    ```
2.  **Compile the code:**
    ```bash
    gcc main.c -o calculator
    ```
3.  **Run the executable:**
    ```bash
    ./calculator
    ```

---

## 📸 Output Screenshots

| **Menu Interface** | **Calculation Example** |
| :---: | :---: |
| <img src="Menu Interface.jpg" width="300" /> | <img src="Calculation Example.jpg" width="300" /> |

---

> **Note:** This project was submitted as part of the internal assessment for the academic year 2025-2026.
