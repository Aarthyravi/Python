# Python 
## Server 
    - Server is a bascially a big computer that stores common data 
## I.D.E
    - Run is a coding environment that is used to check if the program works and for short codes 
    - Developement is also a coding environment that can be saved and you have to run it your self and save it
    -I.D.E. is just diffenent places and environments that you program and code in
## How it is run
    - Python is an interpeter system which means it is run as soon as it is written.
    - There is also compiler which means the program is run after all  the code is written.
## What is Library Function
   -Let us say that I type print("Hello Dad") and then it prints Hello Dad. Originally you have to type multiple codes just to print a text but other people have simplified that since they already programed what the computer should when someone types print and stored it in.
## Big O Notation
   Big O Notation is a mathmatical equation to represent an algorithm. An algorithm is steps for how to solve. Lets say your bff gives you a secret message which you have to decode. The message is eeghdvjw and it comes with a key like e is a and 
   The algorithm is:
   
   Create output locate(Storage)
   For each input string find key
         Get the ouput letter
         Store output letter in output location
   Return output location 
Now we need to put this algorithm in a mathematical equation.  This is how O(2+3n), the 2 represents creating output location and returning output location. The 3n represents :For each input string find key, Get the ouput letter, Store output letter in output location. And the n is for the number of times this is repeated depending on how long the secret message is. Now this is best case since it's efficent and quicker. the worst case is O(26+2+3n) where the 26 represents the computer reading and matching the letters with the key one by on or slowly . The average case is O(13+3n+2)
## Indentation
Indentation is important in python. There will be an error if there is no intentation in the right palce.
## Comments
If typing a note to yourself for later purposes, you use a # such a #lalalal and type what ever you want but using # means you can only type one line. If the comment is sooooooo big and you need multiple lines you use 3 qutations like """lalalala""" this is called docstring.
## Python variables
x = "awesome"
print("Python is " + x)

x = 5
y = 10
print(x + y)

## Python numbers
int - Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length.
float- Float, or "floating point number" is a number, positive or negative, containing one or more decimals.
complex- Complex numbers are written with a "j" as the imaginary part
## String
A string is a set of characters. In python you use quotations for words or letters since it is a way for the computer identify what is an integer and what is a string. ("Jaisree25") The computer takes in the 25 as a string since it is inside the quotes.
## Casting
It is basically specfiying a varible for example there is the number 100.8234 and right now it is a float and you want it to be an integer so you can do:
x = int(100.8234)
print(x)
>>> 100 
## String Literals
a = "Hello, World!"
print(a[1])
Ans: e, this program prints a letter. since I put 1 in the barckests the program prints out the 1st number which is e. If I were to put 0 in the brakests it would print H.

b = "Hello, World!"
print(b[2:5])
Ans.llo, this progarm: Gets the characters from position 2 to position 5 (5 not included)

x = "    Jaisree"
print(x.strip())
Ans. Jaisree
This command removes any spaces in front or the end of a string

d = "Jaisree"
print(len(d))
Ans.7
this command gives the length of the string

h = "Jaisree"
print(h.lower())
Ans. jaisree
This command givies the  string in lower case. Instead of lower, if you type print(h.upper()) then You will get the string in upper case: JAISREE

b =  "Hello from the outside"
print(b.replace("H","J")
Ans. Jello from the outside
This command replaces strings

t = "Jaiwsree"
u = t.split("w")
print(u)
Ans ['Jai', 'sree']
this command splits strings. The w is gone and that is where the string is split

## Python Operators
Arithmetic operators-Arithmetic operators are used with numeric values to perform common mathematical operations
Assignment operators-Assignment operators are used to assign values to variables
Comparison operators-Comparison operators are used to compare two values
Logical operators-Logical operators are used to combine conditional statements
Identity operators- To compare objects if similar. Like x is y, x is not y
Membership operators- helps to see if a sequence is in an object
Bitwise operators-Bitwise operators are used to compare (binary) numbers

## List
There are 4 different catagories of data sets. List is used for data sets that needs to be ordered and changed and this also allows duplicate strings and variables. Index is basicallly a position. So we can acesss the data randomly not in order, you can pull an element from even the middle. We can also change the elements in the data set or list.
