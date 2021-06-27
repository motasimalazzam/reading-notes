#  Java Basics

## Variables

Kinds of variabels in Java programing language:

* **Instance Variables (Non-Static Fields):** Objects store their individual states in "non-static fields", that is, fields declared without the ***static*** keyword, and they are also known as instance variables because their values are unique to each instance of a class.

* **Class Variables (Static Fields):** Are any fields declared with the static modifier, this tells the compiler that there is exactly one copy of this variable in existence, regardless of how many times the class has been instantiated.

* **Local Variables:** A method will often store its temporary state in local variables. The syntax for declaring a local variable is similar to declaring a field. here is no special keyword designating a variable as local; that determination comes entirely from the location in which the variable is declared — which is between the opening and closing braces of a method.

* **Parameters:** Parameters are always classified as "variables" not "fields"

### Naming

The rules and conventions for naming variables:

* Variable names are case-sensitive and a variable's name an unlimited-length sequence of Unicode letters and digits, beginning with a letter, the dollar sign "$", or the underscore character "_", but the best practice for naming variables is to start with a letter, not with symbols.

* Subsequent characters may be letters, digits, dollar signs, or underscore characters. When choosing a name for variables, use full words instead of cryptic abbreviations and it must not be a keyword or reserved word.

* if the variable name contains more than one words, use camel case for naming it.

### Primitive Data Types

The Java programming language is statically-typed, which means that all variables must first be declared before they can be used. A variable's data type determines the values it may contain, plus the operations that may be performed on it. A primitive type is predefined by the language and is named by a reserved keyword. The eight primitive data types are:

1) **byte:** The byte data type is an 8-bit signed two's complement integer. It has a minimum value of -128 and a maximum value of 127.

2) **short:** The short data type is a 16-bit signed two's complement integer. It has a minimum value of -32,768 and a maximum value of 32,767.

3) **int:** By default, the int data type is a 32-bit signed two's complement integer, which has a minimum value of -231 and a maximum value of 231-1.

4) **long:** The long data type is a 64-bit two's complement integer. The signed long has a minimum value of -263 and a maximum value of 263-1.

5) **float:** The float data type is a single-precision 32-bit IEEE 754 floating point. 

6) **double:** The double data type is a double-precision 64-bit IEEE 754 floating point.

7) **boolean:** The boolean data type has only two possible values: ***true*** and ***false***.

8) **char:** The char data type is a single 16-bit Unicode character.

## Operators

 Operators are special symbols that perform specific operations on one, two, or three operands, and then return a result.

 ![operators in java](https://i0.wp.com/www.flowerbrackets.com/wp-content/uploads/2017/04/operators-in-java.jpg?resize=591%2C382&ssl=1)