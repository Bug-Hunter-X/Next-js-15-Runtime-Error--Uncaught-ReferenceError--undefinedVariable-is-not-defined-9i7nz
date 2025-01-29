# Next.js 15 Runtime Error: Uncaught ReferenceError

This repository demonstrates a common runtime error in Next.js 15 applications where accessing an undefined variable within a component throws an error that is not caught during the build process.

## Bug Description

The `pages/about.js` component attempts to render an undefined variable (`undefinedVariable`). This leads to a runtime `ReferenceError` in the browser.

## Solution

The solution involves either defining the variable properly or using optional chaining and nullish coalescing to handle potential undefined values.

## Reproduction Steps

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to `/about`.
5. Observe the runtime error in your browser's console.