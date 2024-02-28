# Arrow Functions

### Learning about arrow functions
- Arrow functions are function expressions, which are anonymous functions saved to a variable.
- Arrow functions allow us to take in parameters.

``` javascript
// Traditional Function
function add(a, b) {
    return a + b;
}

// Arrow Function
const addArrow = (a, b) => a + b;

// Usage
console.log(add(3, 5));      // Output: 8
console.log(addArrow(3, 5)); // Output: 8

```

### Description:
- No need for the function keyword.
- If there is only one parameter, you can omit the parentheses (e.g., a => a * 2).
- If there are no parameters, use an empty set of parentheses (() => alert('Hello!')).
- If the function body consists of a single expression, you can omit the curly braces ({}) and the return keyword.
- Arrow functions are especially useful for short and concise functions, making your code more readable and expressive.

### Exercise
- Open the index.js file and work on the exercises listed. You can commit and push your code when complete.

