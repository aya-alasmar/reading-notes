#### Operators and Loops
##### Comparison and logical operators :
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

##### Loops :
 loops check condition if it's True run the code inside { } if false skip the code inside { } .
   * **FOR** if we have a specific times of times . should determine the counter , the stop condition , update the counter .`for ( var i=0 ; i<5 ; i++){ block of code }`.
   * **While** if we don't know the times of repeating the code and we have a condition ` while(condition){ block of code }`.
   * **Do While** if we need to run the code at least one time and then check the condition `do {block of cade }while(condition)`


