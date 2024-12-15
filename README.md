# Next.js 15 App Router - Unexpected Error with `use` keyword

This repository demonstrates a bug encountered in Next.js 15's App Router when utilizing the `use` keyword within a component.  The issue manifests as an unexpected error during rendering.  The solution provides a workaround to resolve this issue.

## Bug

The original `pages/index.js` demonstrates the problem. Attempting to render this simple component results in an error because of the unexpected use of the `use` keyword which is not handled properly by the app router.

## Solution

The `pages/index.js` file in the `solution` directory provides a workaround. This version avoids the problematic use of the `use` keyword, ensuring the component renders correctly within the Next.js 15 App Router environment.