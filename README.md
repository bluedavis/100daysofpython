# 100daysofpython
a udemy python course

## Section 1: Day 1 - Beginner - Working with Variables in Python to Manage Data
  - print() function
  - input() function
  - Variables
  - New Lines, Strinbg Manipulation
  - Debugging

### Printing & String Manipulation
`print("Hello World!")`

#### Quotations
Three ways to add quote(s) within a string:

- `print("A 'single quote' inside a double quote")` 
- `print('A "double quote" inside a single quote')`
- `print("Alternatively you can just \"escape\" the quote")`

#### Spacing & New Lines
`print("Hello" + " " + "Blue"`

`\n` - new line at the end of a string

#### Comments & Undo Changes

- Use the hashtag symbol `#` to make a line of code a comment
- Highlight the code and use keys: `command + \` for mac or `Ctrl + \` for windows

Undo
- Hold down the keys keys: `command + z` for mac or `Ctrl + z` for windows


### Functions
Fucntions can live inside other functions.

### Input Function
`input()` - a prompt for the user

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
In this example, the variable name has a value of "Blue" and "Mike". When asked to input "What is your name?" the value of name is decided and the length of the string ("Blue" or "Mike") is printed. 

#### Classic Method for Swapping two Variables
Temporary variables are used to remporarily hold the value of one of the variables so that the original value is not lst during the swap process.

**Input values for a and b**
````
a = input("Enter value for a: ")
b = input("Enter value for b: ")
````

**Swap the values**
````
c = a  # Save the value of a in temporary variable c
a = b  # Assign the value of b to a
b = c  # Assign the saved value (original a) to b
````

**Display original and swapped values**
````
print("a: " + a)
print("b: " + b)
````

### f-strings
The `print(f"")` statement in Python is used for **formatted string literals**, also known as **f-strings**. Introduced in Python 3.6, f-strings provide a way to embed expressions inside string literals, using curly braces `{}`.

### Basic Usage 
To create an f-string, you prefix the string with the letter `f` or `F`, followed by a string in double quotes `" "` or single quotes `' '`. Inside the string, you can include variables and expressions within curly braces `{}` that will be evaluated at runtime and formatted into the string.”


