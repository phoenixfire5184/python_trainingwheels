# Practice Problems  - Chapter 2
### 1. What are the two values of the Boolean data type? How do you write them?
```
True and False
```
### 2. What are the three Boolean operators?
```
AND , NOT , OR
```
### 3. Write out the truth tables of each Boolean operator (that is, every possible combination of Boolean values for the operator and what they evaluate to).

| VAL_1 | VAL_2 |  OR  |  AND  |
|-|-|-|-|
|T|T|T|T|
|T|F|T|F|
|F|T|T|F|
|F|F|F|F|

|VAL_3|NOT|
|-|-|
|T|F|
|F|T|

### 4. What do the following expressions evaluate to?
```
(5 > 4) and (3 == 5)                        F
not (5 > 4)                                 F
(5 > 4) or (3 == 5)                         T
not ((5 > 4) or (3 == 5))                   F
(True and True) and (True == False)         F
(not False) or (not True)                   T
```
### 5. What are the six comparison operators?5. What are the six comparison operators?
```
==
!=
>=
<=
>
<
```
### 6. What is the difference between the equal to operator and the assignment operator? 
```
== Checks if both values are equal , while = assigns the RHS to the LHS.
```
### 7. Explain what a condition is and where you would use one.
```
Conditions are expressions that evaluate to either true or false and its used widely for flow control .
```
### 8. Identify the three blocks in this code
```
spam = 0                        -block 1
if spam == 10:
    print('eggs')               -block 2
    if spam > 5:
        print('bacon')          -block 3
```
### 9. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints Greetings! if anything else is stored in spam.
```
if (spam==1)
    print('Hello')
elif(spam==2)
    print('Howdy)
else
    print('Greetings!')
```
### 10. What keys can you press if your program is stuck in an infinite loop?
``` 
Ctrl + C
```
