# Expo CLI: Unclear Metro Bundler Module Resolution Error

This repository demonstrates a difficult-to-diagnose error encountered while building an Expo project using the Expo CLI. The issue centers around a vague Metro bundler error related to module resolution, resisting standard debugging techniques.  The `bug.js` file contains a simplified representation of the project structure that exhibited the problem. The solution, found in `bugSolution.js`, illustrates how the issue was ultimately addressed.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install` or `yarn install`.
3. Attempt to run the project using `expo start`. The build process will likely fail with a cryptic Metro bundler error related to module resolution. 

## Solution

The solution often involves meticulous dependency checks and careful review of import paths. Refer to `bugSolution.js` for more details.