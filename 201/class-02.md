# Text in HTML 

1) HTML has 6 heading (h1,h2,h3,h4,h5,h6), the `<h1>` is the biggest heading and it used for main heading. There is an inverse relationship between the heading level and its importance and size.  

2) Paragraph: to put a paragraph in the web page we use `<p>` and put the paragraph between the tag.

3) Bold and italic: to make some content of text bold or italic we can use `<b>` for bold and `<i>` for italic.

4) Superscript and subscript: `<sup>` is used to superscript some characters such as suffix of dates. `<sub> `is used to subscript some characters such as chemical formulas.

5) Line breaks and horizontal rules: `<b/>` is used to add new line inside the middle of a paragraph. `<hr/>` is used to draw a horizontal line to separate sections.

## Semantic markup

Semantic elements do not affect the content of HTML but we used it to give other programs more information.

1) `<strong>` : it used to define text with strong importance and the content inside it displayed in bold.
The different between `<b>` and `<strong>` is the importance.

2)`<em>` : is used to define emphasized text and the content inside it displayed in italic.

3) Quotations: we use to tags to quotation text, `<blockquote>` for long quotation and `<q>` for short quotation.

4) `<abbr>`: use it for an abbreviation or acronym.

And also  we have `<address>` for author details, `<ins> <del>` and `<s>` for changes to content.

# CSS

CSS: allows you to control the way the page contents are displayed, such as the color, size, and position of the elements. CSS have two parts:

1) Selector: Select the element which you want to formatting it.

2) Declaration: Determine the format you want to add. Sit inside curly brackets and have two parts (property and value) and you can add You can add more than one property and separate them by semi colon.

![selector and delacration](https://uploads.sitepoint.com/wp-content/uploads/2013/05/figure2.png)

We can use the CSS by 3 ways:

1) Inline: write in the same line in opining tags. (EX: `<p style=” color: blue;”> </p>` ).

2) Internal: Write it in HTML in the head. (EX: `<style> p{ color: blue;} </style>` ).

3) External: create CSS file and link it with the HTML file by writing `<link rel=”stylesheet” href=”path css file”>` .

 # Java script

JavaScript is a programing language and it is make the website interactive and we can use logic and math in it. So HTML elements for building the website and JavaScript for making the website dynamic. Steps to write a script: 1) stat your goal 2) design the script 3) code your ideas.

Statement: A series of commands that the computer tracks and executes one by one, and sometimes the commands are placed in one group between {} and it is called code blocks.

Variables: We can use variables to store different type in it ( numeric, string and Boolean), which we need it to do some job. But at first we must declare it.

![declare value](https://1.bp.blogspot.com/-8UmWFTngfwY/XkVRuoPFfkI/AAAAAAAACmI/93j-FMkA9EYyoRIT1qlJ2sMUbobnWT1UgCLcBGAsYHQ/s1600/javascript_var.png)

Array: it is a special type of variable, which we can store a list of values in it and variables are related to each other. We can create an array by 2 methods:

1) Give it a name and the values are assigned to the array inside a pair of square brackets and each value is separated by comma. EX: var number =   [ ‘1’ , ‘2’ , ‘3’ ]; .

2) By using new keyword followed by Array(). EX: var number= new Array ( ‘1’ ,’2’, ‘3’); .

Expressions: expressions that just assign a value to a variable, the general form is [ name = value ].

Operators: create a single value from one or more values: 

1) Assignment operator: Assigning one value to a single variable ( Ex: name = Azzam).

2) Arithmetic operator: Use arithmetic operations to give a variable a value ( Ex: y = 5+6).

3) String operator: Combine two strings ( Ex: MyName = ‘ Motasim ‘ + ‘ Alazzam’ ).

4) Comparison operator: Compare between two values and return true or false ( Ex: 3>5 ).

5) Logical operator: Combine expressions and return true or false ( Ex: price= (1030) &&(35).

## If statements

It used for evaluating or checking a condition and if the condition is true, any statement in the subsequent code block are executed.

### If … else statement: 

if the first code block is false, the second code block is run instead.

![if else statmenet](https://cdn.programiz.com/sites/tutorial2program/files/js-if-else-statement.png)

