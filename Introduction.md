


Introduction to React Hooks
What are React Hooks? Hooks are special functions that enable the use of state and other React features in functional components  

Why were they introduced? Previously, state management and lifecycle methods were only accessible in class components. React hooks, introduced in version 16.8,
allow functional components to work similarly to class components, making them easier to use and the preferred choice for many developers  

Benefits: They simplify code, improve readability and reusability, and enhance overall application performance  

Commonly Used Hooks:  useState, useEffect, useRef, useMemo, useCallback, useContext, useReducer, useLayoutEffect, and custom hooks 


1. useState
.............
useState creates a state variable to track and update the state of a component, which in turn updates the user interface when the state changes
Syntax: It returns an array with two elements: the current state value and a function to update that value.
<pre>
const [color, setColor] = useState("red");
</pre>




























