## Basics of HTML, CSS & JS
### HTML Book!
#### chapter 2 "Text":
* We have 2 types of Markups :
     1. **Structural markup:** the elements that you can use to describe both headings and paragraphs.
  

    Name | tag | description
    -----|-----|-----------
    **Heading** |`<h1>..</h1> ,<h2> ...</h2> ,<h3>..</h3>,<h4>...</h4>,<h5>..</h5>,<h6>...</h6> ` |we have a 6 levels of heading , the biggest is h1 used for main headings, and smallest h6. ![heading levels](heading.png)
    **Paragraph** | `<p>  ...content... </p>` |to create a paragraph.
    **Bold** | `<b> ... content..</b>` | make characters appear bold.
    **Italic** | `<i> .. content .. </i>` | make characters appear italic.
    **Superscript** |`<sup> ..content.. </sup>` |used to contain characters that should be superscript 
    **Subscript** | `<sub> ..content..</sub>` | contain characters that should be subscript. ![Superscript & Subscript](sub_sup.png)
    **white space** | `&nbsp;`| when you write more than 2 white space the browser will show only one white space ,if you need to big white space `&nbsp;` each time you write this word will show in browser as white space.
    **Line Breaks** | `<br />` or `<br>` | to start new line or new paragraph .
    **Horizontal Rules** |`<hr />` or `<hr>` | to paint a Horizontal line.



     2. **Semantic markup:** which provides extra information; such as where emphasis is placed in a sentence, that omething you have written is a quotation (and who said it), the meaning of acronyms, and so on.

     Name | tag | description
     ------| -----| ----------
     **Strong** | `<strong> ..content.. </strong>`| indicates that its content has strong importance. will show in bold .
     **Emphasis** |`<em> ..content.. </em>` | indicates emphasis that subtly changes the meaning of a sentence. show in italic
     **Quotations** | `<blockquote> `| used for longer  uotes that take up an entire paragraph.
     **Quotations** | `<q> .. contemt.. </q>` | shorter quotes that sit within a paragraph.

     **Abbreviations**| `<abbr title ="professor" > prof</abbr>`| A title attribute on the opening tag is used to specify the full term.
     **Citations** |`<cite> ..content..</cite>`| When you are referencing a piece of work such as a book, film or research pape
     **Definitions** | `<dfn> ..content ..</dfn>`| element is used to indicate the defining instance of a new term.
     **Author Details** | `<address> .. content..</address>` |to contain contact details for the author of the page.

     **inserted** | `<ins> ..content ..</ins>` |element can be used to show content that has been inserted into a document,The content usually underlined.
     **delete** |`<del>..content ..</del>` |show text that has been deleted from it,the content usually has a line through it.

#### Chapter 10: “Introducing CSS"

* CSS allows you to create rules that control the way that each individual box (and the contents of that box) is  resented.
* **Block** level elements look like they start on a new line(h1,h2,p). **Inline** elements flow within the text and do not start on a new line(span,li).

* In CSS we have a **selector** to control the style of each  element, this selector works with HTML tags


`P {color:black ; fonr-size-20px} `


* **External CSS** write the CSS style in external file an then link the CSS file with HTML file by write `<link>` inside the `<head>` , `href `This specifies the path to the CSS file , `type`This attribute specifies the type
of document being linked to, The value should be text/css ,`rel` This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.


* **The selector** could be :
     1. element itself.
     2. id name .
     3. class name.

![selectors types](selector.png)


### JavaScript Book! 
#### Chapter 2: “Basic JavaScript Instructions”


* A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.

**JAVASCRIPT IS CASE SENSITIVE this mean aya not equal AYA or Aya**

* Add comment to explain to you do in this code, use // before the text to write a single line comment, /* with multiple lines and end with */

* Choose a meaningful names for variables, names that indicate to the value inside it.

* Var keyword using to indicate that we want to create variable .
 **`Va x ;`**

* To assign then the value 
X = value 
The values could be number (0,1,2,…,etc or fraction numbers )or string (group of characters starts and ends with “ “ or ‘ ‘ ) or Boolean(True,false)

* To print the “ inside the code used backslash before the” to escape the quotation mark .

* When you assigned a value to variable you can change the value by write the variable name and then assigned the new value .
`Var x=5 ;`
`X= 8 `
This called “ overwriting” and the final value that stored in x is 8 


#### 6 Rules to choose the variable name :
1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.
2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.
3. You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript. ONLINE EXTRA View a full list of keywords and reserved words in JavaScript.
4. All variables are case sensitive so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases.
5. Use a name that describes the kind of information that the variable stores. For example, fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age.
6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash).


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




#### chapter 4 

1. Comparison operators:
 * **==** return True if the values are the same` 50 == "50" ` , ` "aya" == "aya" ` , `10 == 10` all of them return True, `"aya" == "AYA"` not the same soreturn False.
 * **!=** return True if the values are not the same `"aya" != "AYA" ` return True.
 * **===** return True if the values are the same and the data type of them also the same ` 50 === 50` return True, **but** ` 50 === " 50"` return False .
 * **!==**  return True if the values are the same and the data type of them are different ` 50 !== "50"` return True.
 * **<** less than 
 * **>** greater than
 * **<=** less than or equal
 * **>=** greater than or equal

2. logical operators :
     * **|| called OR**  return True if we have at least one side is True ` T || T` ,` F || T`,` T || F` , and return false if the both sides are false ` F || F`.

     * **&& called AND**  return True if the both sides are True ` T && T`, and return false if we have at least one F ` F && T`,` T && F` ,` F && F`.

     * **! called NOT** return true if the value False `!False` , return false if the value true `!True` .
