## Dynamic web pages with JavaScript

### Exercise 
This was my first go at cloning files that were not my own off GitHub and using them for a project on my computer. In this reading we followed instructions in our book to have our first go at coding in JavaScript! 

What I learned from this exercise is it's important to make sure the directories for your project are organized or things will not communicate well with each other. 

### How to use Objects & Methods
```js
document.write('Goodafternoon!');

[object][member operator][method[parameters]]
```
* Object: represents the entire web page
* Member operator: usually a period '.'
* Method: allows new content to be written into the page
* Parameters: Whenever a method requires some information in order to work, the data is given inside the parentheses

Javascript runs where it is found in the HTML, so you need to reference it with script tags in your HTML

### Chapter 2: Basic Javascript Instructions

Script is a series of instructions your computer follows. The instructions within the script are called **statements**. JavaScript consists of statements, curly brackets to indicate code blocks, and directions on which code should be run based on the scenario. 

Write comments to explain what your code does. Multiple line comments are pink bracketed with /* and */. Single line comments are grey and follow //

### Variables

```js
var quantity;
[variable keyword] [variable name or variable identifier];
```
You then want to assign a value to the variable:
```js
quantity = 3;
[variable name] [assignment operator] [variable value];
```
until you assign a value to the variable it is said to be 'undefined' 

### Data Type

Type | Definition
------------ | -------------
Number data type | handles number
String data type | consists of letters and characters and is enclosed with quotes
Boolean data type | true or false data


You can use variables to store numbers, strings,  quotes inside of strings, and boolean. Strings must always be written on the same line. 

#### Shorthand for creating variables
1. Variables are declared. Values assigned in the same statement.
1. Three variables declared on the same line. Values assigned to each. 
1. Two variables declared and assigned values on the same line. Then, one is declared and assigned a value on the next line
1. Variable holds reference to an element in the HTML

#### Rules for Naming Variables
1. Name must begin with a letter, dollar sign, or underscore. NEVER a number.
1. Name can contain letter, dollar sign, number, or underscore. Cannot contain dash, or period.
1. You cannot use **keywords** or **reserve** words. [see link](https://flaviocopes.com/javascript-reserved-words/)
1. All variables are case sensitive, and it's bad practice to create two variables that have the same name using different cases.
1. Use a name that describes the kind of information that the variable stores.
1. If your variable contains multiple words, capitalized the first letter of additional words.


[⬅ Back to README Home](README.md)