# Programming with JavaScript

## Intro + Scripts: Pages 1 - 24

* ACCESS, MODIFY, PROGRAM, REACT
* What is script? A series of instructions that a computer can follow to achieve a goal. Every time a computer performs a task it's like it's learning it for the first time, so you need to be explicit and detailed. 
* To write script: (1) Define the goal, (2) Design the script, (3) Code each step
* Always important to define the goal of your script before you start coding. Then, break it down into a series of tasks. Flow chart are useful for this. 

## Expressions + Operators: 74 - 79
* Expressions: Two kinds of expressions (1) Expressions that just assign a value to a variable (2) Expressions that use two or more values to return a single variable
* Operations: assignment operators, arithmetic operators, string operators, comparison operators, logical operators

Name | Operator | Purpose & Notes
------------ | ------------- | -------------
Addition | + | Adds one value to another
Subtraction | - | Subtracts one value from another
Division | / | Divides two values
Multiplication | * | Multiplies two values
Increment | ++ | Adds one to the current number
Decrement | -- | Subtracts one from the current number
Modulus | % | Divides two values and returns the remainder

Use order of operations with your formulas. 

## Functions: 88 - 94
* Functions let you group a series of statements together to perform a specific task: calling, parameters, return value
* Programming languages often rely on name/value pairs

### Declaring a Function
```js
function sayHello() {
    document.write('Hello!');
}
```
### Calling a Function
```js
sayHello();
```

### Functions that Need Information
```js
function getArea(width, height) {
    return width * height;
}
```

### Getting single value out of a function
```js
function calculateArea(width, height) {
    var area = width * height;
    return area;
}
var WallOne = calculateArea(3, 5);
var WallTwo = calculateArea(8, 5);
```

[⬅ Back to README Home](README.md)