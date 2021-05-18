# Passing Functions as Props

## React Docs - lists and keys

1) What does .map() return?

The map() is a function, which creates a new array and returns every element in order.

2) f I want to loop through an array and display each value in JSX, how do I do that in React?

By using curly braces, and by using map(), and after that we use ReactDOM.render() to display each value.

3) Each list item needs a unique ____

Each list item needs a unique **key**.

4) What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed.

## The Spread Operator

1) What is the spread operator?

InJavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments. And it used for for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

2) List 4 things that the spread operator can do.

* Copying an array

* Concatenating or combining arrays

* Using Math functions

* Using an array as arguments

3) Give an example of using the spread operator to combine two arrays.

```
let firstName={firstName:"My name is Motasim"};
let lastName={lastName:"Alazzam"};
let fullName={...firstName, ...lastName};
console.log(fullName)

 ```
