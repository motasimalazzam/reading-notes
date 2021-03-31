# HTML

## Links

The link feature allows navigation between web pages, whether between pages on the same site or between pages of other sites.

1) Linking to other sits:

To put a link to another website we use `<a>`, and this tag comes with the **href** feature that stores the website link inside it and this link is called ***absolute URL***.
EX: `<a href=” http://www.google.com”> google website</a>`

2) Linking to other pages on the same site:

We use `<a>`, in the same way as the previous one, but here we use the different type of link called ***relative URL***.

### Directory structure 

When building a multi-page site, the best way is to build each page in its own folder, and this facilitates the design process and the programmer deals with the contents of the site, and each file and each folder has its own relative URL.

3) Email links:

To put a link containing a specific email address we want to send mail to, we add **mailto** to the **href** feature.

EX: `<a href=” mailto: user@email.com” > email </a>`

4) Opining links in a new window:

To open a web page link in a new window we use the target property followed by _blank.

EX: `<a href=” http://www.google.com “ target=”_blank”> google website </a>`.

5) Linking to a specific part of the same page:

To do this, we must first create an id for the part you want to create a link for, where the id is used to create the link.

EX: `<a href=”#top”> top</a>`

Note that when creating a link it must begin with # before the id.

# CSS

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

# JavaScript

The functions, methods and objects are used to perform special tasks, and it reduces the number of codes used for the same tasks and this helps to organize the codes.

## Functions 

It is a set of programming commands within a single group that perform a specific task.
The first step to create a function is declaring a function. In another meaning, give the function a name and then write the codes inside curly braces.

![ declaring a function in javascript ](https://matw.me/wp-content/uploads/2018/11/anatomy_of_a_function2-300x188.png)

After creating the function, we can use it and execute the commands inside it when needed, and this process is called calling the function, and this is done by writing the function name followed by parentheses. After the function's task finishes, it returns to its calling point.

Sometimes the function needs certain information to complete its task, and this information can be stored in the parameters, which are variables that are defined during the declaring of the function. When calling a function containing parameters, the function name must be written, and in parentheses the parameters are written, in this case, the parameters are called arguments. Some functions returning a value and this is called return.

![calling the function](https://cdn.programiz.com/sites/tutorial2program/files/javascript-function-with-parameter.png)