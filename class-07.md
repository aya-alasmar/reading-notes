## Object-Oriented Programming, HTML Tables
### Domain Modeling
* **Domain modeling** is the process of :
     1. creating a conceptual model in code for a specific problem.
     2. describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

* This is object-oriented programming in JavaScript at its most fundamental level.
     1. The new keyword instantiates (i.e. creates) an object.
     2. The constructor function initializes properties inside that object using the this variable.
     3. The object is stored in a variable for later use.

* Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

* Here's some tips to follow when building your own domain models.

     1.  When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
     2.  Model its attributes with a constructor function that defines and initializes properties.
     3. odel its behaviors with small methods that focus on doing one job well.
     4. Create instances using the new keyword followed by a call to a constructor function.
     5. Store the newly created object in a variable so you can access its properties and methods from outside.
     6. Use the this variable within methods so you can access the object's properties and methods from inside.

### HTML Book 
#### Chapter 6: “Tables”
* A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.
* Grids allow us to understand complex data by referencing information on two axes.

##### Basic Table Structure
1. `<table>` used to create a table. The contents of the table are written out row by row.
2. `<tr>` indicate the start of each row using the opening `<tr>` tag, At the end of the row you use a closing `</tr>`.
3. ` <td>` represente Each cell of a table.
4. ` <th>`used just like the `<td>` element but its purpose is to represent the heading for either a column or a row.
5. The` colspan` attribute can be used on a` <th>` or `<td> `element and indicates how many columns that cell should run across.
6. The `rowspan` attribute can be used on a` <th>` or `<td>` element to indicate how many rows a cell should span down the table.
7. The headings of the table should sit inside the `<thead> `element.
8. The body should sit inside the `<tbody>` element.
9. The footer belongs inside the `<tfoot>` element.


### JavaScript Book 
#### Chapter 3: “Functions, Methods, and Objects” 
* creating an object constructor notaion :
     1. create a new object using combimation of the `new` keyword and the object() constructor function 
     2.  add proparties and methods to it using dot notaion 
 * to create an empty object using `var varName ={}`.
 * to update property use dot notation or `[]` then enter the new value.
 * to delete use `delete` keyword
 
LITERAL NOTATION | OBJECT CONSTRUCTOR NOTATION
-----------------|-----------------------------
 A colon separates the key/value pairs.There is a comma between each key/value pair. | The function can be used to create multiple objects. The` this `keyword is used instead of the object name.

* The keyword `this` is commonly used inside functions and objects. Where the function is declared alters what `this` means. It always refers to one object, usually the object in which the function operates.

* When a function is created at the **top level** of a script (that is, not inside another object or function), then it is in the **global scope or global context**.

* All global variables also become properties of the window object. so when a function is in the global context, you can access global variables using the window object, as well as its other properties.

* **Arrays** are a special type of object .

###### WHAT ARE BUILT-IN OBJECTS?
1. **BROWSER OBJECT MODEL** The Browser Object Model contains objects that represent the current browser window or tab. It contains objects that model things like browser history and the device's screen.

2. **DOCUMENT OBJECT MODEL** The Document Object Model uses objects to create a representation of the current page. It creates a new object for each element (and each individual section of text) within the page.

3. **GLOBAL JAVASCRIPT OBJECTS** The global JavaScript objects represent things that the JavaScript language needs to create a model
of. For example, there is an object that deals only with dates and times.



###### DATA TYPES REVISITED 
1. String
2. Boolean
3. Number
4. null
5. object
6. undefined


###### GLOBAL OBJECTS: MATH OBJECT
Method | DESCRIPTION
-------|------
Math.PI | Returns pi (approximately 3.14159265359)
Math.round() | Rounds number to the nearest integer
Math.sqrt(n)| Returns square root of positive number, e.g., Math. sqrt (9) returns 3
Math.cei1() |Rounds number up to the nearest integer
Math.floor() | Rounds number down to the nearest integer
Math.random() | Generates a random number between 0 (inclusive) and 1 (not inclusive)

###### GLOBAL OBJECTS: DATE OBJECT (AND TIME)

METHOD | DESCRIPTION
-------|--------
getDate() setDate() |Returns I sets the day of the month (1-31).

getDay()  |Returns the day of the week (0-6).
getFulYear() setFullYear() | Returns I sets the year (4 digits)
getHours() setHours() |Returns I sets the hour (0-23)
getMi11iseconds() setMi11iseconds() |Returns I sets the milliseconds (0-999)
getMinutes() setMinutes() |Returns I sets the minutes (0-59)
getMonth()) setMonth() | Returns/ sets the month (0-11)
getSeconds() setSeconds() | Returns I sets the seconds (0-59) Number of milliseconds since January 1, 1970,
getTime() setTime() |00:00:00 UTC (Coordinated Universal Time)
getTimezoneOffset () | Returns time zone offset in mins for locale
toDateString() |Returns "date" as a human-readable string
toTimeString() |Returns "time" as a human-readable string
to String() | Returns a string representing the specified date


* Functions allow you to group a set of related statements together that represent a single task.
* Functions can take parameters (informatiorJ required to do their job) and may return a value.
* An object is a series of variables and functions that represent something from the world around you.
* In an object, variables are known as properties of the object; functions are known as methods of the object.
* Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
* JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
* Arrays and objects can be used to create complex data sets (and both can contain the other).