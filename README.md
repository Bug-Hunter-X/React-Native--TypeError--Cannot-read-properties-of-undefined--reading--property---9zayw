# React Native: TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native: attempting to access a property of an object that is null or undefined.  This often occurs when dealing with asynchronous operations or data fetching where the data may not be available immediately when the component renders.

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a solution using optional chaining and nullish coalescing.