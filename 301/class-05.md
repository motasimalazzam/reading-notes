# Putting it all together

1) How would you break a mock into a component heirarchy?

draw boxes around every component (and subcomponent) in the mock and give them all names. and to know what should be its own component Use the same techniques for deciding if we should create a new function or object.

2) What is the single responsibility principle and how does it apply to components?

it is a technique used to know each component, and each component should ideally only do one thing.

3) What does it mean to build a ‘static’ version of your application?


 build an app that takes the data model and renders the UI but has no interactivity.

 4) Once you have a static application, what do you need to add?

build components that reuse other components and pass data using **props** and  don’t use **state** at all to build this static app.

5) What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props? If so, it probably isn’t state.

* Does it remain unchanged over time? If so, it probably isn’t state.

* Can you compute it based on any other state or props in your component? If so, it isn’t state.

6) How can you identify where state needs to live?

* Identify every component that renders something based on that state.

* Find a common owner component (a single component above all the components that need the state in the hierarchy).

* Either the common owner or another component higher up in the hierarchy should own the state.


* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.