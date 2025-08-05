


Introduction to React Hooks
What are React Hooks? Hooks are special functions that enable the use of state and other React features in functional components  

Why were they introduced? Previously, state management and lifecycle methods were only accessible in class components. React hooks, introduced in version 16.8,
allow functional components to work similarly to class components, making them easier to use and the preferred choice for many developers  

Benefits: They simplify code, improve readability and reusability, and enhance overall application performance  

Commonly Used Hooks:  useState, useEffect, useRef, useMemo, useCallback, useContext, useReducer, useLayoutEffect, and custom hooks 


1. useState
 
useState creates a state variable to track and update the state of a component, which in turn updates the user interface when the state changes
Syntax: It returns an array with two elements: the current state value and a function to update that value.
<pre>
const [color, setColor] = useState("red");
</pre>

Key Concepts:

The useState hook can be initialized with any data type, such as a string, boolean, or number 

Updating state with an object: To update only a specific property within a state object without losing other data, you must spread the previous state and then add the new value 

<img width="300" height="300" alt="Screenshot 2025-08-04 111321" src="https://github.com/user-attachments/assets/b56023cb-6197-4599-8da3-dbf4bb0aca09" />

Updating state based on the previous state: When performing multiple state updates in a single render, it's essential to 
use a function that receives the previous state to ensure correct calculations 

<img width="300" height="300" alt="Screenshot 2025-08-04 111321" src="https://github.com/user-attachments/assets/7f2f9893-285b-480b-9e42-c61edce6d885" />



























