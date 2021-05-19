# React and Forms

## React Docs - Forms

1) What is a ‘Controlled Component’?

 A JavaScript function that handles the submission of the form and has access to the data that the user entered into the form.

 2) Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

 In React, mutable state is typically kept in the state property of components, and only updated with `setState()` .

 ## The Conditional (Ternary) Operator Explained

1) Why would we use a ternary operator?

It is similar to the if-else statement, and the goal of using it is to write the code and condition in one line. The syntax ` condition ? value if true : value if false `

2)  Rewrite the following statement using a ternary statement:

```
if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
  ```

 (x===y)? console.log(true) : console.log(false)