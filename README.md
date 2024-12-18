##### Writing a Function in **JavaScript**

In **JavaScript**, **functions** are blocks of reusable code. They allow you to bundle functionality, make it more readable, and _avoid repetition_. Here's a brief tutorial on writing an arrow function in _JavaScript_.

## 1. Basic syntax

**const** _functionName_ = (params) => {
// code to be executed
}

**const**: const should be used whenever a function expression is assigned to a **variable**.
**The function name**: The name you choose for the **function**.
**Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, _the () is still required_.
**The arrow syntax**: Indicates that this will be a **function**.
**The body**: The statements that make up the function itself. Surrounded by **curly braces**.

# Example:

const greet = (name) => {
console.log("Hello, " + name + "!");
}

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include `fetchData( )`, `calculateArea( )`, or `printReport( )`.

## 2. Calling a function

To execute the function, you call or invoke it by using its name followed by **parentheses**.

**Example**:

`greet('Alice'); // Outputs: Hello, Alice!`

## 3. Return values

Functions can process data input and output a value using the return keyword.

**Example**:

const addNums = (numA, numB) => {
return numA + numB
}

const total = addNums(2, 4);

console.log(total) // **Expected value: 6**

**For more information on functions and how they are used in JS, check out the MDN docs.**
[MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
_Writing a Function in JavaScript_

![Image of a computer](https://media.istockphoto.com/id/1979289147/photo/data-analysis-science-and-big-data-with-ai-technology-analyst-or-scientist-uses-a-computer.webp?s=1024x1024&w=is&k=20&c=WqGfiIeod3kNA5XFFRRa0w5uhoL3c2PfxoWYNXfvl68=)
