# HTML

## images

The strong site contains pictures that express the site, but we must be careful when using images, we must pay attention to copyright. When using pictures, it is best to put all pictures in their own folder.

To add image in our website we use **`<img>`** tag in HTML file which indicate more than one values. in ***src*** value we put the linke of image, and in ***alt*** value put a description of the image, and at the end we use ***tittle*** to write more information about the image.

Also we can control the image size bu using ***width*** and ***height*** values in `<img>` tag, and we can align the image by using ***align value***. We can specify the align value, we can align it horizontally by use ***align-left*** or ***align-right***, or vertically by ***align-top***, ***align-bottom*** or ***align-midde***.

HTML5 contain a **`<figure>`** and **`<figcaption>`** for image which came with the caption.

# CSS

## Color

The color feature allows adding colors to the texts or the background of the page, and this is done in 3 ways:

1) Rgb values: (red green blue) It is a measurement made of numbers between 0 to 255 for each color. (EX: rgb(102,222,0) ). And there is rgba, and the a is alpha, which denotes opacity And its value is between 0 and 1.

![rgb color in CSS](https://tutorial.techaltum.com/images/css-colors.jpg)

2) Hex codes: (rr gg bb) these are six digit codes, It is a measure of the amount ofred, green, and blue colors in a single color. ( 00 is the lowest value and ff is the largest value).

![Hex color in CSS](https://tutorials.freshersnow.com/wp-content/uploads/2020/02/css-color-1.png)

3) Color name: There are 147 colors and only the color name is written to be added.

Hue

The color gradation is by a circle, that is, the color gradient is from 0 to 360. Saturation is amount of gray in color ( 0% gray , 100% full color). Lightness is amount of white in color ( 0% black , 100% white).

![Hue color in CSS](https://www.quackit.com/pix/stock/color_wheel_hsl.png)

## Text

To specify typefaces of the text we use **font-family** property in the CSS file to apply the style on the text.

We can increase or decrease the size of the text by using **font-size** property, and for the value we can use ***px***, ***percentages*** or ***ems*** as a unit.

The **font-weight** property allows us to create bold text. And to make an italic text, we use **font-style** property.

To change the case of the text, we use **text-transform** property which allows us to put 3 values:

1) ***uppercase***: To appear the text in upper case.

2) ***lowercase***: To appear the text in lower case.

3) ***capitalize***: To appear the first letter of each word to capitalize.

**text-decoration** property has values, which can use it to decorating the text:

1) ***none***: This value remove any decoration already applied to the text.

2) ***underline***: Adds a line underneath the text.

3) ***overline***: Adds a line over the top of the text.

4) ***line-through***: Adds a line through words.

There are many properties which can apply to the text, like:

1) **line-height**: Use to increase or decrease the vertical space between the line.

2) **letter-spacing**: Use to increase or decrease the space between letters.

3) **word-spacing**: Use to increase or decrease the space between the words.

4)**text-align**: Control the alignment of the text and it has 4 values *** (left, right, center and justify) ***