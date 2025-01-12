# React useEffect Infinite Loop

This repository demonstrates a common error in React's `useEffect` hook: creating an infinite loop by incorrectly managing dependencies.

The `bug.js` file contains the buggy code. The `useEffect` hook attempts to update the `count` state in every render without specifying any dependencies, leading to an infinite loop.  The `bugSolution.js` shows the correction.