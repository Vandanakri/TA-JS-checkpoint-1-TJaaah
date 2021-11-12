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

Ans- The first function will give you return value a + b and the second function will give you console.log (a + b) then it will give you  undefined.


2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

Ans- The first function will give you return value a + b and the second function will give you console.log (a + b) then it will give you  undefined.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

Ans- when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)` then the output will be 36 because there is only two parameter then the value put only two parameter.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?


Ans- yes, because function is an expression and we could be store a function in a variable.


5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

function sayHello (name) {
return `hello ${name}`
}

sayHello("Arya")


6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage(); 
Hello, John
```
because we declear the userName after the function.


7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 // John

showMessage(); // Output 2 // Hello, John

alert(userName); // Output 3 // John
```

8. What is a Anonymous Function give example of three functions.

we store a function in side a variable you don't have to give a name to the function.
example; let addnum = function (numA,numB) {
  return numA + numB;
};
let addnum = function (numA,numB) {
  return numA - numB;
};
let addnum = function (numA,numB) {
  return numA * numB;
};

9. Can function declaration be a Anonymous Function? Explain

no, because In Anonymous Function we put variable and In function declaration we dont put variable.


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
1. function sum(a, b) {
  return a + b;
}

2. let addnum = function (numA,numB) {
  return numA * numB;
};

3. function sum(a, b) {
  return a + b;
}

4. function add(num1,num2) {
  if(num1 > num2) {
    return true
  } else if (num1 < num2) {
    return false
  }
}

