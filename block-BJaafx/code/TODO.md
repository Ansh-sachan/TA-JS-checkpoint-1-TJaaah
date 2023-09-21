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
```js
function getProductOfDigits(num){
  let product =1;
  while(num != 0){
    product = product*(num % 10);
    num = Maths.floor(num / 10);
  }
  return product
}
getProductOfDigits(234);
```



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
 
check(10); // output  greater than 5
check(1); // output  smaller than 5
check(5); // output  5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output  you are arya
getOutput('John'); // what will be the output  you are john
getOutput(); // what will be the output  who are you
```

8. What will be the output of the following code given below? Explain the reason?
console,log returns but in the function and return statement returns the value. 
```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output who are you
getOutput('John'); // what will be the output  who are you
getOutput(); // what will be the output  who are you
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

yes a function had multiple return statement but it will return value when the function is called.


10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

For loop is used when the number of iteration is known and while is used when number of iteration is unknown and the statement will run until the condition is proved false . 
