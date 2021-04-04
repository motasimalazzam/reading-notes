# What is an object

It is a set of variables and functions that perform a specific job. The variable is called a property if it is part of the object and function is called a method if it is also part of the object. The property and methods have names and values, and the name is called a key.

Property value can be string, number, Boolean, array or another object. And the value of method is always function.

## Creating an object

There are several ways to create objects, one of them is ***Literal notation***.

We create a variable bearing the name of the object and between {} we place the keys with their value arranged vertically and separate them using a comma and create a method in a similar way to creating a function.

# The Document Object Model (DOM)

It is an object, which is part of the browser. When you open a site through the browser, the browser creates a DOM, and its task is to control how the elements are displayed on the site and how they are dealt with.

### The document node:

When you open the site, the browser creates Dom tree, which is a map-like layout that contains all the contents of the html file.

### The element nodes:

It is the HTML elements that make up the Dom tree like `<p>` which contain text.

### Attribute nodes

They are the properties of the elements, and the property of each element appears on the Dom tree.

### Text nodes:

The text that accompanies the elements, and each element contains text that appears on Dom tree.

![Dom tree example](http://www.w3big.com/images/pic_htmltree.gif)

## Working with the Dom tree

To access and update the Dom tree, we have two steps:

1) Locate the node that represent the element you want to work with.

2) Use its text content, attributes and child elements.

### Step one: we have 3 methods to access element:

1) Select an individual element node:

***getElementById()*** and ***querySelector()*** are common ways to select an individual element.

2) Select multiple element (NODELISTS):

***getElementByClassName()***, ***TagName()***, and ***querySelectorAll()*** are common ways to select multiple elements.

3) Traversing between element nodes:

We can move from one element node to related element node by ***parentNode***, ***previousSibiling/nextSibiling*** and ***firstChild/lastChild***.

### Step two: work with elements:

We can work with elements by 3 ways:

1) Access/Update text nodes:

To access or update contents of text node we use ***nodeValue*** property.

2) Work with HTML content:

***innerHTML*** property allows access to child element and text content.

3) Access/Update attribute values:

We can work with attributes by ***className/id***.
