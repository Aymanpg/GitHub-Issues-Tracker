1. What is the difference between var, let, and const? 
   - `var` is function-scoped and hoisted (can be used before declaration). It allows redeclaration and reassignment.  
   - `let` is block-scoped, not hoisted, allows reassignment but not redeclaration in the same scope.  
   - `const` is block-scoped, not hoisted, does not allow reassignment or redeclaration (but objects/arrays can be mutated).

2. What is the spread operator (...)?  
   The spread operator (`...`) expands an iterable (like an array or object) into individual elements. It's used for copying arrays/objects, merging, or passing arguments to functions. Example: `const arr = [...[1, 2], 3]; // [1, 2, 3]`.

3. What is the difference between map(), filter(), and forEach()? 
   - `map()` creates a new array by applying a function to each element (transforms data).  
   - `filter()` creates a new array with elements that pass a test (filters data).  
   - `forEach()` executes a function on each element but returns nothing (used for side effects like logging).

4. What is an arrow function?
   An arrow function is a concise way to write functions: `() => {}`. It doesn't have its own `this` (uses lexical scope), no `arguments` object, and can't be used as constructors.

5. What are template literals?
   Template literals are string literals using backticks (`` ` ``) that allow embedded expressions `${expr}` and multi-line strings. Example: `` `Hello ${name}!` ``.
