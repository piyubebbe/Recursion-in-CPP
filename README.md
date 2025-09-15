# Recursive Programs in C++

This repository contains four simple C++ programs demonstrating the use of recursion to solve different problems:

1. Factorial calculation  
2. Sum of natural numbers  
3. Reverse a string  
4. Reverse digits of a number  

---

## 1. Factorial Calculation

**Theory:**  
The factorial of a non-negative integer `n` is the product of all positive integers less than or equal to `n`. It is denoted as `n!`. By definition, `0! = 1` and `1! = 1`. Factorials grow very fast and are useful in permutations, combinations, and many areas of mathematics.

**Algorithm:**  
1. If `n` is 0 or 1, return 1 (base case).  
2. Otherwise, return `n * factorial of (n-1)` (recursive call).  
3. Continue until the base case is reached.

---

## 2. Sum of Natural Numbers

**Theory:**  
The sum of the first `n` natural numbers is the total obtained by adding all integers from 1 to `n`. This can be computed iteratively or recursively.

**Algorithm:**  
1. If `n` is less than or equal to 1, return 1 (base case).  
2. Otherwise, return `n + sum of (n-1)` (recursive call).  
3. Continue adding until the base case is reached.

---

## 3. Reverse a String

**Theory:**  
Reversing a string involves printing the characters from the last to the first. Recursion can be used to traverse to the end of the string, then print characters on returning from each recursive call.

**Algorithm:**  
1. Check if the current character is the null terminator `\0` (base case).  
2. If not, recursively call the function with the next character.  
3. Print the current character after the recursive call returns.  
4. This prints the string in reverse order.

---

## 4. Reverse Digits of a Number

**Theory:**  
Reversing digits of an integer means printing the digits from last to first. By taking the modulus and division by 10, digits can be extracted and printed recursively.

**Algorithm:**  
1. If `n` is not zero, print the last digit `n % 10`.  
2. Recursively call the function with `n / 10`.  
3. Continue until `n` becomes zero (base case).

---

## Conclusion

These programs demonstrate the power and elegance of recursion in solving problems that involve repetitive or self-similar structures. Recursion simplifies code by breaking down complex tasks into smaller, manageable subproblems. Understanding these examples is fundamental for mastering recursion and applying it effectively in various algorithmic challenges.

