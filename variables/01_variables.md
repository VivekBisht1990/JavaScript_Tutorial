# Variables

A JavaScript application handles information such as products and a shopping cart in an online shop, or users and messages in a chat app. Variables store this data.

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
## Understanding Variables with a Real-Life Analogy
Think of a variable as a box for storing data, with a unique name as a label.

For instance, the variable message can be imagined as a box labelled `"message"` with the value `"Hello!"` in it:

<img width="175" alt="image" src="https://github.com/user-attachments/assets/b6caa3b3-2cf8-407b-aee1-af2faee6560d">

We can put any value in the box.

We can also change it as many times as we want:

```js
let message;

message = 'Hello!';

message = 'World!'; // value changed

alert(message);
```
When the value is changed, the old data is removed from the variable:

<img width="409" alt="image" src="https://github.com/user-attachments/assets/63e0ec7d-36d8-43b0-8084-93ff1b018972">





