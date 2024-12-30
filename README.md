# Expo Navigation Error

This repository demonstrates a common navigation error in Expo React Native apps and its solution.

## Problem
The original code (`bug.js`) uses `navigation.navigate` within a component, but in some cases, `navigation` might be undefined. This leads to a `TypeError: undefined is not an object (evaluating 'navigation.navigate')` error.

## Solution
The solution (`bugSolution.js`) addresses this by using `useNavigation` hook from `@react-navigation/native`, providing access to the navigation object in the correct context, thus avoiding the undefined error.