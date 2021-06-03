# State and Props

1) Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Based off the diagram, the ‘render’ happens before the ‘componentDidMount’.

2) What is the very first thing to happen in the lifecycle of React?

The very first thing to happen in the lifecycle of React is mounting, the componentWillMount() method is the first called in this phase.

3) Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

These things will happen in this order: 1- constructor() 2- render() 3- componentDidMount() 4- React Updates 5- componentWillUnmount()

4) What does componentDidMount do?

componentDidMount is executed after the first render only on the client side, this is where AJAX requests and DOM or state updates should occur.

5) What types of things can you pass in the props?

Types of things can you pass in the props can be any data type, from strings to functions, objects, etc.

6) What is the big difference between props and state?

The main differance between props and state; in props you passed into a component and is handeled inside that component, but state is handeld outside that component and must be updated outside.

7) When do we re-render our application?

We re-render our application when we change the state inside the application.

8) What are some examples of things that we could store in state?

input elements, iside forms(checkbox and others).