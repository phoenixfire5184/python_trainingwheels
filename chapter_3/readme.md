# Practice Problems  - Chapter 3
### 1. Why are functions advantageous to have in your programs?
```
They help reduce redundancy and improve code quality .
```
### 2. When does the code in a function execute: when the function is defined or when the function is called?
```
The code executes when the function is called .
```
### 3. What statement creates a function?
``` 
def function_name()
```
### 4. What is the difference between a function and a function call?
```
Function refers to the block of code while the function call refers to the instance where the function code is invoked in the program 
```
### 5. How many global scopes are there in a Python program? How many local scopes?
```
Python has a global scope created at the start of the program and ends with the program while local scopes amount to the same no. of functions in the program .
```
### 6. What happens to variables in a local scope when the function call returns?
```
The local scope is destroyed after the function ends/returns.
```
### 7. What is a return value? Can a return value be part of an expression ?
```
Return values are the stuff that functions return to the part where they are called in the program .
```
### 8. If a function does not have a return statement, what is the return value of a call to that function?
```
The function returns a null value (None).
```
### 9. How can you force a variable in a function to refer to the global variable?
```
Using the global keyword.
```
### 10. What is the data type of None ?
```
Null is the datatype of None .
```
### 11. What does the import areallyourpetsnamederic statement do? 
``` 
It importa a module of the name "areallyourpetsnamederic"
```
### 12. If you had a function named bacon() in a module named spam, how would you call it after importing spam?
```
import spam
spam.bacon()
```
### 13. How can you prevent a program from crashing when it gets an error?
```
Using exception handling (try , except).
```
### 14. What goes in the try clause? What goes in the except clause?
```
The block of code that may contain the problems is enveloped in the try part and the code that has to be executed if the earlier mentioned code leads to an error is enclosed within the except part .
```
