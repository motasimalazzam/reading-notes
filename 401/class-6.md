# Inheritance and Interfaces

## Inheritance

* It is the mechanism in java by which one class is allowed to inherit the features of an nother class.

* The `extends` keyword followed by the name of the class to inherit from.

* Multiple inheritance is not supported in java to reduce the complexity and simplify the language.

* Types of inheritance class: 
   
   1. Single Inheritance

   2. Multilevel Inheritance
   
   3. Hierarchical Inheritance

   ![Types of inheritance](https://www.w3schools.in/wp-content/uploads/2017/12/Java-Inheritance.png)

**Example**: 

```
class MountainBike extends Bicycle {

    // new fields and methods defining 
    // a mountain bike would go here

}
```

## Interface

* It is a collection of abstract methods. In other word it is **abstract class** that is used to group related methods with empty bodies.

* To use the interface in the class, we use The `implements` keyword in the class declaration.

* We can implement multiple interfaces by separate them with a comma.

## Package

* It is a folder in a file directory and it used used to group related classes and interfaces.

* Package in java can be categorized in two form, built-in package and user-defined package.