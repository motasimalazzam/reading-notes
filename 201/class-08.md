## Layout

### Building blocks:

CSS deals with HTML elements by placing them in boxes, and the boxes are the basis for dealing with the layout. These boxes will either be a block-level box or an inline box. We can control the properties of the boxes, such as the space it occupies, or the separation of the boxes by using margin, padding, borders and background color.

* Block-level elements: Start on a new line.

* Inline elements: Flow in between surrounding text.

* Containing elements: If the position of one block-level element inside another block-level element, the outer box is known as the containing or parent element.

![ Building blocks and Inline elements ](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/06/Block-level-Inline-elements-in-html-df.jpg)

### Controlling the position of elements:

CSS contains positioning schemes and with it we can control the page layout. The positioning schemes are normal flow, relative positioning and absolute positioning. 

1) Normal flow:

In the normal flow, the location of each box is vertically above the other, and the **position:static;** property is written inside the box, and it can also not be written because it is the default position.

2) Relative positioning:

It moves the elements with a relative distance to the normal flow distance, and the **position:relative** property is written in the box, and this relative distance can be controlled by specifying the distance between the boundaries of the box and the boundaries of other boxes.

3) Absolute positioning: 

The **position:absolute;** property moves the elements and put them in a new position, and this position is determined by the programmer, but when these elements are moved to the new position, It is treated as if there are no other elements on the same site.

4) Fixed positioning:

This property is a kind of absolute positioning, the difference is when the user moves the screen to move between the page elements, the elements that contain the **position:fixed:** property remain fixed on the screen and do not move.

### Overlapping elements 

**Z-index property:** This property make an element fixed on the browser window, even when the user scrolls down the page.

**Floating elements (float):** This property allows to change the position of the element to the right or the left, and when using this property, we should use the width property to indicate how wide the floated element should be.

***Clearing floats (clear):*** This property performs a better format for elements than the Float property. Clear property did not allow the element to touch the left or right-hand sides (or both sides) of a box. This property comes with 4 value: ***left***, ***right***, ***both*** and ***none***.

### Screen size:

Visitors use different devices to visit the website, and therefore the design must be appropriate for all devices.

***Screen resolution:*** Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

***Page size:*** Due to the variety of screen sizes and resolution, designers create pages around 960-1000 pixels wide which  most of the users' screens use this pixels wide.