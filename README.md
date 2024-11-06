Decimal to Binary Converter
===========================

This C++ program converts a decimal number to binary, separating the integer and fractional parts. 
The integer part uses a stack-linked list for conversion, and the fractional part uses a queue-linked list.

Files
-----
1. main.cpp - Main function handling user input and program flow.
2. stack.h / stack.cpp - Stack class for integer part binary conversion.
3. queue.h / queue.cpp - Queue class for fractional part binary conversion.
4. README.txt - Project documentation.

How It Works
------------
- The program prompts the user to enter a decimal number (e.g., 10.625).
- Converts the integer part using a stack and the fractional part using a queue.
- Outputs the complete binary representation (e.g., 10.625 -> 1010.101).

Compilation and Execution
-------------------------
Compile with:
    g++ main.cpp stack.cpp queue.cpp -o DecimalToBinary

Run with:
    ./DecimalToBinary

Example
-------
Input: 10.625  
Output: 1010.101

License
-------
Open-source under the MIT License.
