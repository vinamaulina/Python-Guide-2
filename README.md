# Python-Guide-2
## Else after For
The else function after for is the priority function in search loops - to provide a program exit when the search is not found. <br>
Example:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/f3cf529d-5742-4a3f-b832-32e2d7e77e87)

## Break
- The break statement is used to stop the iteration process in the for or while statement.
- The break statement stops the loop and then exits, followed by executing the statement after the loop block.
- If you have a nested loop, break will stop the loop according to the level or loop it is in.
- However, if it is placed in a second depth loop, for example, only that loop stops, not the main loop.<br>
Example:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/cbd74f55-72a7-484e-a46f-239d6953fff1)

## Continue
- The continue statement will make the current literacy stop.
- Then move on to the next literacy.
- Ignore statements that are between continue and the end of the loop block. <br>
Example:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/cb3dd72e-61f4-441f-91d3-b20da3bcb9f3)

## While
-	In Python, "while" is used to execute statements as long as the given condition is met or True.
-	The condition can be any expression, and please note that in Python, True includes non-zero values.
-	When the condition becomes False, the program will proceed to the line after the statement block.
-	Remember to increment the limit, or else the loop will continue forever. <br>
Example:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/9cad592f-0979-4c96-a247-d4618d2590cb)

### Else after While
In a while statement, the else block will always be executed when the condition in the while becomes false.<br>
Example:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/b846d32e-8750-4cd8-a4a0-b249e7615b3b)

## List Comprehension
- List comprehension in Python is an easy and compact syntax for creating a list from a string or another list.
- It is a very concise way to create a new list by performing an operation on each item in the existing list.
- List comprehension is considerably faster than processing a list using the for loop. <br>
Example:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/bb82d563-2762-4af4-94e7-84566af7b97b)

Example of list comprehension with conditional expression:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/3da4cf2e-2149-4d87-b2ce-3a49fc565807)

## Function
- In mathematics, a function is a process that relates between an input and an output.
- In Python, apart from these relational functions, functions are also a way to organize code - with the ultimate goal of code being reusable (reusability)
- it is best if the function has only one specific use but can be reused
- common functions are provided by Python
- But we can always define our own functions  

### Defining a Function
- Functions are defined with the keyword def followed by the name of the function and its parameters in brackets ( )
- Optionally, you can add a docstring – a documentation string that explains the context of the function.
- The code block in each function starts with a colon and uses indentation
- The function stops when there is a return [expression] statement that returns [the expression to the caller.
- You can also make a function return no output with return none.<br>
Example:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/3bea69e7-e149-4c1a-a705-b5176e680b71)

Another Example:  
We want to create a function to calculate the area of a triangle.<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/0e173680-519a-4b4d-833d-19e738ba3196)

### Return
The optional return statement symbolizes the return of values ​​from the Function to the calling code.<br>
Example:<br>
![image](https://github.com/vinamaulina/Python-Guide-2/assets/114405502/d00680d5-50ce-4021-a453-2754a1320e15)
