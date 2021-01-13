##  Debugging 
* The JavaScript **interpreter** uses the concept of **execution contexts**. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

###### EXECUTION CONTEXT
Every statement in a script lives in one of three execution contexts:
1. **GLOBAL CONTEXT** Code that is in the script, but not in a function. There is only one global context in any page.
2. **FUNCTION CONTEXT** Code that is being run within a function.Each function has its own function context.
3. **EVAL CONTEXT (NOT SHOWN)** Text is executed like code in an internal function called eval()


###### VARIABLE SCOPE
 The first two execution contexts correspond with the notion of scope (which you met on p98):
1. **GLOBAL SCOPE** If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.
2. **FUNCTION-LEVEL SCOPE** When a variable is declared within a function,it can only be used within that function. This is because it has function-level scope.

###### EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity:
1. PREPARE
     * The new scope is created
     * Variables, functions, and arguments are created
     * The value of the this keyword is determined
2. EXECUTE
     * Now it can assign values to variables
     * Reference functions and run their code
     * Execute statements
* Each execution context also creates its own variab1es object. This object contains details of all of the variables, functions, and parameters for that execution context.


###### ERROR OBJECTS
* Error objects can help you find where your mistakes are and browsers have tools to help you read them.

* error object contanin:

PROPERTY | DESCRIPTION
---------|------------
name  |Type of execution
message| Description
fileNumber | Name of the JavaScript file
lineNumber | Line number of error


* There are seven types of built-in error objects in JavaScript. You'll see them on the next two pages:



OBJECT | DESCRIPTION
-------|-----------
Error | Generic error - the other errors are all based upon this error
Syntax Error | Syntax has not been followed
ReferenceError| Tried to reference a variable that is not declared/within scope
TypeError | An unexpected data type that cannot be coerced
Range Error | Numbers not in acceptable range
URI Error |encodeURI ().decodeURI(),and similar methods used incorrectly
EvalError |eval () function used incorrectly


###### HOW TO DEAL WITH ERRORS
1. DEBUG THE SCRIPT TO FIX ERRORS : track down the source of the error, and fix it.

2. HANDLE ERRORS GRACEFULLY :You can handle errors gracefully using try, catch, throw, and finally statements.



###### CONSOLE METHODS 
1. **console.info()** can be used for general information
2. **console.warn()** can be used for warnings
3. **console.error()** can be used to hold errors
4. **console.log**

* Grouping Msgs :

    1. If you want to write a set of related data to the console, you can use the **console.group()** method to group the messages together. You can then expand and contract the results.
    2. When you have finished writing out the results for the group, to indicate the end of the group the **console.groupEnd()** method is used.

* WRITING TABULAR DATA :
     *  **console.table()** method lets you output a table showing(objects, arrays that contain other objects or arrays)

* WRITING ON A CONDITION:
     * **console.assert()** method, you can test if a condition is met, and write to the console only if the expression evaluates to false.


###### HANDLING EXCEPTIONS

1. `TRY` First, you specify the code that you t hink might throw an exception within the try block.If an  exception occurs in this section of code, control is automatically passed to the corresponding catch block. The try clause must be used in this type of error handling code, and it should always have either a catch, finally, or both.If you use a continue, break, or return keyword inside a try, it will go to the finally option.
2. `CATCH` If the try code block throws an exception, catch steps in with an alternative set of code. It has one parameter: the error object. Although it is optional, you are not handling the error if you do not catch an error.
The ability to catch an error can be very helpful if there is an issue on a live website. It lets you tell users that
something has gone wrong (rather than not informing them why the site stopped working).
3. `FINALLY` The contents of the finally code block will run either way - whether the try block succeeded or failed.
It even runs if a return keyword is used in the try or catch block. It is sometimes used to clean up after the previous two clauses. These methods are similar to the .done(), .fail() , and .a1ways() methods in jQuery.
You can nest checks inside each other (place another try inside a catch), but be aware that it can affect performance of a script.



###### DEBUGGING TIPS
1. ANOTHER BROWSER
2. ADD NUMBERS
3. STRIP IT BACK
4. SEARCH
5. CODE PLAYGROUNDS
6. VALIDATION TOOLS




* Debugging is the process of finding errors. It involves a process of deduction.
 * The console helps narrow down the area in which the error is located, so you can try to find the exact error.
* JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.