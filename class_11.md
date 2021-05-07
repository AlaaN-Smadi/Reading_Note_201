## Images

![html image](https://acumbamail.com/blog/wp-content/uploads/2014/10/maquetacion-email-html.png)

#### The HTML < img > tag is used to embed an image in a web page.

#### Images are not technically inserted into a web page; images are linked to web pages. The < img > tag creates a holding space for the referenced image.

#### The < img > tag is empty, it contains attributes only, and does not have a closing tag.

### The < img > tag has two required attributes:

- src - Specifies the path to the image
- alt - Specifies an alternate text for the image

#### When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the "alt"text are shown if the browser cannot find the image.

#### The width, height, and style attributes are all valid in HTML.

#### However, we suggest using the style attribute. It prevents styles sheets from changing the size of images.

-----------

## Audio & Video APIs

### How it Works

#### The controls attribute adds video controls, like play, pause, and volume.

#### It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

#### The < source > element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

#### The text between the < video > and < /video > tags will only be displayed in browsers that do not support the < video > element.

![Video](https://samanthaming.gumlet.io/tidbits/91-html-video.jpg.gz)

### HTML Video Formats

#### There are three supported video formats: MP4, WebM, and Ogg. The browser support for the different formats is:

Browser	| MP4 | WebM | Ogg
------- | ----- | ----- | -------
Edge | YES | YES | YES
Chrome |	YES	| YES	| YES
Firefox	| YES |	YES	| YES
Safari	| YES |	YES	| NO
Opera	| YES	| YES	| YES


### HTML Video Tags

Tag |	Description
----- | ---------
< video > |	Defines a video or movie
< source >	| Defines multiple media resources for media elements, such as < video > and < audio >
< track >	| Defines text tracks in media player

