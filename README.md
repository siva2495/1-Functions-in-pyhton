# 1-Functions-in-pyhton
User defined functions
Defining Functions
•	Purpose of functions is to group a particular lines of code that needs to be executed multiple times.
•	The key word def  introduces a function definition and it must be followed by the function name.
Return statement
•	A return statement is used to end the execution of the function call and give the result.
•	The statements after the return statements are not executed
Positional Arrangement
•	Most arguments are identified by their position in the function call. print (a, b) will give different result from print (b, a).
•	Keyword argument: if we are defining the keywords, then we can define them in any order.
•	In python we can not first define key argument and then positional arguments.
•	In python we always define positional arguments before the keyword arguments.
Variable Length Argument
•	Sometimes, we need to more flexibility while defining functions like we don’t know in advance fixed number of arguments.
•	Python allows us to make function call with variable length argument.
•	In the argument use an (*) astrick sigh before the argument.
•	If you have unknown number of keyword arguments, then you use double astrick(**).
Scope of Variables: Local and Global Variables
•	"Scope of Variable" means that part of program where we can access the particular variable.
•	"Local Variable" are those which are defined inside the function and can be only accessed inside that particular function.
•	"Global Variable" are defined outside the function and can be accessed throughout the program.
