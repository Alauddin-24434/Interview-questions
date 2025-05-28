# Interview-questions

# JS Interview

## What is a Higher Order Function & Callback Function in JavaScript?
Higher Order Function: A function that takes another function as an argument or returns a function.
A Callback is a function passed into another function to be executed later.

## What is Hoisting & Closure in JavaScript?
Hoisting is JavaScript's behavior of moving variable and function declarations to the top of their scope before code execution.
A closure is a function that can remember and use variables from outside its own scope, even after the outer function has finished running.

## What is Scope in JavaScript?
Scope determines the visibility or accessibility of variables in JavaScript.
Types:

Global Scope: Accessible anywhere.

Function Scope: Accessible inside the function only.

Block Scope (let, const): Accessible only inside {} blocks.

## What is a Cookie?
 A cookie is a small piece of data stored in the browser that helps track user information like sessions, preferences, and login status. It is sent with every HTTP request to the server.
 ##  What is a Promise in JavaScript?
 A Promise is a special object in JavaScript that helps you work with asynchronous tasks (like fetching data from a server).
It has three states:

Pending:
The initial state, representing that the asynchronous operation is still in progress.
Fulfilled (Resolved):
The asynchronous operation completed successfully, and a result value is available.
Rejected:
The asynchronous operation failed, and a reason for the failure is available.

## What is an Event Loop? How does JavaScript handle asynchronous tasks?
The Event Loop continuously checks the call stack and the task queue. If the stack is empty, Take the next task from the queue and run it. 

JavaScript uses the Event Loop to handle asynchronous tasks like:

setTimeout

fetch

promises
