# d3-string-subroutines
d3 String Manipulation Subroutines.

* Takes some repetitive simple string manipulation and encapsulate the details within a subroutine. 
* I prefer to use these subroutines while experimenting to help make my d3 programs more readable
* You may determine that these string subroutines are: 
	* not necessary 
	* may make your program use more memory than desired 
		* since large strings could be passed as arguments. 
	* In this case, 
		* convert back to using normal string manipulation 
			* instead of calling these subroutines to do it for you.

			
			
| Filename | Subroutine | Parameters | Description |
| -------- | ---------- | ---------- | ----------- |
| **string\_append\_sub** | STRING.APPEND | ANYTHING, TO_SOMETHING | Append ANYTHING TO_SOMETHING and RETURN the result in the 2nd parameter.
| **string\_left\_sub** | STRING.LEFT | SOMETHING, HOW.MANY, LEFT.CHARS | Returns the specified number of characters from the beginning of a string. |
| **string\_list\_sub** | STRING.LIST | CURRENT, TOTAL, SEPARATOR, VALUE| Append the SEPARATOR to the VALUE if CURRENT is less than TOTAL. |
| **string\_prepend\_sub** | STRING.PREPEND | ANYTHING, TO_SOMETHING | Prepend ANYTHING TO_SOMETHING and RETURN the result in the 2nd parameter. |
| **string\_right\_sub** | STRING.RIGHT | SOMETHING, HOW.MANY, RIGHT.CHARS| Returns a specified number of characters HOW.MANY from the end of string variable SOMETHING |
| **string\_wrap\_append\_sub** | STRING.WRAP.APPEND | SOMETHING, WITH\_THIS, AFTER\_WHAT | First Wrap SOMETHING WITH_THIS then append it to AFTER\_WHAT |
| **string\_wrap\_prepend\_sub** | STRING.WRAP.PREPEND | SOMETHING,WITH\_THIS, BEFORE\_WHAT| First Wrap SOMETHING WITH_THIS then prepend it to BEFORE\_WHAT |
| **string\_wrap\_sub** | STRING.WRAP | SOMETHING, WITH_THIS, WRAPPED| Wrap SOMETHING WITH_THIS and return the result in the 3rd parameter
