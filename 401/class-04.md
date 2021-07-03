# OOP

## Object and Class ones

### An Object

Everything around us is an object, and every object is made up of attributes and actions. Attributes are Properties of an object such as color, and actions are what the object does, such as moving or standing. This also applies to objects in programming, and properties are in the form of variables with specific values such as color = blue, and verbs in the form of functions.

### A Class

There are many individual objects all of the same kind. A class is the blueprint from which individual objects are created.

#### Declaring Class:

The syntax for Declaring Class:
 
```
 public class Example {

     // write the variables and methods
 }
```

 We can `extends` the class by add another class like the code below:

 ```
 public class Example extends SuperExample {

     // write the variables and methods
 }
```
and also `implements` Interface to the class:

```
 public class Example implements InterfaceExample {

     // write the variables and methods
 }
```
**Important note**: we can implements more than one interFace but we can not extends more than one class.

### Declaring Member Variables

**There are several kinds of variables**

* Member variables in a class—these are called fields.

* Variables in a method or block of code—these are called local variables.

* Variables in method declarations—these are called parameters.

**Access Modifiers**

* public modifier—the field is accessible from all classes.

* private modifier—the field is accessible only within its own class.

### Providing Constructors for Your Classes

Constructor declarations look like method declarations—except that they use the name of the class and have no return type. 

## Binary, Decimal and Hexadecimal Numbers

### Decimals numbers

* Every digit in a decimal number has a "position", and the decimal point helps us to know which position is which.

* It is called **Base 10** because it is based on 10 symbols:(0, 1, 2, 3, 4, 5, 6, 7, 8, 9).

### Binary Numbers

* It is called **Base 2** insted of **Base 10**. 

* It start counting at 0 to 1 and then start again from 0.

### Hexadecimal Numbers

* Single Hexadecimal digit can show 16 different values instead of the normal 10.

* The 16 values are starting and it used letters ("A',"B","C","D","E","F") instead of values from 10 to 15.