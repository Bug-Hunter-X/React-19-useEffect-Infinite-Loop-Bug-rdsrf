# React 19 useEffect Infinite Loop Bug

This repository demonstrates a common bug in React 19 related to the `useEffect` hook and provides a solution.

## Bug Description

The `useEffect` hook, when used improperly, can cause an infinite loop by triggering unnecessary re-renders. This often happens when dependencies are not correctly managed.  The provided example shows this problem and how it can be resolved.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the console. You will notice the component rendering infinitely.

## Solution

The solution involves correctly specifying the dependencies for `useEffect` to prevent unnecessary re-renders.