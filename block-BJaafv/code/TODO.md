1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
In first function there is return statement and it is valid and in the second statement there is console.log which is invalid  statement.


2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
first- a+b
second- undefined
3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
36 is the output because here we had given two parameters so it does not take third parameters

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
yes beacuse function is used as an expression

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
```js

function sayHello(name){
  return `hello ${name}`
}
sayHello(ansh)
```
6. What will be the output of the function below and why?
hello john
it is because here outer variable is used by the function showMessage

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1  john

showMessage(); // Output 2   hello john

alert(userName); // Output 3    john
```

8. What is a Anonymous Function give example of three functions.
anonymous function is a function in which we use function as an expression and store function in an statement

9. Can function declaration be a Anonymous Function? Explain
yes because function is an expression

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
"add"-to add something
"track"-to track something
"reassemble"- to reassemble the word
"subtract"- to subtract something