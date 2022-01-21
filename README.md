# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

Map is an array function that loops through an array and maps each value in a specifed way, returns a new array with these new values. 
    One use case for map could be returning an array of values based on a specific key in an object array. For example creating a list of names from an array of person objects. 

Reduce is an array method that returns a single value based on the entire array. 
    For example say you have an array of numbers, you could use reduce to easily return the sum of all of the numbers. 

Filter is an array method that returns a new array that contains only the values from the original that pass a conditional statment. 
    For example say you have an array of names and you only want to return the names that start with 'a' this would be a perfect case for filter

2. Explain the difference between a callback and a higher order function.

A callback function is a function that you pass into a function

A higher order function is a function that accepts a function as a parameter. 

3. Explain what a closure is.

A closure happens when a function is enclosed by another function and the inner function references something in the lexical scope.  

4. Describe the four principles of the 'this' keyword.

Implicit binding: When calling a method on an object the this key word refers to the Object to the left of the dot. 

Explicit binding: When we use the functions (`call` , `apply` , `bind`) we call a function with an object where the function lives outside of the object's execution context. 

Global / window binding: when you reference `this` in the global scope. (returns the window or console object)

New binding: `this` refers to the object that is returned by the function called with the new keyword

5. Why do we need super() in an extended class?

`super` allows us to access the methods within a parent class. (Child.proto = {...Parent.proto})

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://notion.so.bloomtech.BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
