1. What are the three states of a `Promise`?
2. How does the `async` keyword affect a function's return value?
3. Explain the purpose of the `await` keyword.
4. What is a callback function and how is it used in asynchronous operations?
5. Describe the role of the event loop in JavaScript.
6. Write a function called `delayedGreeting` that takes a name as an argument and logs a greeting message to the console after a 2-second delay using `setTimeout`. Use a callback function to achieve this.


1. 	
    - Pending
	- Fulfilled (Resolved)
	- Rejected

2. 
 - The async keyword makes a function return a Promise, regardless of what the function returns. If a value is returned, it’s wrapped in a   resolved Promise.
    - async function example() {
    -   return "Hello"; // Actually returns Promise.resolve("Hello")
    - }

3. 
 - The await keyword is used inside an async function to pause the execution until the Promise is resolved or rejected.

    - async function fetchData() {
    - const data = await fetch('https://api.example.com/data');
    - const json = await data.json();
    - console.log(json);
    - } 

4. 
 - A callback function is a function passed as an argument to another function and is executed after an operation is completed.
  - In asynchronous operations, callbacks are used to handle results after a delay.

    - function getData(callback) {
    -  setTimeout(() => {
    -    callback("Data received");
    -  }, 1000);
    - }

5. 
 - The event loop is a mechanism that handles asynchronous operations. It checks the call stack and task queue, and moves tasks from the queue to the stack when the stack is empty, enabling non-blocking behavior.

6. 
 -    function delayedGreeting(name, callback) {
        setTimeout(() => {
         callback(`Hello, ${name}!`);
       }, 2000);
      }

 -   // Example usage:
 -     delayedGreeting("Kanila", function(message) {
 -      console.log(message);
 -     });