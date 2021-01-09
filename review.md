# Final 102 Review Notes

### Loops
**For Loop:** (let i=0) is where the *counter/initializer* starts. Second part (i <10) is the *condition*, Third part (i++) is the *iterator*. Inside of {} is the code you will run. 
```js
for (let i = 0; i < 10; i++){
    console.log(i);
}
```

```js
for (let i = 0; i <= 10; i++){
    if(i < 5){
        console.log('We are less than 5');
    } else if (i >9){
        break;
    }
}
```
### Function
*'ThisIsAFunction'* is how you can send parameters inside of the function i.e. *'name'*. Then, you can use that information within the function. Name will be replaced with whatever the input is for the rest of the function. In this example, Roger & Lydia will console log. 
```js
function thisIsAFunction(name){
    console.log(name);
}

thisIsAFunction('Lydia')
thisIsAFunction('Roger')
```
In this example, multiple things will console log. thisIsAFunction is 'doing the declaration under the hood'. This is one example where you do not have to define the variable. 
```js
function thisIsAFunction(name, age, state){
    console.log(name, age, state);
}

thisIsAFunction('Lydia', 1, 'wa')
thisIsAFunction('Roger', 1, 'tx')
```
In this example, something will return. In order to return something out of the function, you have to use the return command. 
```js
function thisIsAFunction(name, age, state){
    console.log(name, age, state);
    return name;
}

thisIsAFunction('Lydia', 1, 'wa')
thisIsAFunction('Roger', 1, 'tx')
```
```js
let getName = function (){
    console.log('Hello');
}

getName()
```
Good examples on page 97 of the book

* **Logical Operators**
    * And operator (&&): both answers must be true for the answer to pass as true
    * Or operator (||): Only one answer must be true for the answer to pass as true
```js
answer = 3:

if (answer > 5 && answer < 10>){
    pass
}
```
In this equation, the output would be 'false' because one answer is false
```js
answer = 3:

if (answer > 5 || answer < 10>){
    pass
}
```
In this equation, the output would be 'true' because one answer is true
* **Equal signs**
    * = is an assignment operator
    * == this is a comparison operator
    * === this is strictly comparative operator 
    * ex. '93' == 93 is a true statement, but '93' === 93 is a false statement. Double equals only compares a value. Strictly equals compares not only the value, but also the data type. In the '93' === 93, '93' is a string whereas 93 is a number, so the data type does not match. 

### HTML
* Body: Content on your webpage
* !DOCTYPE: starts your HTML
* Head & Body: Required parts of any HTML file
* Anchor tag 'a': allows you to add external links to your website (a href)
* Inline elements - takes up the space it needs: strong, img, em, script, a, span, 
* Block elements - takes up as much space as it can: section, nav, main, li, p 

### CSS
* Tag HTML: element, class, id
    * class: can be used multiple places
    * id: can be used one time per page

* Note: in your console log you can input typeof(put item in here), and your console log will let you know what it is. 
[⬅ Back to README Home](README.md)