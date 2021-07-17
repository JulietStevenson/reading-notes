# Operators

**Operators:** capable of manipulating a certain value or operand
- used to perform specific mathematical and logical computations
- compare values, perform arithmetic
- Binary and unary operators

## Types of Operators

**Assignment Operators:** assigns a value to its left operand based on the value of its right operand
- `x = y` assigns the value of y to x
- each assignment is evaulated **right** to **left**

**Comparison Operators:** compares its operands and retursn a logical value based on if the comparison is true
- may be numerical, string, logical, or object values

`==` Equal
`!=` Not equal
`===` Strict equal
`!==` Strict not equal
`>` Greater than
`>=` Greater than or equal
`<` Less than
`<=` Less than or euqal

**Arithmetic Operators:** takes numerical values and returns a single numerical value
- standard arithmetic operators are addition `+`, subtraction `-`, multiplication `*`, and division `/`

`%` Remainder
`++` Increment of 1
`--` Decrement of 1
`-` Unary Negation
`+` Unary Plus
`**` Exponentiation

**Logical Operators:** typically used with Boolean values and return a boolean value. 
- `&&` and `||` can be used with non-boolean values and will return a non-Boolean value

`&&` Logical AND
`||` Logical OR
`!` Logical NOT

**String Operators:** the concatenation operator `+` concatenates two string values together and returns another string that is the union of the two operand strings

**Comma Operator:** evaluates both of its operands and returns the value of the last operand
- Primarily used inside a for loop

**Unary Operators:** operations with only one operand 

`delete`: deletes an objects property

`typeof`: returns a string indicating the type of the unevaluated operand

`void`: specifies an expression to be evaluated without returning a value

**Relational Operators:** compares its iperands and returns a Boolean value based on whether the comparison is true

`in`: returns true if the specified property is the specified object

`instanceof` returns true if the specified object is of the specified object type
- when you need to confirm the type of an object at runtime

**Operator Precedence:** determines the order they are applied when evaluating an expression
- May override precedence by using parentheses

## Expressions

**Expression:** any valid unit of code that resolves to a value
- Arithmetic: evaluates to a number

- String: Evaluates to a character string

- Logical: Evaluaets to true or false

- Primary: Basic keywords and general expressions
    `this` refers to a current object
    `validate` validates an object's value property

- Lef-hand-side: left values are the destination of an assignment
    `new` create an instance of a user-defined object type
    `super` call functions on an object's parent

# Loops and Iteration

**Loops:** Offer a quick and easy way to do something repeatedly
- will repeat an action some number of times

**for:** loop that repeats until a specified condition evaluates to `false`

> `for ([initialExpression]; [conditionExpression];``>[incrementExpression])`
>  `statement`

1. Initializes the expression one or more loop counters
2. `conditionExpression` is evaluated and if the value of the conditional expression is true, the loop continues to execute. If not, the loop will terminate
3. Statement will execute
4. If present, the updated expression is executed
5. returns to step 2

**while:** executes its statements as long as a specified condition evaluates to true

> `while (condition)`
>  `statement`

- if the condition becomes false, the statement will stop executing

[HOME](README.md)