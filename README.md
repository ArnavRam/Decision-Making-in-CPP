# Experiment 5 - Conditional Statements (If-Else, Switch-Case) in C++

---

## Aim
- To explore key decision-making structures in C++ including `if-else`, the `if-else-if` ladder, and `switch-case`.
- To implement foundational examples such as:
    1.  Checking if a number is odd or even.
    2.  Finding the largest of three numbers.
    3.  Identifying if a character is a vowel or a consonant.
    4.  Using a `switch` statement for menu-based selection.

---

## Tools Used
- Visual Studio Code
- MinGW-w64 with g++ Compiler

---

## Theory
Conditional statements control the flow of a program's execution based on evaluated conditions, allowing for dynamic and flexible logic. These constructs are crucial for enabling programs to respond to different inputs or states.

### `if-else` Statement
The `if-else` structure allows a program to make a binary decision. If a condition evaluates to true, one block of code is executed; otherwise, the alternate block in the `else` statement runs. It is useful for simple "yes or no" logic checks.

### `if-else-if` Ladder
This structure expands decision-making to multiple, sequential conditions. The program evaluates each condition from top to bottom. As soon as one condition is found to be true, its corresponding block runs, and the rest of the ladder is skipped. The final `else` acts as a default case if none of the prior conditions are met.

### `switch-case` Statement
The `switch-case` structure offers a cleaner alternative to a long `if-else-if` ladder when comparing a single variable against a series of discrete integer or character values. It matches the variable's value against predefined `case` labels and executes the matched block. A `default` case can be used to handle any value that doesn't match a specific case.

---

## Algorithm / Logic

### Program 1: Odd or Even Number Detection
1.  **Start**
2.  Declare an integer variable `num`.
3.  Prompt the user to enter a number and store it in `num`.
4.  Check if `num % 2 == 0`.
5.  If `true` → Display "Even".
6.  If `false` (in the `else` block) → Display "Odd".
7.  **End**

### Program 2: Largest of Three Numbers
1.  **Start**
2.  Declare three integer variables `a`, `b`, and `c`.
3.  Prompt the user to enter all three numbers.
4.  Compare using an `if-else-if` ladder:
    - If `a > b && a > c` → Display `a` is largest.
    - Else if `b > c` → Display `b` is largest.
    - Else → Display `c` is largest.
5.  **End**

### Program 3: Vowel or Consonant
1.  **Start**
2.  Declare a character variable `ch`.
3.  Prompt the user to enter a character and store it in `ch`.
4.  Check if `ch` is an alphabet character.
5.  If it is an alphabet, check if `ch` is 'a', 'e', 'i', 'o', 'u' (or their uppercase equivalents).
    - If `true` → Display "Vowel".
    - Else → Display "Consonant".
6.  If it is not an alphabet → Display "Not a letter".
7.  **End**

### Program 4: Month Selector Using `switch-case`
1.  **Start**
2.  Declare an integer variable `choice`.
3.  Display a menu of months (1 to 12).
4.  Prompt the user to enter a choice and store it in `choice`.
5.  Use a `switch` statement on the `choice` variable.
6.  For `case 1:` display "January", for `case 2:` display "February", and so on for all 12 months.
7.  Include a `default` case to display "Invalid Input" if the choice is not between 1 and 12.
8.  **End**

---

## Conclusion
Decision-making is at the heart of intelligent programming. This experiment demonstrated how to branch logic with `if-else`, scale conditions with `else-if` ladders, and simplify discrete options with `switch-case`. Mastering these structures is essential for writing smarter, more dynamic code that can respond appropriately to a variety of conditions.
