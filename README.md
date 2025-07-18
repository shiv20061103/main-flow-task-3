🧑‍💻 Objective
This project contains a collection of beginner-level Python programs that demonstrate the use of user-defined functions to solve common problems. Each program focuses on basic problem-solving, clean logic, and clarity in user input/output.

✅ List of Tasks Completed

Multiplication Table
Approach: A function takes an integer n as input and prints its multiplication table using a simple for loop.
Key Challenge: Ensuring the function handles all integers, including edge cases like 0.
Solution: Used a loop from 1 to 10 and printed n * i for each step.
Swap Two Numbers (No Third Variable)
Approach: Used arithmetic (addition and subtraction) inside a function to swap two values.
Key Challenge: Avoid using a third variable as per restriction.
Solution: Swapped values using a = a + b, b = a - b, a = a - b.
Check Substring
Approach: A function checks if one string exists within another using the in keyword.
Key Challenge: Making the function return only boolean and keeping input/output clean.
Solution: Used return s2 in s1 for simplicity and performance.
Decimal to Binary Converter
Approach: Wrote a function that manually converts a decimal number to binary by dividing by 2 and storing remainders.
Key Challenge: Avoid using built-in functions like bin() (though an alternative version with bin() was also explored).
Solution: Repeated division and stored bits in reverse order.
Matrix Addition
Approach: Two 2D matrices are taken as input, and their sum is calculated using nested loops.
Key Challenge: Handling user input in matrix form and ensuring both matrices are the same size.
Solution: Input functions for rows and columns, and clean formatting of output using loops.
Matrix Multiplication
Approach: Implemented using the dot product rule of rows and columns with triple nested loops.
Key Challenge: Checking that matrix dimensions are compatible (columns of A = rows of B).
Solution: Added a validation check before performing multiplication.
Find Second Largest
Approach: A function iterates through the list to find the largest and second largest unique values.
Key Challenge: Handling duplicate values and short lists.
Solution: Used two-pass comparison (first and second) and fallback for invalid inputs.
Check Anagram
Approach: Two strings are cleaned (lowercase, no spaces), sorted, and compared.
Key Challenge: Removing spaces and ignoring case sensitivity.
Solution: Used sorted() with cleaned strings and returned True or False.
AI-Based Tic-Tac-Toe (Minimax)
Approach: Implemented a full terminal-based game with a minimax-based AI for unbeatable performance.
Key Challenge:
Designing the recursive minimax algorithm.
Handling all possible end conditions (win/draw/invalid move).
Making the AI "think" like a human player.
Solution: Used game theory principles to write a minimax() function that evaluates all possible future moves and chooses the best one. The board is displayed in a user-friendly way and all invalid inputs are handled gracefully.

🔚 Conclusion

This project helped reinforce:
Writing clean and modular Python code.
Using functions to organize logic and improve reusability.
Implementing beginner to intermediate algorithms like minimax.
Taking matrix input from users and validating edge cases.
