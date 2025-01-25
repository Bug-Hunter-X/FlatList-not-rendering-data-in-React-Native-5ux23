# React Native FlatList Rendering Issue

This repository demonstrates a common issue in React Native where a FlatList component fails to render data even when the state containing the data is correctly updated. The bug is present in `bug.js` and the solution is provided in `bugSolution.js`.

## Problem

The initial `bug.js` implementation uses a `useEffect` hook to populate the `items` state with sample data. Despite this, the FlatList remains empty. This happens because of how React's reconciliation process works.