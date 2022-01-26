1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let totalPercentage = function (marks, total) {
  return (marks * 100) / total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

Ans - When we store any function into a variable then it becomes function expression.
ex:-   
```js
let totalPercentage = function (marks, total) {
  return (marks * 100) / total;
}
```

4. Why is a function call an expression in JavaScript?

Ans - A function call expression is used to execute a specified function with the provided arguments.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); valid
five = add; invalid
five = five(10, 11); valid
five = function () {
  return 'Hello';
}; invalid
```

6. What is the difference between function definition and function call? Explain with an example.

Ans - The function in function declaration can be accessed only after the function definition and A function call means invoking or calling that function. 
ex:- function defination,
```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
```
ex:- function call,
```js
percentage(20, 50);
```

7. What is the similarities between function definition and function call?

Ans - A function call means invoking or calling that function. Unless a function is called there is no use of that function. ... So the difference between the function and function call is, A function is procedure to achieve a particular result while function call is using this function to achive that task.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; valid
```

9. What is higher order function explain with an example.

Ans - Higher-order functions are functions that take other functions as arguments or return functions as their results. Ex:- sort, reduce, filter, forEach, map, find

10. Explain what is callback function. Why you can pass a function inside a function?

Ans - A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.
Because functions are objects we can pass them as arguments to other functions. Functions that can accept other functions as arguments are also called higher-order functions. 
