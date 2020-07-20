# Docs for the HTML \<canvas\> Element and Chart.js

### Easily Create Stunning Animated Charts with **Chart.js** | Sara Vieira

We use charts for a more visually appealing and digestible method of displaying data.

**Charts.js**  

Charts.js is a JavaScript plug-in that uses HTML5's canvas element to display graphs.

Charts.js is used to create:  
- bar charts
- line charts
- pie charts
- and so much more!

*This article was referenced from* [HERE!](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

### Basic Usage of Canvas | MDN Contributors

**The \<canvas\> element**

The canvas has only two attributes:  
- width
- height

When no width or height is specified, the canvas is set to *300 pixels wide and 150 pixels high* as a default.

CSS can also be used to size the element, but may cause distortion.

The canvas element can use:  
- the id class
- margin*
- border*
- background*
- fallback content  
... but these rules will not affect the drawing on the canvas

Additionally, the \<canvas\> element **requires a CLOSING tag**!

Initially, the canvas is blank, and requires a script to access the rendering context.

Method:  
- getContext\()

Rendering in 2D:
  - CanvasRenderingContext2D


*This information was referenced from* [HERE!](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

### Drawing Shapes with **canvas** | MDN Contributors

**The Grid**  
- There is a default grid that is displayed over a canvas.
- The origin of the grid is set to 0 , 0 but can be modified later
- All elemend are placed relative to the origin
- The location of the canvas \(x,y\) becomes __*x*__ pixels from the left of the origin and __*y*__ pixels from the top.

Knowing the position of the canvas is essential for creating different types of canvases, like:  
- Rectangles
- Drawing Paths
- Triangles
- Arcs
- Curves
- Many other shapes too!

*This information was referenced from* [HERE!](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)



[**Return to Home**](README.md)