# HTML

In HTML we can put the content as a list in 3 forms:

1) Ordered lists: We can create ordered lists by using `<ol>` and each item should be placed in `<li>`.

2) Unordered lists: We can create unordered lists by using `<ul>` and also each item should be placed in `<li>`.

3) Definition lists: We can create Definition lists by using `<dl>`, and because this tag is intended to be the definition, we need `<dt>` to put the definition term and `<dd>` used to contain the definition.

We can create nested  lists by adding another `<ul>` in `<li>` tag.

# CSS

Box in CSS consist of: margins, borders, padding and the content.

![box in CSS](https://codinglead.github.io/images/box-model.png)

Using properties, we can modify the appearance of boxes in CSS, so we can:
1) Control the dimension of boxes.
2) Create borders around boxes.
3) Set margins and padding for boxes.
4) Sow and hide boxes.

## Height and width 

We can adjust the width and the height of the box by using width and height properties, and the dimension unit is either in pixels, percentage, or ems, and the pixel unit is the most used unit because it enables the programmer to better control the dimensions. 

There are (min-width, max-width, min-height, max-height) properties, and the aim of them is to restrict the largest and smallest size of the box in order to avoid changing the arrangement of the contents or the way they are displayed.

## Overflow

This property allows the browser to deal with the contents of the box. If the contents of the box are larger than the box itself, there are two properties:

1) (overflow: hidden) : hide any content exceeding the size of the box.

2) (overflow: scroll) : creates a scrollbar to navigate to the redundant content.

## Border

We can control the width of the borders of the box using the (border-width) property. And we can also control the shape of the borders of the box using (border-style property), and this property allows many shapes such as solid borders and dashed borders. And we can also modify the border color of the box using a (border-color) property.

## Padding

This property is used to increase the distance between the elements of a single box.

## Margin

This property is used to increase the distance between the boxes.

## Display

This property allows controlling the way the box elements are displayed, and these methods are (display: inline, display: block, display: inline-block) etc.

## Visibility

This property allows hiding a specific box with its contents while keeping the space between the boxes.

Several properties can be added to the funds, such as (border-img), (box-shadow) to make box shadows, (border-radius) to make rounded corners.

# JavaScript

## Switch statements

It similar to if-else statement. It starts with a variable called the switch value. This variable will be the basis for comparison between it and between cases. Switch statement contains cases, if the result is true, the first case is executed and if it is false it moves to the next case, and to separate between cases we use break after each case. After the last case we write (default) and its mission is to execute its command box if all cases are false.

![switch statement](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/03/JavaScript-Switch-case-execution-flow.jpg)

## Loops

It is a block of programming commands, it is executed more than once based on the fulfillment of the condition, and it stops working at the first false of the condition, and we have 3 types:

1) For loop: It is used if we want to execute the programming commands a certain number of times, and a counter is used to determine the number of times of execution, and it is the most used. 

General form: For(initialization ; condition ; update ){the code}.

![for loop](https://cdn.programiz.com/sites/tutorial2program/files/javascript-for-loop.png)

2) While loop: We use it when we don't know how many times a loop will repeat, and it stops working at the first false.

General form:  While(the condition){the cod}.

![while loop](https://cdn.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-while-loop.png)

3) Do while loop: Similar to the previous type, but the difference is that it executes the condition one time again for the last time after the first false. 

General foem: do {the code } while(the condition);

![do while loop](https://cdn.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-do-while-loop.png)
