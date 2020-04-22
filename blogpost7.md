[Home](README.md) || [My GitHub](https://github.com/leahgrace555)

# Programming with Javascript

A script is a series of instructions that a computer follows to acheive a goal

When designing a script, consider these steps:

1. Define the goal
2. Design the script
3. Code each step

Once you know the goal of the script, you can work out the individual tasks you need to acheive it. Programmers will often use flow charts to work out how tasks fit together. 

## Expressions and Operators

**Expressions** result in a single value. There are two types of expressions: expressions that assiing a single value to a variable, and expressions that use two or more values to return a single value.

Expressions rely on **operators** to create single values from two or more values

### Arithmatic Operators: 

| Name        |Operator    |Purpose      |
|-------------|------------|-------------|
|addition     |+           | Adds values together|
|Subraction   | -          |subtracts values from one another
|Division     |          / | Divides two values
|Multiplication | *        | multiplies two values
|Increment    | ++         | Adds one to the current value|
|Decrement    | - -        | Subtracts one from the current value
Modulus       | %          | Divides two values and returns the remainder|

The order of operations apply here as they do in math. Multiplication and division are performed before addition and subtraction. To change the order of operations, use parentheses to indicate which operation should be performed first. 

### String Operators:

The only string operator is '+'. It is used to join two strings on either side of it.

Things to note:

***Adding a numeric value to a string makes it become part of the string***

For example: '5' + 5 will **NOT** return a value of 10. Instead, the second 5 will be added to the string and return a value of '55'. 

Attempting to multiply two strings will return a value of "NaN", or "Not a Number"

## Functions

To use a function, you must first declare it. 
````
function sayHello() {
    document.write('hello')
};
````
In the above example, the function is declared using the function keyword, the function is named 'sayHello', and the curly braces contain the code block with instructions for the function to perform. 

Once a function has been delcared, you can execute the function by calling it:
````
sayHello();
```
