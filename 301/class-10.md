# Understanding the JavaScript Call Stack

1) What is a ‘call’?

The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

2) How many ‘calls’ can happen at once?

It is done one at a time from top to bottom. It means the call stack is synchronous.

3) What does LIFO mean?

**Last In First Out** it means the last function that gets pushed into the stack is the first to be pop out, when the function returns.

4) What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

# JavaScript error messages

1) What is a ‘refrence error’?

It is means you try to use a variable that is not yet declared you get this type of errors.

2) What is a ‘syntax error’?

It means you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3) What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

4) What is a ‘tyep error’?

This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5) What is a breakpoint?

Select a line in the cod and check if it works or no, if it works that means the error is before it.

6) What does the word ‘debugger’ do in your code?

The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.
