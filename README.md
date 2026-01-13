# ES6
POC about ecma script 6

## What is Ecma Script?

ECMAScript is a scripting language specification on which JavaScript is based. 
Ecma International is in charge of standardizing ECMAScript.

## What did we have?

Before 2015, JavaScript was mainly ES3 and ES5.

It was created in 1995 for:

- form validation
- simple browser scripts
- Then it suddenly became:
- a backend language (Node.js)
- the foundation of huge web apps (Google, Facebook, Netflix)

But the language itself was not designed for:

- large systems
- modular architecture
- complex software

Objects before EC6:

```js
function Person(name) {
  this.name = name;
}

Person.prototype.sayHi = function () {
  console.log("Hi " + this.name);
};
```

This works, but it is:

- verbose
- fragile
- hard to read
- error-prone

By 2014, JavaScript had become:

- an application platform
- not just a scripting language

But its syntax still looked like it was made for small scripts.

So ES6 was designed to answer one question:

“How do we turn JavaScript into a real software-engineering language?”

Meaning:

- safer
- more predictable
- easier to scale
- easier to maintain
- better for teams

### It introduced four modern foundations.

#### #1 Variable Scope

```js
var x = 10;
if (true) {
  var x = 20;
}

console.log(x);

let z = 10;
if (true) {
  let z = 20;
}

console.log(z);
```

#### #2 Functional programming style

```js
const double = x => x * 2;
```

#### #3 Real object-oriented syntax

```js
class User {
  constructor(name) {
    this.name = name;
  }
}
```