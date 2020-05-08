# Understanding ES6 with examples

## What is ECMAScript6?

ECMA stand for European Computer Manufacturer Association. ECMA is the association that puts out the guidelines for JavaScript in all browsers.

It means that we now have a ton of new options to work with when designing our JavaScript projects. We have new keywords available for declaring variables, like let and const. For functions, we can also use default parameters and arrow functions. ES 6 also contains classes, template strings, and new ways for dealing with arrays and objects.

# Examples

- Open browser's console to view all results and logs of the example programs.
- For Google Chrome -> Go to Developer Tools and then select console tab.

## Transpiling ES6

- [In-browswer babel transpiling](./babel-transpiling/index.html)
- [Webpack transpiling](./webpack-transpiling)

## ES6 Syntex

- [Using `let` keyword](./using-let-keyword/index.html) - `let` is a great tool for enforcing block scoping in your JavaScript code.
- [Using `const` keyword](./using-const-keyword/index.html) - `const` is a great tool to use when we're dealing with constant values.
- [Template String](./template-string/index.html) - Template string allow us to create strings that are longer and that have a lot of dynamic content in them.
- [Spread Operators](./spread-operator/index.html) - The spread operator can turn the elements of an array into arguments of a function call, or into elements of an array literal.
- [Map](./map/index.html) -
  - Holds key value pairs
  - Any type can be used as a key
  - Why to use map ?
    - When you have to use something other than a string as key
    - To utilize key value pairs that are always the same values
    - For iterating in order
- [Sets](sets/index.html) -
  - Collections of values
  - Can be on any type
  - Each value must be unique
- [The for...of loop](for...of-loop/index.html) - For-of is a new loop in ES6 that we can use to loop over iterable objects like arrays, strings, maps, and sets.

## ES6 Functions and Objects

- [Default function parameters](deafult-function-parameters/index.html) - Default parameters can be extremely useful when you want to use a default value if another value is not provided.
- [Enhancing object literals](enhanced-object-iterals/index.html) - ES6 enhancements give us ways of shortening and simplifying object literals.
- [Arrow function](arrow-function/index.html) - Arrow functions are a great way to make your JavaScript code more readable and more compact.
- [Arrow functions and the `this` scope](arrow-functions-and-the-this-scope/index.html) - In the previous topic we reviewed how arrow functions can make our code more readable. In addition, arrow functions can help us deal with the scope of the 'this' keyword in our JavaScript code.
- [Destructuring assignment](destructuring-assignment/index.html) - Destructuring Assignment gives us an easy way to extract data from arrays and objects and assign them to variables.
- [Generators](generators/index.html) -
  - Generators are a new type of function that allow us to pause functions in the middle of execution, to be resumed later.
  - We hit pause within our function by using the new yield keyword. And this can be used multiple times within the same function.
  - So generators make it much easier to create asynchronous functions.
- [Symbols](symbols/index.html) -
  - New type of primitive in JavaScript
  - Often used as unique IDs
  - Define customised iteration behaviou
- [Iterators](iterators/index.html) -
  - Processing items in a collection
  - Using for loops, while loops, and map()
  - Custom iteration behaviour new in ES6
  - New Protocols
    - Iterable - JS objects define their own iteration behaviour
    - Iterator - a standard way to produce a sequesnce of values.

## Asynchronous Features

- [Promises](promises/index.html) -
  - Promises have emerged in the S6 to help us deal with asynchronous behavior in JavaScript.
  - When something is asynchronous it means that some sort of weighting is going on.
  - They make asynchronous code more manageable and more reusable.
- [Building promises](building-promises/index.html) - Often we use promises to load data. This example has a function called spacePeople that returns a promise. We'll call it space people because it's going to fetch some data from an API of astronauts currently in space. This is going to be a function that returns a promise.
- [Loading data with fetch](loading-data-with-fetch/index.html) -
  - Fetch function simplifyy all code from [Building promises](building-promises/index.html) section.
  - The fetch function works natively in most browsers.
  - There are also node packages that work with fetch like node fetch and isomorphic fetch.
- [Async and await](async-and-await/index.html) -
  - Async functions give us another way of dealing with asynchronous javascript.
  - Previously we only had access to `callbacks` and to `promises` but with `async` `await` we can write asynchronous code with a more synchronous looking code structure.
  - The `async` keyword makes it possible for us to write some cleaner more readable code but to also take advantage of asynchronous behavior.
  - Another nice benefit of using `async` `await` is that we have air handling and it's sometimes a little bit easier to debug than a promise.
- [Async and fetch](async-and-fetch/index.html) - Fetch is by definition is asynchronous, we make a request, and then we wait to get some data back. So we're going to do just this inside of an async function using Github request.

## ES6 Classes

- [ES6 class syntax](es6-class-syntax/index.html)
- [Class inheritance](class-inheritance/index.html) - The idea of class inheritance is pretty simple. We create one super class and then we can extend this class for reuse in different ways. Developers who have come to JavaScript from Python or Java are usually pretty excited to hear this because it's so similar to the class syntax of those languages.
- [Getters and setters](getters-and-setters/index.html) -
  - A getter is a method that gets the value of a specific property
  - A setter is a method that sets the value of a specific property
  - Getters and setters are very popular in other programming languages. They have come to JavaScript in a major way inside of objects and in classes.
