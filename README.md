# Javascript Notes

### Where to put it?

1. In the `<head>` or the `<body>` enclosed in `<script>`.
2. Through external script: `<script src="myScript.js"></script>`

### Javascript Output

1. Write into an HTML element:
```js
document.getElementById("demo").innerHTML = "<h2>Hello</h2>";

// OR

document.getElementById("demo").innerText = "Hello";
```


2. Java Statemets

### Keywords

- `var`: for declaring a variable (global scope)
  - can redeclare multiple times
```js
var carName = "Volvo";
var carName; // redeclared but the value remains the same.
```

- `let`: for declaring a block variable (block scope)
  - can not redeclare under the same block
- `const`: declares a block constant


```js
let _x = 5; // start using let
let $ = 3; // valid
let $myMoney = 5; // valid
var _y = 2; // Avoid using var
```

### Arrays

- zero-indexed
- dynamic size
- can store diff data types

#### `const` arrays

```js
const cars = ["a", "b", "c"]
cars[0] = "d" // change the element
cards.push("e") // adds an element
```








 
