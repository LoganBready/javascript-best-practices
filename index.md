1. Avoid global variables.  Minimize the use of global variables.  Including all data types, ojbects, and functions. Globals can be over written by other scripts.  Use local variables instead.
2. Declarations on Top.  Good practice to put all declarations at the top of each script or function.  Will give cleaner code, provide a place to look for local variables.  Make it easier to avoid global variables.  Reduce the possibility of unwanted re-declarations.
3. Initialize Variables.  It is good coding practice to initialize variables when you declare them.  Gives cleaner code, provide a single place to initialize variables.  Avoid undefined values.
4. Never declare number, string, or boolean objects.  Always treat numbers, strings, or booleans as primitive values.  Not as objects.  Declaring these types as objects, slows down execution speed, and produces nasty side effects. 
5. Use Parameter Defaults.  If a function is called with a missing argument, the value of the missing argument is set to undefined.  Undefined values can break your code.  It is a good habit to assign default values to arguments. 
6. Commment as much as needed but not more than needed.  Comment only what you consider is needed and dont tell your life story.
7. Use shortcut notations.  They will keep your code snappy and easier to read once you get use to it. 
8. Allow for configuration and translation.  Everything that is likely to change in your code should not be scattered th roughout your code. 
9. Recognize and remove duplicated code.  
10. Set default values.  Doing so will ensure the values of each attribute are not undefined. 