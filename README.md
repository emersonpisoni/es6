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