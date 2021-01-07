# Operators and Loops

## Comparison and logical operators: 150-151, 156, and 157
### Comparison operators
* == is equal to
* != is not equal to
* === strict equal to
* !== strict not equal to
* ```>``` greater than
* ```<``` less than
* ```>=``` greater than or equal to
* ```<=``` less than or equal to

``` md
(score >= pass)
([Operand] [comparison operator] [Operand])
```
Operand doesn't have to be a single variable, it can be an expression. 

### Logical operators
* && logical and. If just one of the answers is false, the expression will return false. Both need to be true for true to return. 
* || logical or. If one or both of these is true, the expression will return true.
* ! logical not. This reverses the state of an expression. If it was false it would return true.
* All evaluated left to right.

## **for** and **while** loops: 170 - 173, and 176

* For: Most common loop. If you need to run code a specific number of times, use a for loop. Conditoin is *usually* a counter which is used to tell how many times the loop should run
* While: If you do not know how many times the code should run, use while loop. Condition can be something other than a counter, and code will continue to loop for as long as the condition is true. 
* Do while: similar to while loop, but it will always run the statements inside the curly braces at least once, even if the condition evalutes to false. 
```md
for (var i = 0; i < 10; i++) {
    document.write(i);
}
```
* for = keyword
* content inside of () = condition(counter)
* document.write(i) = code to execute during loop

* Initialization: create a variable and set it to 0
* Condition: loop will run until the counter reaches a specific number
* Update: every time the loop has run the statements in the curly braces, it addes one to the counter. 


[⬅ Back to README Home](README.md)