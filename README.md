# Unexpected Behavior with useState and useEffect in Next.js

This repository demonstrates an uncommon bug in a Next.js application involving the `useState` and `useEffect` hooks. The bug causes unexpected behavior and console logs.

## Bug Description

A simple component using `useState` and `useEffect` does not update its count state correctly.  The console logs show unexpected messages related to component mounting and unmounting, indicating a potential issue with the lifecycle methods.

## Bug Reproduction

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the Next.js development server.
4. Observe the unexpected behavior in the browser and console.

## Solution

The solution involves a better understanding and implementation of `useEffect` hook's cleanup function and ensuring that the component re-renders correctly when the state changes. See `bugSolution.js` for details.