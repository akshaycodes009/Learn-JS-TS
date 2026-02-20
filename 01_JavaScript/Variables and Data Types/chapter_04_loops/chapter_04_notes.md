# Chapter 04 - Loops in JavaScript

Loops are used to repeat code multiple times.

---

## 1. for Loop

Syntax:

for (initialization; condition; increment/decrement) {
   // code
}

Example:

```js
for (let i = 1; i <= 5; i++) {
   console.log(i);
}
2. while Loop
let i = 1;

while (i <= 5) {
   console.log(i);
   i++;
}
3. do...while Loop
let i = 1;

do {
   console.log(i);
   i++;
} while (i <= 5);
4. break and continue

break → loop stop kar deta hai
continue → current iteration skip karta hai

Example:

for (let i = 1; i <= 5; i++) {
   if (i === 3) continue;
   console.log(i);
}

---

# 💻 day4.js Practice Code

```js
// Print numbers 1 to 10
for (let i = 1; i <= 10; i++) {
   console.log(i);
}

// Print even numbers
for (let i = 1; i <= 10; i++) {
   if (i % 2 === 0) {
      console.log("Even:", i);
   }
}