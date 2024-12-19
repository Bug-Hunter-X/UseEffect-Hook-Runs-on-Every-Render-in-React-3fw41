# React useEffect Hook Runs on Every Render

This repository demonstrates a common error in React applications where the `useEffect` hook runs on every render instead of only when its dependencies change. This can lead to performance issues and unexpected behavior.

The `bug.js` file contains the faulty code, while `bugSolution.js` provides the corrected version.  The issue stems from an improperly configured dependency array in the `useEffect` hook.