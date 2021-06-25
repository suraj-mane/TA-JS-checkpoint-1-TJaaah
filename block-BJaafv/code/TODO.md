1. What is the difference between the two `sum` function given below?

```js
// first


// second
function sum(a, b) {
  console.log(a + b);
}
```
Answer- In the first function the return sum when we call. but in second function out will undefined because of return statement.  

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
Answer- we store the value in variable. the first value is retrun by function. but in secound the values are undefined.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
Answer- The function is not accepet the thired value. becuase of thay are create as two parameter.
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
Answer- yes. because they hava return statement.
5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
Answer- function sayHello(name){
          return `Hello ${name}`;
        }
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
Answer- `Hello Jhon`;
7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); - `Jhon`;

showMessage(); - "Hello, Jhon"; 

alert(userName); `Jhon`;
```

8. What is a Anonymous Function give example of three functions.
Answer- The anonymous function is that have no name. 
let sum = function (numA) => {
  return numA;
}
let add = function (numA, numB) => {
  return numA + numB;
}
const x = function (a, b) {return a * b};
9. Can function declaration be a Anonymous Function? Explain
Answer - No becuase the function declartion is used the name but in anonymous function has no name.
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.
Answer- 
1) Function addTwoNumber(numA,numB) {
  return numA + numB;
}
2) Function userName(name){
  return name;
}
3) Function carName(cars){
  return cars;
}
4) Function bikeSpeed(speed){
  return speed;
} 
5) Function songs(singer){
  return singer;
}
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
