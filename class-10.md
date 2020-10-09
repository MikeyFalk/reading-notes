
# Reading Notes Day 10

## JS Book

## Javascript book. Ch.10 "Error Handling & Debugging"

### Ways to find errors - 

Order of Execution - make sure you understand how scripts are processed. Its not always from top to bottom.

###Execution Contexts - 

Every statement is in 1 of 3 execution contexts

1. Global Context
code in script but not in a function

2. Function Context
code run in a function

3. Eval Context
code in an internal function

## Global and Function Context correspond with variable scope

### global scope

a variable declared outside a function

### function level scope

a variable declared in a function

### The Stack

- Javascript processes one line of code at a time. When statement needs data from another function, it stacks the new function on top of the current task.

- Execution Context and Hoisting 2 phases for of activity for each execution context

1. Prepare
    - new scope is created
    - variables, functions and arguements are created

2. Execute
    - Now it can assign values to variables
    - reference functions and run their code 
    - execute statements

***Lexical Scope - functions are like a nesting doll - the children can ask the parents for infomation on their variables, but the parents cannot get variables from their children. Each child will get the same answer from their parent.***

`try` `catch` `finally`
Exception handling code should inform users when there is a problem otherwise the code will stop and the user will not know why.


**Error objects** can help id where the error is ocurring there are 7 types 

- Understanding execution contexts with 2 satges and stacks, you are more likely to find the error in your code

- debugging is the process of finding error - you must use deduction

- use the console to find the line where the code isn't working

- JS 7 has 7 types of errors each creates its own object which can tell you its line number and gives a description of the error


[<-- Back](README.md)