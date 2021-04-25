# Readings : Chart.js, Canvas

**Charts** are used to display data and they’re easier to look at and convey data quickly you can use Chart.js is a javascripy plugin that uses HTML5 canvas element to draw the graph into the page. and you should download it first then you can ust it by puting it inside script tag `<script src='Chart.min.js'></script>` like this and to draw a chart first you should create canvas element `<canvas></canvas>` 


**Canvas**: `<canvas></canvas>` It's like the image but it just has the width and hieght property. and it has a fallback content it means it works on the browser that doesn't support it, it will ignore container and render the canvas content (fallback content) inside it. `<canvas id="tutorial" width="150" height="150"></canvas>` it must have the closing tag.

How to draw on canvas If you want to draw a rectangle you have three function to draw it 
- fillRect(x, y, width, height)
   Draws a filled rectangle.
- strokeRect(x, y, width, height)
   Draws a rectangular outline.
- clearRect(x, y, width, height)
   Clears the specified rectangular area, making it fully transparent.

And you can draw the path by using drawing command beginPath(), Path methods, closePath(), stroke() and fill().

You can draw Arcs by usin arc() or arcTo() methods.and it used measured in radius  not degrees you can convert it like yhis radians = (Math.PI/180)*degrees.
And you can make Bezier and quadratic curves,Cubic Bezier curves and Making combinations.

Also you can applying style and color on canvas by using  fillStyle and strokeStyle. We can also draw semi-transparent globalAlpha property. and Line styles to make a style to it.

You can also draw a text canvas render context provides two methods to render text: fillText(text, x, y [, maxWidth]) and strokeText(text, x, y [, maxWidth])
And you can style the text by change the font, text-align, textBaseline and direction.





[Home](README.md)

