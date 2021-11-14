1. Using loops take 10 inputs from user and find the average of all the numbers.

```js

let sum = 0;
for(let v = 0; v < 10; v++){
  let num = +prompt("Enter the number");
  sum = sum + num;
}
let average = sum / 10
console.log(average);

```

2. What will be the output of the code below


```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}

```       

Ans= error because println is not defined

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.


```js
function getEvenSum (max){
let sum = 0;
for(let v = 0; v <= max; v = v+2){
sum = sum + v;
}
console.log(sum);
}
j
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.


```js
function getOddSum (max){
let sum = 0;
for(let v = 1; v <= max; v = v+2){
sum = sum + v;
}
console.log(sum);
}

```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.


```js

function getProductOfDigits(num) {
let product = 1;
while(num > 0) {
  let reminder = num % 10
  num = num - reminder
  product = product * reminder
  num = num / 10
}
return product
}

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


check(10); // Bigger than 5
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

getOutput('Arya'); // 'You are arya'  when we apply the condition "===" then the output will be 'You are arya' 
getOutput('John'); // 'You are john' when we apply the condition "===" then the output will be 'You are john'

getOutput(); // 'Who are you' there is a not any argument then the output will be 'Who are you'.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // the output will be both 'You are arya' and 'Who are you'because when we function call then the value return both.
getOutput('John'); // the output will be both 'You are arya' and 'Who are you'because when we function call then the value return both.
getOutput(); // the output will be 'Who are you' because that is empty argument.
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

```js

we can't take more then one return statement.
function sum(num1,num2){
  if(num1 > num2){
    return true;
    return "True";
  }

}

```

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

```js

'for' have 3 things in one line, and while have 3 things in 3 line.

```

