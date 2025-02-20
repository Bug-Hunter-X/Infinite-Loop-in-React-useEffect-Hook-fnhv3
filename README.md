# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The `useEffect` hook is used incorrectly, causing an infinite loop due to a missing dependency. The solution corrects this by adding the `count` to the dependency array.