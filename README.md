# 100daysofpython
a udemy python course

## Section 1: Day 1 - Beginner - Working with Variables in Python to Manage Data
### Printing & String Manipulation
`print("Hello World!")`

#### Quotations
Three ways to add quote(s) within a string:

- `print("A 'single quote' inside a double quote")` 
- `print('A "double quote" inside a single quote')`
- `print("Alternatively you can just \"escape\" the quote")`

#### Spacing
`print("Hello" + " " + "Blue"`

#### Comments & Undo Changes

- Use the hashtag symbol `#` to make a line of code a comment
- Highlight the code and use keys: `command + \` for mac or `Ctrl + \` for windows

Undo
- Hold down the keys keys: `command + z` for mac or `Ctrl + z` for windows


### Functions
Fucntions can live inside other functions.

### Input Function
`input()` - can bring in the value that's in the input pane

`print(input())` - prints the input

`print("Hello" + " " + input())` - input function runs first, then prints `Hello + the string responding to the input()`

### Integer Function 
`int()` - turn string into integer

### Length Function
`len()` - length of a string

`print(len(input()))` - prints the length of the string in the input

### Variables
`var1` = variable; can be varied; used to store data in assigned variable

`var1 = input("")` - assigns a variable to the input

`print(var1)` - prints the variable

eg. assiging a value to a variable:

```
name = "Blue"
print(name)

name = "Mike"
print(name)

name = input("What is your name? ")
length = len(name)
print(length)
```
In this example, the length of the string "Blue" and "Mike" are printed in that order. 

#### Classic Method for Swapping two Variables

**Input values for a and b**
````
a = input("Enter value for a: ")
b = input("Enter value for b: ")
````
**Display original values**
````
print(f"Original a: {a}, b: {b}")
````
**Swap the values**
````
c = a  # Save the value of a in temporary variable c
a = b  # Assign the value of b to a
b = c  # Assign the saved value (original a) to b
````
**Display swapped values**
````
print(f"Swapped a: {a}, b: {b}")
````
