# JavaScript

When writing code on JavaScript for the first time, it is certain that the code will contain errors, and there are 3 ways to help us discover errors:

1) The console and Dev tools: Tools built into the browser that help us hunt for errors.

2) Common problems: Common sources of errors, and how to solve them.

3) Handling errors: How code can deal with potential errors gracefully.

## Order of execution:

JavaScript executes the program line by line, and there are commands that are not executed until the error is fixed.

## Execution contexts:

Every code line lives in one of three execution contexts:

1) Global context: Any code in the script is global context, but the text in function is not global context.

2) Function context: The code lives in the function.

3) Eval context.

**Variable scope:** In JavaScript we have:

1) Global scope: Any variable is declared outside a function, it can be used any where.

2) Function-level scope: Any variable is declared in function: it can ***only*** only be used in the function.

## Error objects

 Error objects can help us find where our mistakes are and browsers have tools to help us read them.

 Error object contain 4 properties:

 1) name: Type of execution.

 2) message: Description.

 3) fileNumber: Name of the Javasript file.

 4) lineNumber: Line number of error.

These properties show on the console on the browser.

### There are seven types of built-in error objects in JavaScript:

1) Error

2) Syntax Error

3) Ref erenceError

4) TypeError

5) Range Error

6) URI Error

7) Eval Error