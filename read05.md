 # Comparison Operators
## JavaScript language includes operators that compare two operands and return Boolean value true or false.


## Operators	Description :
==	Compares the equality of two operands without considering type. 
===	Compares equality of two operands with type.
!=	Compares inequality of two operands.
**> **	Checks whether left side value is greater than right side value. If yes then returns true otherwise false.
<	Checks whether left operand is less than right operand. If yes then returns true otherwise false.
**>=**	Checks whether left operand is greater than or equal to right operand. If yes then returns true otherwise false.
<=	Checks whether left operand is less than or equal to right operand. If yes then returns true otherwise false.

Example about it:
var a = 5, b = 10, c = "5";
var x = a;

a == c; // returns true### **this operators compare a value.**

a === c; // returns false **this operators compare a value and data type.**

a == x; // returns true

a != b; // returns true

a > b; // returns false

a < b; // returns true

a >= b; // returns false

a <= b; // returns true

a >= c; // returns true

a <= c; // returns true


# Logical Operators
## Logical operators are used to combine two or more conditions. JavaScript includes following logical operators.

**&&	&&** is known as AND operator. It checks whether two operands are non-zero (0, false, undefined, null or "" are considered as zero), if yes then returns 1 otherwise 0.
**||	||** is known as OR operator. It checks whether any one of the two operands is non-zero (0, false, undefined, null or "" is considered as zero).
**!	!** is known as NOT operator. It reverses the boolean result of the operand (or condition)
![logical operator](https://1.bp.blogspot.com/-E3z93RXYCGc/XfXd0T8x3FI/AAAAAAAAE04/zNAwwEov8cw-t353RBQ4rAq59znfY0C5QCLcBGAsYHQ/s1600/Screenshot%2B%2528455%2529.png)

## Loops in JavaScript
##### Looping in programming languages is a feature which facilitates the execution of a set of instructions/functions repeatedly while some condition evaluates to true.
 #### Java provides three ways for executing the loops. While all the ways provide similar basic functionality, they differ in their syntax and condition checking time.

 #### while loop: A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.
Syntax :
while (boolean condition)
{
   loop statements...
}
![figure about while](https://media.geeksforgeeks.org/wp-content/uploads/Loop1.png)
#### for loop: for loop provides a concise way of writing the loop structure. Unlike a while loop, a for statement consumes the initialization, condition and increment/decrement in one line thereby providing a shorter, easy to debug structure of looping.
Syntax :
for (initialization condition; testing condition; 
                              increment/decrement)
{
    statement(s)
}
![figure about for](https://media.geeksforgeeks.org/wp-content/uploads/loop2.png)