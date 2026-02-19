# Chapter 03 - Conditional Statements

Conditional statements are used to make decisions in JavaScript.

---

## 1. if Statement

Syntax:

if (condition) {
   // code runs if condition is true
}

Example:

```js
let age = 20;

if (age >= 18) {
   console.log("You are eligible to vote");
}
2. if...else
let marks = 35;

if (marks >= 40) {
   console.log("Pass");
} else {
   console.log("Fail");
}
3. else if
let score = 85;

if (score >= 90) {
   console.log("Grade A");
} else if (score >= 75) {
   console.log("Grade B");
} else {
   console.log("Grade C");
}
4. switch Statement
let day = 2;

switch(day) {
   case 1:
      console.log("Monday");
      break;
   case 2:
      console.log("Tuesday");
      break;
   default:
      console.log("Invalid Day");
}

---

# 💻 day3.js me Practice Code

```js
let age = 21;

if (age >= 18) {
   console.log("Adult");
} else {
   console.log("Minor");
}

let temperature = 30;

if (temperature > 35) {
   console.log("Very Hot");
} else if (temperature > 25) {
   console.log("Warm");
} else {
   console.log("Cool");
}
