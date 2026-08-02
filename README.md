# JavaScript Basics, DOM Manipulation & Event Handling

## Overview
This repository contains my practice programs and notes on **JavaScript Fundamentals**, **DOM Manipulation**, **Event Handling**, and **Password Validation**. It is intended for beginners who want to understand how JavaScript makes web pages interactive.

---

# 📚 Topics Covered

## 1. JavaScript

JavaScript is a **client-side scripting language** used to make web pages interactive and dynamic.

### Types of JavaScript

### 1. Client-Side Scripting
- Runs inside the user's browser.
- Used for form validation and webpage interactions.
- Example:
  - Email validation (`@` and `.`)
  - Password validation
  - Button click events

#### Internal Scripting
JavaScript is written inside the HTML file using the `<script>` tag.

```html
<script>

</script>
```

#### External Scripting
JavaScript is written in a separate `.js` file and linked to the HTML page.

Example:

```html
<script src="script.js"></script>
```

---

### 2. Server-Side Scripting

- Executes on the server.
- Used for database operations.
- Common technologies:
  - Node.js
  - Express.js

---

# Variable Declaration

JavaScript provides different ways to declare variables.

### let

- Value can be changed.
- Block scoped.

```javascript
let a = 20;
console.log(a);

a = 30;
console.log(a);
```

### const

- Value cannot be changed after declaration.
- Mostly used for constants like URLs, PI, API Keys.

```javascript
const pi = 3.14;
console.log(pi);
```

---

# Functions

Functions are reusable blocks of code.

Syntax:

```javascript
function functionName(parameters){
    // statements
}
```

Example:

```javascript
function add(a, b){
    return a + b;
}
```

---

# Arrow Function

Arrow functions are a shorter way to write functions.

Mostly used in:
- React.js
- Modern JavaScript

Syntax:

```javascript
const add = (a, b) => {
    return a + b;
}
```

Short Form:

```javascript
const add = (a, b) => a + b;
```

---

# Objects

Objects store data as key-value pairs.

Example:

```javascript
const product = {
    prodName: "Pen",
    prodPrice: 40.59,
    prodQuantity: 5
};

console.log(product);
console.log(product.prodName);
```

---

# Arrays

Arrays store multiple values in a single variable.

Example:

```javascript
let fruits = ["Apple", "Mango", "Orange"];
```

### Common Array Methods

- push()
- pop()
- shift()
- unshift()
- slice()
- splice()
- concat()
- sort()
- reverse()
- indexOf()
- includes()

### Higher Order Functions

- forEach()
- map()
- filter()
- find()
- findIndex()
- reduce()
- some()
- every()

---

# DOM Manipulation

DOM stands for **Document Object Model**.

It allows JavaScript to access and modify HTML elements dynamically.

Common DOM Methods:

- `document.getElementById()`
- `document.querySelector()`
- `innerHTML`
- `style`
- `value`

Example:

```javascript
document.getElementById("demo").innerHTML = "Hello JavaScript";
```

---

# Naming Conventions

### Pascal Case

First letter of every word is capital.

Example:

```text
StudentDetails
EmployeeManagement
```

Used for:
- Classes
- Components
- File names (commonly)

---

### Camel Case

First word starts with lowercase.

Example:

```text
studentName
calculateTotal()
```

Used for:
- Functions
- Methods
- Variables

---

### Snake Case

Words are separated using an underscore (`_`).

Example:

```text
student_name
user_email
```

Commonly used for:
- Variables (in some languages)
- Database column names
- Folder or file names (depending on conventions)

---

# Event Listeners

Event Listeners detect user interactions.

Syntax:

```javascript
element.addEventListener("event", function(){
    // code
});
```

### Mouse Events

### Click

```javascript
button.addEventListener("click", function(){
    console.log("Button Clicked");
});
```

### Mouse Over

```javascript
button.addEventListener("mouseover", function(){
    button.style.backgroundColor = "blue";
});
```

### Mouse Out

```javascript
button.addEventListener("mouseout", function(){
    button.style.backgroundColor = "";
});
```

### Keyboard Events

#### keyup

Occurs when the user releases a key.

```javascript
textbox.addEventListener("keyup", function(){
    console.log(this.value);
});
```

#### keydown

Occurs when the user presses a key.

```javascript
textbox.addEventListener("keydown", function(){
    console.log("Key Pressed");
});
```

---

# Mini Projects Included

## 1. Uppercase Converter
- Accepts user input.
- Converts text to uppercase using `toUpperCase()`.

---

## 2. Button Events
- Click Event
- Mouse Over
- Mouse Out

---

## 3. Keyboard Events
- keyup
- keydown

---

## 4. Password Validation

Checks whether the password contains:

- Exactly 8 characters
- One uppercase letter
- One lowercase letter
- One number

Validation updates in real time using JavaScript.

---

# Technologies Used

- HTML5
- JavaScript (ES6)
- DOM Manipulation
- Event Handling

---

# Learning Outcomes

By completing these programs, I learned:

- JavaScript Basics
- Variable Declaration (`let`, `const`)
- Functions
- Arrow Functions
- Objects
- Arrays and Array Methods
- DOM Manipulation
- Event Listeners
- Mouse Events
- Keyboard Events
- Password Validation
- Form Validation
- Naming Conventions
- Client-side vs Server-side Scripting

---

# Author

**Shivapriya Bagari**

B.Tech – Computer Science & Engineering

---

⭐ Feel free to explore the programs and use them for learning JavaScript fundamentals.
