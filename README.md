# React Router v6 useParams Hook: Unexpected Behavior Outside Direct Child Routes

This repository demonstrates a common issue encountered when using the `useParams` hook in React Router v6.  The `useParams` hook, when used outside a component that is a direct child of a route element defined using the `Route` component, may not update correctly, leading to stale or undefined parameter values. This can cause unexpected behavior in your application.  The solution involves ensuring that the component using `useParams` is a direct child of the corresponding route.

## Steps to Reproduce:

1. Clone the repository.
2. Navigate to the `IncorrectParamsUsage.jsx` file to see the bug in action.
3. Navigate to the `CorrectParamsUsage.jsx` file to see the corrected implementation.