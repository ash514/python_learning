## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Because they are not written in machine-readable language, Python programs need to be processed before machines can run them. Python is an interpreted language. 
This means that every time a program is run, its interpreter runs through the code and translates it into machine-readable byte code.

Q2. Why is Python called a dynamically typed language?
 Python is a dynamically typed language. It doesn’t know about the type of the variable until the code is run. So declaration is of no use. What it does is, 
 It stores that value at some memory location and then binds that variable name to that memory container.  And makes the contents of the container accessible
 through that variable name. So the data type does not matter. As it will get to know the type of the value at run-time.

Q3. List some pros and cons of Python programming language?
PROS:
*It's Simple.
*It's Free.
*It's Easy to Use.
*It's Highly Compatible.
*It is Object-Oriented.
*It has Lots of Libraries.
*It has Built-in Data Structures.

CONS:
Poor Memory Efficiency. To make it simple for the developer, Python needs a lot of memory space; this can be a tad problematic if you want to develop apps where you need to
*optimize memory.
*Slow Speed. ...
*Database Access. ...
*Weak in Mobile Computing. ...
*Runtime Errors.

Q4. In what all domains can we use Python?
1. Data Science
2. Automation
3. Application Development 
4. AI & Machine Learning 
5. Networking and Internet Development :
 Python provides two levels of access to network services. At a low level, you can access the basic socket support in the underlying operating system, which allows you 
 to implement clients and servers for both connection-oriented and connection-less protocols. Python also has libraries that provide higher-level access to specific 
 application-level network protocols, such as FTP, HTTP, and so on.Modules like urllib , socket, and the infamous requests (HTTP for humans) make it an ideal choice for
 networking. Also, beautifulsoup, selenium are very effective for stuff like automation, scrapping, etc.
 
Q5. What are variable and how can we declare them?
Variable is a name given to a specific memory location.
example:
a=5
name='ashu'


Q6. How can we take an input from the user in Python?
for taking input from the user in python we can use input() function.
example:
name=input("Enter the value for name=")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
The input() function by default returns the value as string data type​.

Q8. What is type casting?
In type casting, the compiler automatically changes one data type to another one depending on what we want the program to do. For instance,
in case we assign a float variable (floating point) with an integer (int) value, the compiler will ultimately convert this int value into the float value.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Q10. What are keywords?
Keyword	Description
and	--A logical operator
as --To create an alias
assert	--For debugging
break	--To break out of a loop
class	--To define a class
continue	--To continue to the next iteration of a loop
def	--To define a function
del	--To delete an object
elif	--Used in conditional statements, same as else if
else	--Used in conditional statements
except	--Used with exceptions, what to do when an exception occurs
False	--Boolean value, result of comparison operations
finally	--Used with exceptions, a block of code that will be executed no matter if there is an exception or not
for	--To create a for loop
from	--To import specific parts of a module
global	--To declare a global variable
if	--To make a conditional statement
import	--To import a module
in	--To check if a value is present in a list, tuple, etc.
is	--To test if two variables are equal
lambda	--To create an anonymous function
None	--Represents a null value
nonlocal	--To declare a non-local variable
not	--A logical operator
or	--A logical operator
pass	--A null statement, a statement that will do nothing
raise	--To raise an exception
return	--To exit a function and return a value
True	--Boolean value, result of comparison operations
try	--To make a try...except statement
while	--To create a while loop
with	--Used to simplify exception handling
yield	--To end a function, returns a generator

Q11. Can we use keywords as a variable? Support your answer with reason.
Python Keywords
----------------
Keywords are predefined, reserved words used in Python programming that have special meanings to the compiler.
We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language.
All the keywords except True, False and None are in lowercase and they must be written as they are. The list of all the keywords is given below.

Q12. What is indentation? What's the use of indentaion in Python?
Python Indentation
-------------------------
Indentation refers to the spaces at the beginning of a code line.
Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.
Python uses indentation to indicate a block of code.
Example
if 5 > 2:
  print("Five is greater than two!")
  
The number of spaces is up to you as a programmer, but it has to be at least one.

Q13. How can we throw some output in Python?

Q14. What are operators in Python?
+	Addition: adds two operands	x + y
–	Subtraction: subtracts two operands	x – y
*	Multiplication: multiplies two operands	x * y
/	Division (float): divides the first operand by the second	x / y
//	Division (floor): divides the first operand by the second	x // y
%	Modulus: returns the remainder when the first operand is divided by the second	x % y
**	Power: Returns first raised to power second	x ** y

Q15. What is difference between / and // operators?
/->used for float division
//->used for integer division

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
a="iNeuron"*4
print(a)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
number=int(input("Enter the Value Number"))
if number%2==0:
	print("Even")
else:    
    print("Odd")	
	
Q18. What are boolean operator?
Booleans represent one of two values: True or False.
Example:
print(10 > 9)
print(10 == 9)
print(10 < 9)


Q19. What will the output of the following?
1 or 0 -->True
0 and 0 -->false
True and False and True-->False
1 or 0 or 0 -->True


Q20. What are conditional statements in Python?
if
elif
if..else
Nested if statement

Q21. What is use of 'if', 'elif' and 'else' keywords?
1.if Statement
=============================
If the simple code of block is to be performed if the condition holds true then if statement is used.
Here the condition mentioned holds true then the code of block runs otherwise not.
Syntax:
if condition:           
   # Statements to execute if
   # condition is true

2.if..else Statement
==========================
In conditional if Statement the additional block of code is merged as else statement which is performed when if condition is false. 
Syntax:  
if (condition):
    # Executes this block if
    # condition is true
else:
    # Executes this block if
    # condition is false

3.Nested if Statement
====================================
if statement can also be checked inside other if statement. This conditional statement is called a nested if statement.
This means that inner if condition will be checked only if outer if condition is true and by this, we can see multiple conditions to be satisfied.

Syntax:  
if (condition1):
   # Executes when condition1 is true
   if (condition2): 
      # Executes when condition2 is true
   # if Block is end here
# if Block is end here

4.if-elif Statement
==============================
The if-elif statement is shortcut of if..else chain. While using if-elif statement at the end else block is added which is performed if none of the above if-elif statement is true.
Syntax:-  

if (condition):
    statement
elif (condition):
    statement
.
.
else:
    statement
	
	
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
age=int(input("Enter the Value of age"))   
if age>=18:
    print("I can vote")
else:
    print("I can't vote")   
	
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
List = [12, 75, 150, 180, 145, 525, 50]
print("\nList of numbers: ")
print(List)
sum=0
for i in List:
    if i%2==0:
        sum+=i
print(sum)   


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
num1=int(input("Enter the Value of num1:"))
num2=int(input("Enter the Value of num2:"))
num3=int(input("Enter the Value of num3:"))
if num1>num2:
    print("num1 is greater=",num1)
elif num2>num3:
    print("num2 is greater=",num2)
else:
    print("num3 is greater=",num3)     
	
	
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
List = [12, 75, 150, 180, 145, 525, 50]
print("\nList of numbers: ")
print(List)
for i in List:
    if i>500:
        break
    elif i>150:
        continue
    elif i%5==0:
        print(i)