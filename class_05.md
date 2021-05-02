## Images

#### Images can improve the design and the appearance of a web page.

![HTML Image](https://elzero.org/wp-content/uploads/2019/06/learn-html4.png)

### HTML Images Syntax

#### The HTML < img > tag is used to embed an image in a web page.

#### Images are not technically inserted into a web page; images are linked to web pages. The < img > tag creates a holding space for the referenced image.

#### The < img > tag is empty, it contains attributes only, and does not have a closing tag.

#### The < img > tag has two required attributes:

- src : Specifies the path to the image
- alt : Specifies an alternate text for the image

### The src Attribute

#### The required src attribute specifies the path (URL) to the image.

#### ** Note: ** When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

### The alt Attribute

#### The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

#### If a browser cannot find an image, it will display the value of the alt attribute

---------------

## Color

#### HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

### Color Values

#### In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

![HTML color](https://cdn.educba.com/academy/wp-content/uploads/2019/12/HTML-Colors-.png)

---------------

## Text

#### HTML contains several elements for defining text with a special meaning.

![Text tags](https://docs.moodle.org/2x/pl/images_pl/6/6f/Html_tags.png)


### HTML Formatting Elements

#### Formatting elements were designed to display special types of text:

- < b > - Bold text
- < strong > - Important text
- < i >  - Italic text
- < em > - Emphasized text
- < mark >  - Marked text
- < small > - Smaller text
- < del > - Deleted text
- < ins > - Inserted text
- < sub > - Subscript text
- < sup > - Superscript text

## Text Families

#### The font-family property specifies the font for an element.

#### The font-family property can hold several font names as a "fallback" system. If the browser does not support the first font, it tries the next font.

![Text Family](https://static.javatpoint.com/csspages/images/how-to-use-google-fonts-in-css2.png)

#### There are two types of font family names:

- family-name - The name of a font-family, like "times", "courier", "arial", etc.
- generic-family - The name of a generic-family, like "serif", "sans-serif", "cursive", "fantasy", "monospace".

#### Start with the font you want, and always end with a generic family, to let the browser pick a similar font in the generic family, if no other fonts are available.

