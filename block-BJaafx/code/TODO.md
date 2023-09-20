1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
let input= prompt(`input 10 numbers?`)
for( let i=input;i<=input.length;i++){
  console.log(i)
}
```


2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
} 
//println is not defined
``` 

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js
function getEvenSum(max=10){
  let sum=0
  for(let i=0;i<=max;i++){
    if(i % 2 ===0){
      sum= sum+i
    }
  }
  return sum;
}
getEvenSum(6);
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js
function getOddSum(max=10){
  let sum =0;
  for(let i =0; i<=max;i++){
    if(i % 2 !== 0){
      sum=sum+i
    }
  }
  return sum
}
getOddSum(20);
```
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output
check(1); // output
check(5); // output
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
