- Python Syntax compared to other programming languages
  * Python uses new lines to complete a command, as opposed to other programming languages which often use semicolons or parentheses.
  * Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-brackets for this purpose.
- Python Install
  * Many PCs and Macs will have python already installed.
  * To check if you have python installed on a Windows PC, search in the start bar for Python or run the following (python --version) on the Command Line.
- Python Indentation
  * Indentation refers to the spaces at the beginning of a code line.
  * Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.
  * Python uses indentation to indicate a block of code.
  * The number of spaces is up to you as a programmer, the most common use is four, but it has to be at least one.
- Python Comments
  * Comments can be used to prevent execution when testing code.
  *  A comment does not have to be text that explains the code, it can also be used to prevent Python from executing code
  * Since Python will ignore string literals that are not assigned to a variable, you can add a multiline string (triple quotes) in your code, and place your comment inside it
  * As long as the string is not assigned to a variable, Python will read the code, but then ignore it, and you have made a multiline comment.
- Python Variables
  * Variables do not need to be declared with any particular type, and can even change type after they have been set.
  * If you want to specify the data type of a variable, this can be done with casting.
  * - Unpack a Collection
  ```
  fruits = ["apple", "banana", "cherry"]
  x, y, z = fruits
  ```
- Output Variables 변수 출력
- Global Variables
```
  x = "awesome"
  def myfunc():
    x = "fantastic"
    print("Python is " + x)
  myfunc()
  print("Python is " + x)
```
- global keyword
```
  x = "awesome"
  def myfunc():
    global x
    x = "fantastic"
  myfunc()
  print("Python is " + x)
```
- Random Number
```
  print(random.randrange(1, 10))
```