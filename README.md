# handsOnPython
Here some simple snippets of python as I'm going to start learning Django. The following writting is based on from where I've learnt Python [Tutorials Point](https://www.tutorialspoint.com/python).

During my learning period it seems to me that python is near to C language having some different style of its own. Python code has to write without braces as it uses white spaces to indicate block.

In C when we end a line we use semicolon(;) whereas in python a new line denots end of a line. In some case if it is needed to write two line we have to use backslash(\) which means continuation of the previous line.

single('') and double ("") quotes denote string literals and tripple quotes(""" """) also denotes string literals but it takes multiple lines.

hash(#) for commenting a line and (''' ''') use to comment multiple lines.

## variable declaration

Python don't need to decalre variable type as it does it automatically when we assign a value.

## Python Strings

str = "Python you need to know!"

print str                       prints whole sentence

print str[0]                    prints only first charater

print str[2:5]                  prints from 3rd character to 5th charater

print str[2:]                   prints from 3rd characte to end

print str *2                    prints string two times

print str + "happy journey"     Add this text end of the line

## List and Tuples

 *List and Tuples are almost same and they both print values in the same way as string does. The main difference between List and Tuples is in List data can be updated but in Tuples it doesn't. Tuples works as a read-only type.*
 
 *Tuples are denoted with () whereas List is in []*
 
 ## Python Dictornary

 Python's dictonary is a kind of key value pair colletion. Here are some demonstration of it. 

 ```
lst = {}
lst['one'] = "This is one"
lst[2]     = "This is two"

dict = {'name': 'john','code':123, 'dept': 'sales'}


print lst['one']----------------------> Prints value for 'one' key
print lst[2]--------------------------> Prints value for 2 key
print dict----------------------------> Prints complete dictionary
print dict.keys()---------------------> Prints all the keys
print dict.values() ------------------> Prints all the values
print dict['name'] -------------------> prints John

```

## Python Membership and Identity operator

Membership (in || not in) operator checks whether a value is in a list, tuples or string. and Identity (is not is) operator compare the memory location. 