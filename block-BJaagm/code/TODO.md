1. What does thread of execution means in JavaScript?

Ans - When we want to execute any piece of code, JavaScript engine takes this code executes line by line, that is known as thread of execution in JavaScript.

2. Where the JavaScript code gets executed?

Ans - The JavaScript code gets executed in Global Execution Context.

3. What does context means in Global Execution Context?

Ans - Context is the environment in which you are executing the code.

4. When do you create a global execution context?

Ans - When JavaScript is running your code for the first time then we create global execution context.

5. Execution context consists of what all things?

Ans - Memory & code.

6. What are the different types of execution context?

Ans - Global Execution Context and Function Execution Context.

7. When global and function execution context gets created?

Ans - Global Execution Context gets created by JavaScript engine when it is running your code for first time and Function Execution Context gets created whenever we are executing any function. 

8. Function execution gets created during function execution or while declaring a function.

Ans - Function execution gets created during function execution.

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)