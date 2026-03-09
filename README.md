1. What is the difference between var, let, and const?

var: var can declare variables with function or global scope and allows re-declaration and updates within the same scope.
let: let can declare variables with block scope, allowing updates but not re-declaration within the same block.
const: const can declare block-scoped variables that cannot be reassigned later after their intial assignment.

2. What is the spread operator (...)?

The spread operator (...) in JavaScript provides a simple and expressive way to expand elements from arrays, strings or objects. 
It helps make code cleaner by reducing the need for manual copying or looping. 


3. What is the difference between map(), filter(), and forEach()?

map(): map() function receives a function as a parameter and will apply the code on each element and returns an entirely new array. It will not change the original array.

filter(): The filter() method receives function as a parameter. It runs the function for each element in the array. It will return the new array which satifies the condition applied. It will not change the original array.

forEach(): The forEach() function receives a function as an argument and it applies the same code to every element. It will not return anything, it just applies the condition to every element. It will not chnage the original array. The return value of forEach() method is undefined. The forEach() method does not wait until promises are resolved.  

4. What is an arrow function?

Arrow functions in JavaScript are a concise way to write functions using the => syntax, automatically binding this from the surrounding context.
Syntax:
const functionName = (parameters) => {
// function body
return result; 
};

6. What are template literals?

Template literals are literals delimited with backtick(`)  characters, allowing for multi-line strings, string interpolation(to create strings by doing substitution of placeholders) with embedded expressions and special constructs called tagged templates.
