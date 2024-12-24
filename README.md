# Accessing State Before it's Set in React Native

This repository demonstrates a common error in React Native: attempting to access a state variable before it's been fully initialized.  The `bug.js` file showcases the problem, while `bugSolution.js` provides a corrected implementation.

## Problem

Accessing state too early can lead to unexpected behavior or crashes. This often occurs during component mounting or when using asynchronous operations that update state.