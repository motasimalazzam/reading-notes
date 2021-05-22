# Component Based Architecture

1) What is a component?


A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

2) What are the charactistics of a component?

* **Reusability** : Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

* **Replaceable** : Components may be freely substituted with other similar components.

* **Not context specific** : Components are designed to operate in different environments and contexts.

* **Extensible** : A component can be extended from existing components to provide new behavior.

* **Encapsulated** : A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

* **Independent** : Components are designed to have minimal dependencies on other components.

3) What are the advantages of using component based architecture?

* Component-Based architecture reduces the cost of development and maintenance.

* It is reusable which means can be used to reusable components to spread the development and maintenance cost across several applications.

* It increases the reliability of the whole system via reuse.

* It is easy to maintain and update the implementation without affecting the rest of the system.

* It modifies the complexity with the use of a component container and its services.

* If the new compatible versions are available then it is easy to replace the existing versions without any impact on the other components.

# What is Props and How to Use it in React

1) What is props short for?

**Props** : is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

2) How are props used in React?

* Firstly, define an attribute and its value(data).

* Then pass it to child component(s) by using Props.

* Finally, render the Props Data.

3) What is the flow of props?

props data is read-only, which means that data coming from the parent should not be changed by child components (one way from parent to child).