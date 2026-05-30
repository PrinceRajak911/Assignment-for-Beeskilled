# ?? Even/Odd & Prime Number Checker

A Python command-line utility that takes an integer input from the user and determines two things: whether the number is Even or Odd, and whether or not it is a Prime number. 

This project demonstrates modular programming using functions, mathematical logic, and efficient algorithm design.

## ?? Features

* **Parity Checker:** Uses the modulo operator (`%`) to accurately determine if a number is Even or Odd.
* **Optimized Prime Checker:** Efficiently calculates primality by handling edge cases (like negatives, 0, 1, and 2) and only iterating through odd potential factors up to the square root of the target number.
* **Error Handling:** Prevents program crashes by catching `ValueError` exceptions if the user inputs text or symbols instead of an integer.

## ??? How to Run

1. Ensure you have [Python](https://www.python.org/) installed on your machine.
2. Clone this repository or download the `number_checker.py` file.
3. Open your terminal or command prompt.
4. Run the script using the following command:

   ```bash
   python number_checker.py