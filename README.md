# Null Value Handling in JavaScript Function

This repository demonstrates an uncommon error related to handling null values in JavaScript functions. The error occurs when the function does not explicitly check for null values, leading to unexpected behavior or crashes.

## Bug Description
The `foo` function in `bug.js` does not correctly handle null values passed as arguments. This can result in errors or unexpected behavior, depending on how the null values are used within the function. The solution demonstrates how to handle this correctly.

## Bug Solution
The solution (`bugSolution.js`) adds explicit null checks to the `foo` function. This ensures that the function handles null values gracefully, preventing errors and ensuring predictable behavior.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js`.
3. Compare the implementation of the `foo` function.
4. Run the functions with various inputs, including null values, to observe the difference in behavior.
