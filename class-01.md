### HTML Book
#### Introduction 
##### How People Access the Web :
* **web browser** :Software allow you to visit and access the websites (safari,google chroom,opera ,...)
* **Web Servers** :Are special computers connected to the internet, when you visit the website, you sent a request to this machine to visit the website.
* **Devices** : we have a diiferent devices and connections.
* **Screen readers**:are programs that read out the contents of a computer screen to a user.


* you can be anywhere in the world and sent a request to open any website , the browser in your region will connect to the **Domain Name System (DSN)** to the website region to allow you visit the website.

     1. When you connect to the web, you do so via an Internet Service Provider (ISP). You type a domain name or  eb address into your browser to visit a site; for example: google.com, bbc.co.uk, microsoft.com.
     2. Your computer contacts a network of servers called Domain Name System (DNS) servers. They tell your computer the IP address associated with the requested domain name. Every device connected to the web has a unique IP address; it is like the id for that computer.
     3. The IP address that the DNS server returns to your computer allows your browser to contact the webserver that hosts the website you requested.
     4. The web server then sends the page you requested back to your web browser. 


#### HTML Chapter 1 (Structure) :
* HTML pages contain a set or group of tags , this tags will determine the Structure and content of your website.
* HTML refer to Hyper Text Markup Language .
* HTML contain a  tags , each tag has a different usage that called a elements.


* Important elements that should be in every website :
     1. The opening `<html>` tag indicates that anything between it and a closing `</html>` tag is HTML code.
     2. `<head> .. </head>` contain a meta data and the information that will not show in website .
     3. The `<body>` tag indicates that anything between it and the closing `</body>` tag should be shown inside the main browser window.


* elements usually have a opening tag and closing tag (for example :` <p>   </p>`), and some element ( for example : `<img>`) don't have a closing tag.


* Attributes provide additional information about the contents of an element.
* each attribute contain a Attribute_name and value `<p id="id1"> </p>` , id is a Attributes_name and id1 the value.


#### HTML Chapter 8 (Extra Markup) :
1. `<! DOCTYPE ......>` to tell a browser which version of HTML the page is using.
3. `<!-- -->` make a comment are not visible to users in the main browser window in HTML `<!-- comment goes here -->`.
3. **id** attribute used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character).
4. **class** attribute identify several element as being different from the other elements on the page.
5. **BLOCK** ELEMENT start on a new line in the browser window (`<p>`, `<h1>`).
6. **INLINE** ELEMENT appear to continue on the same line as their neighbouring elements(`<span>` , `<a>`).
7. `<span>` element acts like an inline equivalent of the `<div>` element. It is used to either:Contain a section of text where there is no other suitable element to differentiate it from its surrounding text , Contain a number of inline elements The most common reason why people use `<span> ` elements is so that they can control the
appearance of the content of these elements using CSS.
8. `<iframe>` common use to embed a Google Map into a page. `src` The src attribute specifies the URL of the page to show in the frame. `height` The height attribute specifies the height of the iframe in pixels. `width` The width attribute specifies the width of the iframe in pixels.`scrolling`indicates whether the iframe should have scrollbars or not ,`frameborder` indicates whether the frame should have a border or not. `seamless`where crollbars
are not desired.

9. special symbols 
![special symbols](shortcut.png)


#### HTML Chapter 17 (HTML5 Layout) :
* HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them.
     1. `<header>`,`<footer>`The main header or footer that appears at the top or bottom of every page on the site.
     2. `<nav>` navigation bar contain the main links (pages) on your website
     3. `<section>`element groups related content together, and typically each section would have its own heading.
     4. `<aside>`When the `<aside>` element is used inside an `<article>` element, it should contain information that is related to the article ,When the `<aside> `element is used outside of an `<article>` element, it acts as a container for content that is related to the entire page
     5. `<article>` container for any section of a page that could stand alone and potentially be syndicated.
     6. `<hgroup>` to group together a set of one or more `<h1>` through `<h6>` elements.
     7. `<figure>` contain images, Videos, Graphs,Diagrams, Code samples ,Text that supports the main body of an article.
     8. `<figcaption>` which provides a text decription for the content of the` <figure>` element.
     9. ` <div>` element will remain an important way to group together related elements.

* Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.



#### HTML Chapter 18 (Process & Design):
* Every website should be designed for the **target** audience , you should determine **who** people will visit your website and **why** and **what** they need , and ask yourself set of questions to make determine the target more easily.

* should determine the **sitemap** to make the designing step more easily.that allow you to plan the structure of a site
![sitemap img](sitemap.png)

* **WireFrames** A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.

 ![WireFrames](WireFrames.png)

 * **manage the content to** Organizing and prioritizing information on a page helps users understand its importance and what order to read it in.

 * **Visual hierarchy**  You can use contrast (size, color ,style) to create a visual hierarchy that gets across your key message and helps users find what they are looking for.

 * **grouping and Similarity** organize visual elements into groups (Proximity,Closure,White Sp ace,Continuance,color,Borders)

 * **Designing Navigation** helps people find where they want to go and understand what your site is about and how it is organized (*Concise,Clear,Selective,Context,Interactive,Consistent*)



### JavaScript Book 
#### Introduction :
###### why we use JAvaScript :
* allows you to **ACCESS** content .
* allows you to **MODIFY** content .
* **program resuls** while you writing a steps , the browser will following and executing the steps.
* **react** to to events triggered by the user or browser(when you press to any key from keyboard , clicked the mouse , double clicked ,.. all of them called event ) .


#### chapter 1 (The ABC of Programming) :
##### WRITING A SCRIPT :
* the fist step is DEFINE the goal then DESIGN then CODE EACH STEP .

* to write a clear code you should learn :
   1. **Vocabulary**:The words that computers understand.
   2. **Syntax**: How you put those words together to create instructions computers can follow.

* what might have gone wrong - programmers call **debugging.**
* Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.

###### What happens when you entered your name inside imput feild and press to btn (ok)?
1. The script is triggered when the button is clicked.
2. It collects the name entered into the form field.
3. It checks that the user has entered a value.
4. If the user has not entered anything, a message will appear telling them to enter a name.


##### Expressions + Operators:
###### EXPRESSIONS :
   * there are two types of expressions:
      1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE ` var name="aya" `
      2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE ` var area =5*2 `. the value that stored in area var is 10 .

###### OPERATORS :
   *  ASSIGNMENT OPERATORS `name= "aya" ; ` here we assgin the value to the variable.
   *  ARITHMETIC OPERATORS ` area = 3 * 2; `   
   *  STRING OPERATORS ` fullName ='aya'+'alasmar' ;` Also MIXING NUMBERS AND STRINGS equal STRING ` '5' + 5 = 55 ` , the result '55' is string.
   *  COMPARISON OPERATORS `buy = 3 > 5;`
   *  LOGICAL OPERATORS ` buy= (5 > 3) && (2 < 4);`

###### Mathematical operators in JavaScript:
![mathematical operators img](js.png) 

* **ORDER OF EXECUTION :**
     1. parentheses.
     2. Multiplication and division .
     3. addition or subtraction.
* Arrays are special types of variables that store more than one piece of related information.

##### Functions :
   * function indicate to set of statements that written for acheive specific gaol.
   * you can reuse the function.
   * every function contain **NAME** should describe the task it is performing. when you ask it to perform its task, it is known as ***calling*** the function.
   * Some functions need to provided with information in order to achieve a given task. this information called ***parameters***
   * When you write a function and you expect it to provide you with an answer, the response is known as a ***return value***.
   



