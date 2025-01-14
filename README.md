# React setInterval Memory Leak

This example demonstrates a common mistake when using the `setInterval` function within a React component.  The `setInterval` function is called repeatedly and will continue to run even when the component unmounts, leading to memory leaks and potential performance issues. 

The solution demonstrates the proper usage of `setInterval` within a React component by using the `useEffect` hook with a cleanup function to stop the interval when the component unmounts.