# React Native useState Hook Not Updating State
This repository demonstrates a common error when using the useState hook in React Native: directly modifying the state object instead of using the setter function. This leads to the component not re-rendering and unexpected behavior.

## Bug
The `bug.js` file shows incorrect usage of the useState hook where the state object is modified directly.  This does not trigger a re-render.

## Solution
The `bugSolution.js` file shows the correct usage of the useState hook using the setter function provided by the useState hook to update the state. This correctly triggers re-renders.

## How to reproduce the bug
1. Clone this repository.
2. Run `npx react-native run-android` or `npx react-native run-ios`.
3. Observe the unexpected behavior in the app. 