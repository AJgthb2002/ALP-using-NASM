# ALP (using NASM)
Collection of Assembly Language programs developed by me for second year engineering course- Microprocessor Architecture
***
**1. Arithmetic Operations:** </br>
Performs Addition, Subtraction, Multiplication and Division on 2 input numbers and displays the results. </br>
(Input numbers must be single digit)
```
ARITHMETIC OPERATIONS
 
Enter first number: 4 
Enter second number: 2 
 
Addition is: 6 
Subtraction is: 2 
Multiplication is: 8 
Division is: 2 
Remainder is: 0 
```
***
**2. Find Substring from Indexes:** </br>
Finds the substring of the given string from the start and end indexes entered by user. </br>
(Given string is hardcoded, while the indexes are input by user)
```
Given string is : GoodMorning 
Enter start index: 4 
Enter end index: 7 
Substring is: Morn
```
***
**3. Menu Driven program for String Operations:** </br>
Inputs a string (of max length 6) from user. </br>
Performs one of the 4 available operations depending on choice code entered by user.</br>

```
Given string is PeoPle 
Choose: 
1) Uppercase
2) Lowercase 
3) Toggle
4) Concatenate
1 
The uppercase string is: PEOPLE

Given string is PeoPle 
Choose: 
1) Uppercase
2) Lowercase 
3) Toggle
4) Concatenate
2 
The lowercase string is: people

Given string is PeoPle 
Choose: 
1) Uppercase
2) Lowercase 
3) Toggle
4) Concatenate
3 
Toggled output: pEOpLE

Given string is PeoPle 
Choose: 
1) Uppercase
2) Lowercase 
3) Toggle
4) Concatenate
4 
Enter another string to concatenate: good
 
Concatenated string:  PeoPlegood
```
***
**4. Separation of positive and negative numbers:** </br>
Inputs some numbers from the user, and stores each number in either positive or negative array, by comparing it with the ASCII value of 0. 
Displays the total count of positive and negative numbers, and displays both the arrays.</br>
```
Enter the number of elements: 8 
Enter the elements:  
-1 
-2 
3 
4 
-5 
6 
9 
8 
 
 
Positive numbers: 5 
3 4 6 9 8  
Negative numbers: 3 
-1 -2 -5 
```
