# React Router v6 Catch-all Route '*' Issue

This repository demonstrates a problem with the catch-all route ('*') in React Router v6.  The catch-all route, intended to handle any unmatched routes, is being unexpectedly ignored.

## Problem

The provided `App.js` demonstrates a simple React Router setup. Despite the presence of a catch-all route, navigation to non-existent paths does not trigger the `NotFound` component.  Instead, it behaves unexpectedly. 

## Solution

The solution, found in `AppSolution.js`, addresses this issue. The solution involves careful placement of routes and potentially addressing conflicting route definitions.

## How to reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Navigate to a non-existent path (e.g., `/invalid`). Observe that the `NotFound` component does not render as expected.