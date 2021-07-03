# Maps, primitives, File I/O

## Primitives vs. Objects

In jave there are two-fold type system, the first one is **primitives** type such as *int* *boolean* and the second one is **reference** such as *Integer* and *Boolean*. Every primitive type corresponds to a reference type.

**Autoboxing:** is converting a primitive type to a reference type. The opposite process is called **unboxing**.

### Pros and Cons

To choose between *primitives* type and *reference* type we should know how much available memory we have and what default values we should handle. 

* **Single Item Memory Footprint**

The single variable of the reference type needs more space than the primitive type. For example, Boolean type occupies as much space as 128 primitive ones.

* **Memory Footprint for Arrays**

Arrays of the primitive types long and double need more memory than reference types Long and Double.

* **Preformace**

The reference type required more time to perform the operation than primitive type.

![compare the performance of this operation ](https://www.baeldung.com/wp-content/uploads/2018/08/plot-benchmark-primitive-wrapper-3.gif)

* **Default Values**

Every primitive type of variables has a default value depends on its type. The default value of numeric types is **0** , **false** for the boolean type and **\u0000** for the char type. For the reference type,  the default value is **null**.

## Exceptions

### What Is an Exception?

The term exception is shorthand for the phrase **exceptional event**, which is an event, that occurs during the execution of a program, that disrupts the normal flow of the program's instructions.

**Exception object:** is an object created by a method that contains error, and this object contains information about the error.

**Throwing an exception:** is Creating an exception object and handing it to the runtime system.

**Call stack:** is the ordered list of methods that that had been called to get to the method where the error occurred.

![Call stack](https://docs.oracle.com/javase/tutorial/figures/essential/exceptions-callstack.gif)

### The Catch or Specify Requirement

There are three kinds of Exceptions:

1. **Checked exception:** The application checks for written exceptions, which are errors that the application solves.

2. **The error:** This kind of exception is for external exceptional conditions of the application.

3. **Runtime exception:** This kind of exception is for internal  exceptional conditions of the application. These usually indicate programming bugs, such as logic errors or improper use of an API.

## Scanning

The **Scanner** class is used to get user input and we can create objects und use the available methods found in the Scanner.By default, a scanner uses white space to separate tokens.


In the scanner objects, we need to close the scanner to tell the program the user is finished entering the value. Scanner also supports tokens for all of the Java language's primitive types (except for char).
