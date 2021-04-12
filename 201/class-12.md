# Chart.js

Charts are better than tables for displaying data. You can create a chart in JavaScript using the canvas element in HTML and allow creating different types of charts like a bar chart, line chart, and pie chart.

![bar chart example](https://i1.wp.com/www.cssscript.com/wp-content/uploads/2019/12/Tiny-Animated-Column-Chart-In-Pure-JavaScript-rbar.js.png?fit=714%2C496&ssl=1)

![line chart example](https://cms-assets.tutsplus.com/uploads/users/48/posts/28129/image/Chart.png)

![pie chart example](https://apexcharts.com/wp-content/uploads/2018/05/simple-pie-chart.svg)

## Setting  up

First step is downloading **chart.js**, then creat a `<script>` tag in HTML file and put the relative linke of charts file in it. EX: `<script src="chart.min.js"></script>`.

## Drawing a chart

When creating any chart, we need to create `<canvas>` element at first in the HTML file. Then we need to write a `<secript>` that will contain the containing the context of the canvas. Also in the same `<script>` tag we writing the data that we want to show in our chart.

# The canvas element

The `<canvas>` tag has two attributes, **width** and **height**, and the attributes used to determine the dimensions of the element. Also, we can use **id** attribute in `<canvas>` tag.

# The rendering context

The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown.

# Drawing shapes with canvas

## The gride

We should know -before drawing shapes- the canvas grid or **coordinate space**. The default values of width and height in `<canvas>` element are 150 px for each attribute. The image below shows the default grid overlayed canvas.

![coordinate space](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes/canvas_default_grid.png)

 Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. 

 ## Drawing rectangles

 `<canvas>` only supports two primitive shapes: rectangles and paths (lists of points connected by lines) and by pathes we can draw complex shapes.To draw rectangles on the canvas, we have three functions:

 1) fillRect(x, y, width, height): Draws a filled rectangle.

2) strokeRect(x, y, width, height): Draws a rectangular outline.

3) clearRect(x, y, width, height): Clears the specified rectangular area, making it fully transparent.

# Applying styles and color 

We can apply styles and colors on canvas by using specific functions to do that. We have many styles and colors which can apply on canvas elements like **Transparency** and **line styles** (which contains many options like line width and lineCap).

# Drawing text

The canvas rendering context provides two methods to render text:

1) fillText(text, x, y [, maxWidth]): Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

2) strokeText(text, x, y [, maxWidth]):Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.