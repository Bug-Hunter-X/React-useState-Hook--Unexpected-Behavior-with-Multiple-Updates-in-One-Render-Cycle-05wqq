# React useState Hook Bug: Multiple Updates in One Render Cycle

This repository demonstrates a subtle bug related to how React's `useState` hook handles multiple updates within a single render cycle.  The code example shows a counter component where the `setCount` function is called twice within the `handleClick` function.  Because of this, the final value of the count state might not reflect the expected behavior. 

The `bug.js` file contains the buggy code. The solution, fixing the problem by using functional updates in `useState` is shown in `bugSolution.js`.