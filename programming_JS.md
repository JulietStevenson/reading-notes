# Programming in JavaScript

## Operators & Expressions

**Operators:** used to perform mathematical and logical computations
- Many different types:
    - Assignment 
    - Arithmetic
    - String
    - Numbers
    - Comparison
    - Logical 
    - Type
    - Bitwise

**Expressions:** any valid unit of code that resolves to a value

## Functions

**Function:** a block of code designed to perform a particular task
- Must take an input and return an output where there is some relationship between the input and output
- Executed when "something" evokes it
- Many different kinds of functions
- Reuse code many times with different arguments to produce different results 

1. Declare a function
    - Name of the function
    - List of parameters enclosed in parentheses
    - JavaScript statements that define the function enclosed in curly brackets

> `function square(number) {`
> `return number * number;`   
>`}`

2. Calling a function
    - Actually performs the specified actions with the indicated parameters
    - must be in scope when they are called

> `square(5);`

3. Function will stop when it reaches a `return` statement
- computes a return value

**Function Scope:** variables defined insode a function cannot be accessed from anywhere outside the function
- a function can access all variables and functions defined inside the scope in which it is defined 

**Function Expressions:** function keyword can be used to define a function inside of an expression 
- Convenient when passing a function as an argument to another function

**Recursive Function:** a function that calls itself

## Control Flow

**Control Flow:** the order in which the computer executes statements in a script
- Code is run from the first line to the last line unless the computer runs across strucutres that change the control flow
    - conditionals: `if...else`
    - loops

[HOME](README.md)