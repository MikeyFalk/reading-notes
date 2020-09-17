# Programming with JavaScript

## Chapter 1a: Scripts

1. A script is a series of instructions that the computer can follow in order to achieve a goal
2. Each time the script runs it might only use a subset of all the instructions
3. Computers approach tasks differently than humans and need the solution presented programmatically to solve the task
4. To start writing script determine the goal then create a list of tasks to achieve the intended goal then work out each step needed to complete the task. Flow charts can be used to break up the problem into smaller parts.

## Expressions & Operators

1. An expression evaluates into (results in) a single value. 

   - Broadly speaking there are two types of expressions
        1. Expressions that just assign a value to a variable
            `var color = blue
        2. Expressions that use two or more values to return a single value
            `var area = 3 * 2 
            or
            `var greeting = 'hello' + userName

2. Operators: Expressions rely on operators to create a single value from one or more values

    - assignment operators: assign a value to a variable
        `color = blue;
    - Arthimetic operators: perform basic math
        `area = 3 * 2;
    - String operators: combine two strings
        `greeting = 'Hi' + 'Molly;
    - comparison operators: compare two values and return true or false (Boolean)
    - logical operators: combine expressions and return true or false

## Functions
 
- Functions are used to organize code reducing the need to write thousands of lines for complex code. Functions are a series of statements that have been grouped together because the perform a basic task
- Methods are functions created inside an object
- program will give the function a name which should be descriptive
- code block: consists of one or more statements contained within curly brackets, no semi colon after curly braces
- parameters: pieces of information passed to a function
- return value the name for what is returned after a function is run

Declare a Function
`function sayHello() {
    `document.write('Hello!);
`}

Calling a Function 
`// code before function
`sayHello();
`// code after function

 [<-- Back](README.md)