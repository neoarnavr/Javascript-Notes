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

```js
const cars = ["a", "b", "c"]
cars[0] = "d" // change the element
cards.push("e") // adds an element
```

- `toString()`

```js
const fruits = ["Banana", "Orange", "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits.toString();
```

- Last Array
```js
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let fruit = fruits[fruits.length - 1];
```

- Looping through the array
```js
const fruits = ["Banana", "Orange", "Apple", "Mango"]
let fLen = fruits.length;

let text = "<ul>"
for (let i=0; i< fLen; i++) {
  text += "<li>" + fruits[i] + "</li>";
}
text += "</ul>"

// OR ANOTHER WAY
let text = "<ul>";
fruits.forEach(myFunction);
text += "</ul>"

function myFunction(value) {
  text += "<li>" + value + "</li>";
}
```

- Add elements
```js
fruits.push("Lemon"); // at the end
fruits[fruits.length] = "Lemon"; // at the end

```



### Dictionaries

```js
const person = {
  firstName: "Arnav",
  lastName: "Raina",
  age: 46
};

person.length; // length
person.sort() // sorting
```















 
