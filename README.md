# ATM & Banking Simulator (C++)

A console-based banking application written in C++ that simulates real-world ATM transactions with built-in data validation.

## Features
* **Account Management:** Check current balance, make deposits, and perform secure withdrawals.
* **Input Validation:** Prevents invalid deposit amounts (e.g., negative numbers) and blocks withdrawals that exceed the available balance.
* **Interactive Menu:** Uses a continuous loop and switch-case menu for a seamless user experience until exit.

## Concepts & Techniques Used
* **Modular Programming:** Split logic into clean, reusable functions (`showbalance`, `deposit`, `withdraw`).
* **Control Flow:** Implemented `switch-case` for menu navigation and `if/else` statements for safety checks.
* **Loops:** Used a `do-while` loop to keep the application running dynamically.
