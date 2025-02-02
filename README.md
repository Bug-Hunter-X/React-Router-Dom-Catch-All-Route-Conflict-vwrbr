# React Router Dom Catch-All Route Conflict

This repository demonstrates a common issue with React Router's catch-all route (`/*`). When nested routes are used in conjunction with a catch-all route, unexpected behavior can occur, leading to incorrect rendering or routing problems.  The issue arises from the catch-all route's broad match, potentially intercepting requests intended for other, more specific routes.

The `App.js` file showcases the problem. The solution, shown in `AppSolution.js`, demonstrates how to resolve this conflict.