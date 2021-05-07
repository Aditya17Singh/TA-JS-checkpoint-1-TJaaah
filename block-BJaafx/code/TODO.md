1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
function input(){
  let sum = 0;
  for(i = 1; i <=10; i++){
    let number = +prompt(`Enter number${i}`);
    sum = sum + number;
  }return sum / 10;
}input();
```
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}println is not defined.
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
```js
function getEvenSum(max){
  let sum = 0;
  for(let i = 1; i <= 10; i++){
    if (i % 2 === 0){
      sum += i;
    }
  }return sum;
}
getEvenSum(10);

```
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js
function getEvenSum(max){
  let sum = 0;
  for(let i = 1; i <= 10; i++){
    if (i % 2 != 0){
      sum += i;
    }
  }return sum;
}
getEvenSum(10);
```
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
```js
let num= 1234
let prod =1;
while(num>0){
let rem = num % 10;
 num = num - rem;
 prod = prod * rem;
 num = num /10;
}if (num < 0){}
console.log(prod);

```
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

check(10); // Bigger than 5 because 
check(1); // Smaller than 5
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // You are arya
getOutput('John'); // You are john
getOutput(); // Who are you
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // You are arya
getOutput('John'); // You are john
getOutput(); // Who are you
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
Yes function have multiple return.
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
In `for` loop you first define the variable and then check condition after that you give iteration.
In `while` loop you first apply condition and you increment the value is to increment in the body.
The different place you can use them are -
`for` loop used when you know the iteration .
`while` loop used when you donot know the iteration.