## Syntax error
an error in the syntax. It may be misspelling words, wrong tokens, missing brackets, semicolon, etc.

### Example:
	print("Hello)
The correct one is:
	print("Hello")
## Logic error
 is when a program compiles, doesn't crash, but the answers that it gives are incorrect. The logic, semantics or meaning, conveyed by the code is wrong.

### Example:
You are writing code which supposed to substract 2 entered numbers with each other, but instead of writing c=a-b, you wrote a+b. The code didn't crush but the output value is incorrect, so it's a **logic error**

## Run-time error 
Sometimes you will have a program that compiles fine but breaks when you actually run it.

### Example:
Infinite Loops, incorrect operations with differenet data types
#### Infinite loop
```
a = -1
while a <0:
	do something()
print("It works")
```
This code will be run forever because of the incorrect usage of the condition in the loop.
### Incorrect data types
```
a = int(input("Enter value of a: "))
print(a**2)
```
This code will print the value of square of any number a entered by the user, but it will works only if user inputs correct numbers to change them into integers by **int()** operations. If the user inputs string **int()** operation will crush the code.