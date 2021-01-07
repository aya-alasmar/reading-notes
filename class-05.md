## HTML Book
#### chapter 5 "images"
* If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.
##### Adding Images 
* `<img>` this element to add image to the webpages.
* `src` it's an attribute in img element indicate to the urls/path of the image.
* `alt` it's an attribute in img element provide alternative text if the image did't load or happen any problem with urls.
* `title`  it's an attribute in img element provide additional information about the image.
* `height` it's an attribute in img element to specifies the height of the image in pixels.
* `width` it's an attribute in img element to specifies the width of the image in pixels.

##### Where to Place Images in Your Code
1. **before a paragraph** The paragraph starts on a new line after the image.
2. **inside the start of a paragraph** The first row of text aligns withthe bottom of the image.
3. **in the middle of aparagraph** The image is placed between the words of the paragraph that it appears in.


* Block elements always appear on a new line.
* Inline elements sit within a block level element and do not start on a new line.

##### Three Rules for Creating Images
1. Save images in the right format.
2. Save images at the right size.
3. Use the correct resolution .

##### Image Formats: 
1. **JPEG**  Whenever you have many different colors in a picture you should use a JPEG.
2. **GIF and PNG**  when saving images with few colors or large areas of the same color

* The images you use on your website should be saved at the same width and height that you want them to appear on the page.


###### Resize the images :
1. **REDUCING IMAGE SIZE** You can reduce the size of images to create a smaller version of the image.
     * **Example**: If your image is 600 pixels wide and 300 pixels tall, you can reduce the size of the image by 50%.
2. **INCREASING IMAGE SIZE** You can't increase the size of photos significantly without affecting the image quality.
     * **Example**: If your image is only 100 pixels wide by 50 pixels tall, increasing the size by 300% would result in poor quality.
3. **CHANGING SHAPE** Only some images can be cropped without losing valuable information (see next page).
     * **Example**: If your image is 300 pixels square, you can remove parts of it, but in doing so you might lose valuable information.


###### Cropping Images
* When cropping images it is important not to lose valuable information. It is best to source images that are the correct shape if possible.

* Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.




#### chapter 11 "Color"
* **Every color on a computer screen is created by mixing amounts of red, green, and blue this calles (RGB)**.
* We used color with different ways:
     1. RGB ` color : rgb(0-255,0-255,0-255)` 
     2. Hex codes `color : #ee3e80`
     3. Color names `color : red;`

* We can choose the background or foreground color using this ways .
* each element have a background color value .
* When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.
     * **low constract** lower contrast between background and foreground colors.
     * **meduim constract** For long spans of text, reducing the contrast a little bit improves readability.
     * **high constract** higher contrast between background and foreground colors.

* **Opacity** allows you to specify the opacity of an element and any of its child elements. The value is a number between *0.0 and 1.0*.

* **HSL colors** for hue , saturation ,lightness .



#### chapter 12 "Text" 
###### Typeface Terminology
1. **Serif** Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs.
2. **Sans-Serif** Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.
3. **Monospace** Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts have different widths.)

* **weigth** values are light, meduim ,bold , dolder.
* **Style** values are *italic* ,Normal, Oblique.
* **Stretch** values are Condensed ,Regular ,Extended.


###### Specifying Typefaces 

* font-family :The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.
* You can specify a list of fonts separated by commas so that, if the user does not have your first choice of typeface installed, the browser can try to use an alternative font from the list.


###### Size of Type
* font-size :The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are:
     1. **pixels** :Pixels are commonly used because they allow web designers very precise control over how much space their text takes up. The number of pixels is followed by the letters px.
     2. **percentages** The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px. If you create a rule to make all text inside the `<body>` element to be 75% of the default size (to make it 12px), and then specify another rule that indicates the content of an element inside the `<body>` element should be 75% size, it will be 9px (75% of the 12px font size).
     3. **ems** An em is equivalent to the width of a letter m.