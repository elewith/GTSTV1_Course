# Core of Python Programming
## Indexing
## Slicing
- In Python it is possible to access a section of items from the list using theslicing operator ' :' , not just a single item.
- Syntax:
  - Mylist[ start : stop : step ]
- Slicing is indexing syntax that extracts a portion from a list. If a is a list, thena[m:n] returns the portion of a:
  - Starting with postion m
  - Up to but not including n
  - Negative indexing can also be used
- It is more applicable for strings.
## User Input handling
- On python there are 2 types of inputs
  - By input function
  - By Arguments

1.By input functions,
  - Syntax: var = input(“Text you like to display: ”)
  - Will accept the input and stores on variable
- we can change the input type to int() float() eval() str()….

2.Arguments
- This help us to get the input from the command lines
- Shell: python gtst.py arg1 arg2 arg3
## Operators
- Operators are special symbols that perform operations on variables and values.
- There are lots of operators type on python:

A. Arithmetic operators
- They are a simple maths operationsInputs have to be in int,eval, float only
- there are addition(+), substraction(-),multiplcation(*),division (/),power(**),modulo(%)

B. Assignment Operators
- Assignment operators are used to assign values to variables
- You do the arithmetic operators 1st , then the equal sign.

C. Comparison Operators
- Used to compare to variables and return boolean result
- Boolean means either TRUE or FALSE
- operaters like graterthan,lessthan,not equal etc

D. Logical Operators
- They are used to check if an expression is TRUE or FALSE
- They use Truth tables to compare.
- operaters like and (&),or(|),not etc

E. Bitwise Operators
- Bitwise Operators Used to do maths(Logical operations) on The binary value of The expression.
- There are:

1. Compliment ( Not) (~)
 * It will convert the first value to binary and it will reverse each bit
then converts to decimal.
- In simple maths, it will add 1 to the number and then makes it
negative.

  2. And ( & )
- You can add 0 before the binary of any number if it is not 4 digit binary
eg print(10&7) results 2

  3. Or ( | )
- Same as AND but the logic operator will be changed
eg print(10|7) results 15

  4. Xor ( ^ )
- It is like and , or but the difference is the logic here is
  - If they are same = 0 1^1 = 0 , 0^0 = 0
  - If they are different = 1 1^0 = 1 , 0^1 = 1
  eg print(10^7) results 13

  5. Left Shift (<<)
- Every Numbers have .0 at the end => 1.0 ,32.0 ….
eg print(10<<2) results 40

  6. Right shift (>>)
eg print(10>>2) results 2

F. Special Operators

## indentations
- Are Just a WhiteSpace which python uses for some of its function. If
there is no proper indentation error then you are doomed.
## If-else conditions
- In computer programming, we use the if statement to run a block code only when a certain condition is True.
- In Python, there are three forms of the if...else statement.
1. if statement
- The if statement evaluates condition.
 - If condition is evaluated to True, the code inside the body of if is executed.
  - If condition is evaluated to False, the code inside the body of if is skipped.
- syntax
   if condition:
    body
2. if...else statement
- An if statement can have an optional else clause.
- The syntax of if...else statement is:

if condition:
 body
 else: 
  body (print)

3. if...elif...else statement
- If condition1 evaluates to True, codeblock 1 is executed.
- If condition1 evaluates to False, thencondition2 is evaluated.
- If condition2 is True, code block 2 isexecuted.
- If condition2 is False, code block 3 isexecuted.

if condition:
 body
 elif:
  body (print)
  else:

4.Nested if statements 
- We can also use an if statement inside of an if statement. This is known as a
nested if statement.
- Here two requirements have to be true to run the body of condition2
## Logical Errors ( Exceptions)
- Errors that occur at runtime (after passing the syntax test) are called
exceptions or logical errors.
- For instance, they occur when we
  - try to call an index that is greater than the list have causes ( IndexError )
  - try to divide a number by zero (ZeroDivisionError)
  - When you have error on your syntax (NameError) and so on.
- So specially when errors occur on runtime this causes a huge damage on ourprogram so we have to handle it.
## Error handling
- For handling errors we use try…except blocks.
## Python Loops
- In computer programming, loops are used to repeat a block of code.
- There are 2 types of loops in Python:
  - For Loop
  - While Loop
### for loop
- In Python, the for loop is used to run a block of code for a
certain number of times. It is used to iterate over any
sequences such as list, tuple, string, etc.
syntax: for vai in sequence
         statement
- Sequence is a list,tuple,string or range.
- Val is a variable which will hold the iteration from the
sequence.
- %% Range keyword
  -A range is series of values between two numeric intervals. range(size)
- %% len keyword
  -A len is used to show the length of a sequence may be list,tuple or staffing. len(list)
### While loops
- Python while loop is used to run a specific code until a certain condition ismet.
 Syntax: while condition:
          body
- The for loop is usually used when the number of iterations
is known.
- And while loop is usually used when the number of
iterations are unknown. When we have condition.
- For loops: ends when the iterable is finished.
- While loops: end when the condition is false.
## break
- Break used to exit from an infinite loop.