



## Basic usage of canvas:







#### The   `<canvas>` element :







At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height.



Fallback content :

The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, or `<picture>` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it,


Required `</canvas>` tag :


As a consequence of the way fallback is provided, unlike the `<img>` element, the `<canvas>` element requires the closing tag `(</canvas>)`. If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.


The rendering contex :

The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts.


Checking for support :


The fallback content is displayed in browsers which do not support `<canvas>`. Scripts can also check for support programmatically by testing for the presence of the getContext() method. 





## Drawing shapes with canvas :






The grid :

Before we can start drawing, we need to talk about the canvas grid or coordinate space.



Drawing rectangles :

Unlike SVG, `<canvas>` only supports two primitive shapes: rectangles and paths (lists of points connected by lines).


There are three functions that draw rectangles on the canvas :


fillRect(x, y, width, height) To Draws a filled rectangle.


strokeRect(x, y, width, height) To Draws a rectangular outline.


clearRect(x, y, width, height) To Clears the specified rectangular area, making it fully transparent.
* Each of these three functions takes the same parameters. x and y specify the position on the canvas (relative to the origin)


Drawing Paths :


A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths

`beginPath()` :


Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up


`Path methods` :

Methods to set different paths for objects.


`closePath()` :

Adds a straight line to the path, going to the start of the current sub-path

`stroke()` :

Draws the shape by stroking its outline .

`fill()` :
Draws a solid shape by filling the path's content area .






## Applying styles and colors :





Colors :

Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: `fillStyle` and `strokeStyle`.

`fillStyle = color` 

Sets the style used when filling shapes.


`strokeStyle = color`

Sets the style for shapes' outlines.


`color` is a string representing a CSS `<color>`, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black `(CSS color value #000000)`.






## Drawing text :








The canvas rendering context provides two methods to render text:

`fillText(text, x, y [, maxWidth])`
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

`strokeText(text, x, y [, maxWidth])` 

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.



Styling text:

In the examples above we are already making use of the `font` property to make the text a bit larger than the default size. There are some more properties which let you adjust the way the text gets displayed on the canvas :


`font = value`

The current text style being used when drawing text. This string uses the same syntax as the `CSS font` property. The default font is 10px sans-serif


t`extAlign = value`
Text alignment setting. Possible values: `start`, `end`, `left`, `right` or `center`. The default value is `start`.


`textBaseline = value`

Baseline alignment setting. Possible values: `top`, `hanging`, `middle`, `alphabetic`, `ideographic`, `bottom`. The default value is `alphabetic`.



`direction = value`

Directionality. Possible values: `ltr`, `rtl`, `inherit`. The default value is `inherit`.



* These properties might be familiar to you, if you have worked with CSS before.



Advanced text measurements :

In the case you need to obtain more details about the text, the following method allows you to measure it.


`measureText()`

Returns a `TextMetrics` object containing the width, in pixels, that the specified text will be when drawn in the current text style.

