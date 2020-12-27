### Design web pages with CSS
#### chapter 10 :
* **Block** level elements look like they start on a new line(h1,h2,p). **Inline** elements flow within the text and do not start on a new line(span,li).

* In CSS we have a **selector** to control the style of each  element, this selector works with HTML tags


`P {color:black ; fonr-size-20px} `


* **External CSS** write the CSS style in external file an then link the CSS file with HTML file by write `<link>` inside the `<head>` , `href `This specifies the path to the CSS file , `type`This attribute specifies the type
of document being linked to, The value should be text/css ,`rel` This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.


* **The selector** could be :
     1. element itself.
     2. id name .
     3. class name.


#### chapter 11 :
##### Color: 
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

* **HSL colors** for hue , saturation ,lightness 


