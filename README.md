# reactbasicstwo
In this repository, I have included the topics like useRef and higher order components.useRef returns a mutable ref object whose.current property is initialized to the passed argument (initialValue). The returned object will persist for the full lifetime of the component.

Essentially, useRef is like a “box” that can hold a mutable value its.current property.
You might be familiar with refs primarily as a way to access the DOM. If you pass a ref object to React with <div ref={myRef}/>,  React will set its .current property to the corresponding DOM node whenever that node changes.

Higher order component is an advanced technique in React for reusing component logic. They are pattern that emerges from React’s compositional nature. Concretely, a higher-order component is a function that takes a component and returns a new component.
