# C-Programming
1. Sales of a shop
2. Sum of last two digits
3. Roots of a quadratic equation
4. Finding letter grade
5. Sine series 
6. Print calendar of a month
7. The area under the curve y=log(x)
8. calculating nCr
9. Finding x^n
10. Surface area and volume of a cuboid 
11. set difference 
12. Bubble sort 
13. Binary search 
14. Swap in an array 
15. Identity matrix 
16. Matrix multiplication 
17. Caesar cipher
18. Substring search 
19. Finding topper of a batch 
20. Bitwise operations

---

## 1. Sales of a shop.
Write a program to calculate the total sales of a shop. Given the unit price, quantity, discount rate, and sales tax rate of a particular product. The sales tax is 8.5%, which should be specified using a definite constant. The output should be displayed in proper form using appropriate formate specifier.



## 2. Sum of last two digits.
Write a program to extract and add the two least signification digits of an integer using the following user-defined functions:
a) A function that obtains the unit place digit of a given number.
b) A function that obtains the tenth place digit of a given number.
c) Function that adds unit and tenth place digit of a given number 
The ``` main() ``` function should call the above user-defined functions.


## 3. Roots of the quadratic equation.
Write a program using ``` switch ``` statement to find all the possible roots of a quadratic equation.  Display suitable error message for invalid inputs write a user-defined function ``` fncalc ``` discriminant to calculate the discriminant.



## 4. Finding letter grade.
### 1. Write a program using a ``` switch ``` to read the marks quiz1, quit2, quit3, quit4, test1, test2, and final exam of a student in one-course maximum marks for each exam is given in table 1 below. Calculate the total of all the marks and print the appropriate grade to the student as given in the table 
### 2. User must use ``` ceil() ``` function to round up the value. The program calculates the internal CIE of students.



## 5. Sine series.
Write a program to find ``` sine ``` of an angle using the series ``` sin(x)= x-xpower3/3!+xpower5 /5! ... ``` for a given N term using the loop structure. Also print ```sin(x)``` using library function .



## 6. Print calendar of a month.
Write a program to display the calendar of a month whose starting day of the week and number of days in the month are given as input ``` (0,1,2,3,...6) ``` respectively represent Sunday, Monday, ..... Saturday respectively. Write a function print month which takes there values as parameters and prints the calendar of the month. Perform input validation as well.



## 7. Area under the curve y=log(x).
Write a program to calculate the area under the curve y=log(x) within a given left and right limit. Use trapezoidal approximate-function ``` fn ``` trapezoidal approximation, write a user-defined function ``` fntrapaera ``` to calculate the area of a trapezoid.




## 8. Calculating nCr.
Write a recursive C function to fine the factorial of a number, n!.  Defined by```  fact(n)=1 ``` , if ``` n=0 ```. otherwise ``` fact(n)=n* fact(n-1) ```. using this function write a program to compute the binomial co efficient ``` nCr ``` perform input validation as well.



## 9. Finding x power n.
Write a program in C to find the value of ``` 'x' ```  raised to the power ``` 'n' ``` using recursion 
Example: 
#### 1. x=5 n=3 x power n =125 
#### 2. x=2 n=-3 x power n =0.125000



## 10. Surface area and volume of the cuboid
Write a program that reads the length, breadth, and height of a cuboid the program has to calculate the surface arear and volume of the cuboid using the function ```fncalvol``` surface area the results are then to be displayed by the main function.



## 11. Set difference.
Write a program to find the difference of two set a (set have distinct elements)
A-B= {x|x belongs to A and X does not belong B}
Example: A = {1,3,5,7}
         B = {4,5,7}
         A-B ={1,3}
         
         
        
## 12. Bubble sort
Write a program that arrays N integer numbers in ascending order using bubble sort technique. Write uses defined functions for the following.
(i) Function to generate N random numbers in the range 0 to 999 and store it in an array.
(ii) Function to set N integer numbers in ascending order using bubble sort.
(iii) Function to display N integers.



## 13. Binary search.
Write a program that reads N integer numbers in sorted order and performs a search operation on input by accepting a key element from the user applying binary search method. Report the result of search as **SUCCESS** or *FAILURE* as the case may be write defined functions for the following.
(i) Function to read N integer numbers
(ii) Function to display N integer numbers
(iii) Function to search for key elements using binary search.



## 14. Swap smallest and largest elements in an array using pointers.
Write a program to the smallest and largest elements in an array using pointers and then swap these elements and display the resultant array.



## 15. Identity matrix.
Write a program to perform the following operations using user-defined functions
(i) Read M * N matrix
(ii) Display the matrix
(iii) To check whether a given matrix is identity or not identity matrix
The ```main``` function should call these functions.


## 16. Matrix multiplication.
Write a program that reads two matrices A(m*n) and B(p*q) and computes the product ``` A * B ```. Read matrix A in row-major order and matrix B in column-major order print both the input matrices and resultant with suitable headings and in a matrix format. Program must check the compatibility of orders of the matrices for multiplication display appropriate message in case of incompatibility.



## 17. Cassor cipher 
Write a program to implement ** cassor ** cipher input a message and then encode it by replacing each character in the message by a character that is there position ahead in the English alphabet sequence, wrap back to 'a' if the character is 'z' display the encoded message decode the message using the inverse procedure and display.



## 18. Substring search.
Write a program to read a line of text from the keyboard and print the number of occurrence of a given substring using the built-in function ``` strstr() ```.



## 19. Finding topper of a batch.
Write a c program in c that stores the details of N number of students given by the user 
The following are the information stored for each student 
(i) Name
(ii) USN
(iii) Marks scored in # subjects
Then find and display details of 
(i) Average marks of each student.
(ii) Topper of the batch.



## 20. Bitwise operation.
Write a program that reads an unsigned integer and then perform the following operations using user-defined function 
(i) Check given input is even or odd
(ii) To perform the swapping of two number
(both function should use bitwise operators only)
