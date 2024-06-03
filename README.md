# 100daysofpython
a udemy python course

## Section 1: Day 1 - Beginner - Working with Variables in Python to Manage Data
**Learning Outcomes:**
  - print() function
  - input() function
  - Variables
  - New Lines, Strinbg Manipulation
  - Debugging

### Printing & String Manipulation

`print()` - used to show the text or values you specify inside the parentheses. It's a way for your program to communicate with you by showing messages, numbers, or other information

e.g. `print("Hello World!")`  

#### Quotations
You can use different types of quotation marks, escape characters, or even triple quotes. Here are some common ways to include  quotations within a string:

**Ways to show quotations within a string in Python**

* Using different types of quotation marks
If your string is enclosed in double quotes, you can include single quotes inside it without any special treatment, and vice versa.
`print("A 'single quote' inside a double quote")`
`print('A "double quote" inside a single quote')`

* Using Escape Characters
You can use the backslash \ to escape quotation marks within a string.
- `print("Alternatively you can just \"escape\" the quote")`
- `print('Alternatively you can just \'escape\' the quote')`

* Using Triple Quotes
Triple quotes (either ''' or """) allow you to include both single and double quotes without escaping them. Triple quotes are also useful for multi-line strings.

`print("""He said, "Hello!" and she replied, 'Hi there!'""")`
`print('''He said, "Hello!" and she replied, 'Hi there!' ''')`

*Combining Methods
You can combine different methods for more complex strings.

`print("He said, \"It's a great day!\"")`
`print('She replied, "Yes, it\'s wonderful!"')`

**Summary**

- Escape Characters: Required when using the same type of quote inside a string (e.g., double quotes inside double quotes).
- Mixing Quotes: Use different types of quotes to avoid the need for escape characters.
- Triple Quotes: Useful for including both single and double quotes without escaping and for multi-line strings.

#### Spacing & New Lines
`print("Hello" + " " + "Blue"`

`\n` - represents a newline character. It is used to move the cursor to the next line when printing text. Here's a simple breakdown:

* What \n Does: When Python encounters \n within a string, it moves the cursor to the beginning of the next line before continuing to display text.
* When to Use \n:
*     To format the output of text to make iut easier to read.
*     To print multiple lines of text and separate them.

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


