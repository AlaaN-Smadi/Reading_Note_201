## The < canvas > element

#### At first sight a < canvas > looks like the < img > element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the < canvas > element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

#### The id attribute isn't specific to the < canvas > element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance). It is always a good idea to supply an id because this makes it much easier to identify it in a script.

#### The < canvas > element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas. We'll see how this is done in a dedicated chapter of this tutorial. When no styling rules are applied to the canvas it will initially be fully transparent.

#### => As a consequence of the way fallback is provided, unlike the < img > element, the < canvas > element requires the closing tag (< /canvas >). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

---------------------

## Drawing shapes with canvas


### Drawing rectangles

#### There are three functions that draw rectangles on the canvas:

 -- fillRect(x, y, width, height) --
#### Draws a filled rectangle.

  -- strokeRect(x, y, width, height) --
#### Draws a rectangular outline.

 -- clearRect(x, y, width, height) --
#### Clears the specified rectangular area, making it fully transparent.

#### Each of these three functions takes the same parameters. x and y specify the position on the canvas (relative to the origin) of the top-left corner of the rectangle. width and height provide the rectangle's size.



### Drawing paths

#### To make shapes using paths, we take some extra steps:

 -- beginPath() --
#### Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

 -- Path methods --
#### Methods to set different paths for objects.

 -- closePath() --
#### Adds a straight line to the path, going to the start of the current sub-path.

 -- stroke() --
#### Draws the shape by stroking its outline.

 -- fill() --
#### Draws a solid shape by filling the path's content area.



### Lines

#### For drawing straight lines, use the -- lineTo() -- method.

#### This method takes two arguments, x and y, which are the coordinates of the line's end point. The starting point is dependent on previously drawn paths, where the end point of the previous path is the starting point for the following, etc. The starting point can also be changed by using the moveTo() method.

----------------------

## Applying styles and colors

 -- Colors --

#### there are two important properties we can use: -- fillStyle -- and -- strokeStyle -- .

 -- fillStyle = color --
#### Sets the style used when filling shapes.

 -- strokeStyle = color --
#### Sets the style for shapes' outlines.

#### color is a string representing a CSS < color >, a gradient object, or a pattern object.



## Transparency

 -- globalAlpha = transparencyValue --
#### Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.


## Line styles

 -- lineWidth = value --
#### Sets the width of lines drawn in the future.

 -- lineCap = type --
#### Sets the appearance of the ends of lines.

 -- lineJoin = type --
#### Sets the appearance of the "corners" where lines meet.

 -- miterLimit = value --
#### Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.

 -- getLineDash() --
#### Returns the current line dash pattern array containing an even number of non-negative numbers.

 -- setLineDash(segments) --
#### Sets the current line dash pattern.

 -- lineDashOffset = value --
#### Specifies where to start a dash array on a line.

-----------------

## Drawing text

#### The canvas rendering context provides two methods to render text:

 -- fillText(text, x, y [, maxWidth]) --
#### Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

 -- strokeText(text, x, y [, maxWidth]) --
#### Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.


## Styling text

####  There are some more properties which let you adjust the way the text gets displayed on the canvas:

 -- font = value --
#### The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

 -- textAlign = value --
#### Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

-- textBaseline = value --
#### Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

 -- direction = value --
#### Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.


## Advanced text measurements

 -- measureText() --
#### Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.

