# Understanding ES6 with examples

## What is ECMAScript6?

ECMA stand for European Computer Manufacturer Association. ECMA is the association that puts out the guidelines for JavaScript in all browsers.

It means that we now have a ton of new options to work with when designing our JavaScript projects. We have new keywords available for declaring variables, like let and const. For functions, we can also use default parameters and arrow functions. ES 6 also contains classes, template strings, and new ways for dealing with arrays and objects.

# Examples

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

## ES6 Functins and Objects

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
- [Promises]()
