# Variables

A JavaScript application needs to work with information like 
1. An online shop – the information might include goods being sold and a shopping cart.
2. A chat application – the information might include users, messages, and much more.

Variables are used to store this information.

## Declaring Variables
To create a variable in JavaScript, use the `let` keyword.
```js
let message;
```
Now, we can put some data into it by using the assignment operator `=`.
```js
let message;

message = 'Hello'; // store the string 'Hello' in the variable named message
```
We can access it using the variable name.
```js
let message;
message = 'Hello!';

console.log(message); // Hello!
```
To be concise, we can combine the variable declaration and assignment into a single line.

```js
let message = 'Hello!'; // define the variable and assign the value

console.log(message); // Hello!
```
We can also declare multiple variables in one line, but for readability, it is recommended to declare them separately:
```js
let user = 'John', age = 25, message = 'Hello';
```
Better style
```js
let user = 'John';
let age = 25;
let message = 'Hello';
```





