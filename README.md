# Python-Basic-Assignment  
  
  **_Solutions are available in Jupyter notebook files in the repository_**  
  
  
## Assignment 1 Questions

1. In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.  
```
*  
"hello"  
-87.8  
-  
/  
+	 
6  
```
2. What is the difference between string and variable?  
3. Describe three different data types.  
4. What is an expression made up of? What do all expressions do?  
5. This assignment statements, like `spam = 10`. What is the difference between an expression and a statement?  
6. After running the following code, what does the variable bacon contain?  
`bacon = 22`  
`bacon + 1`  
7. What should the values of the following two terms be?  
```"spam" + "spamspam"```  
```"spam" * 3```  
8. Why is eggs a valid variable name while 100 is invalid?  
9. What three functions can be used to get the integer, floating-point number, or string version of a value?  
10. Why does this expression cause an error? How can you fix it?  
```"I have eaten " + 99 + " burritos."```  

## Assignment 2 Questions  

1.What are the two values of the Boolean data type? How do you write them?  
2. What are the three different types of Boolean operators?  
3. Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean values for the operator and what it evaluate ).  
4. What are the values of the following expressions?  
```(5 > 4) and (3 == 5)```  
```not (5 > 4)```  
```(5 > 4) or (3 == 5)```  
```not ((5 > 4) or (3 == 5))```  
```(True and True) and (True == False)```  
```(not False) or (not True)```  
5. What are the six comparison operators?  
6. How do you tell the difference between the equal to and assignment operators?Describe a condition and when you would use one.  
7. Identify the three blocks in this code:  
```
spam = 0
if spam == 10:  
    print("eggs")  
if spam > 5:  
    print("bacon")  
else:  
    print("ham")  
    print("spam")  
    print("spam")
```  
8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints Greetings! if anything else is stored in spam.  
9. If your programme is stuck in an endless loop, what keys you’ll press?  
10. How can you tell the difference between break and continue?  
11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?  
12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent program that prints the numbers 1 to 10 using a while loop.  
13. If you had a function named bacon() inside a module named spam, how would you call it after importing spam?  

## Assignment 3 Questions

1. Why are functions advantageous to have in your programs?  
2. When does the code in a function run: when it's specified or when it's called?  
3. What statement creates a function?  
4. What is the difference between a function and a function call?  
5. How many global scopes are there in a Python program? How many local scopes?  
6. What happens to variables in a local scope when the function call returns?  
7. What is the concept of a return value? Is it possible to have a return value in an expression?  
8. If a function does not have a return statement, what is the return value of a call to that function?  
9. How do you make a function variable refer to the global variable?  
10. What is the data type of None?  
11. What does the sentence import areallyourpetsnamederic do?  
12. If you had a `bacon()` feature in a spam module, what would you call it after importing spam?  
13. What can you do to save a programme from crashing if it encounters an error?  
14. What is the purpose of the try clause? What is the purpose of the except clause?  

## Assignment 4 Questions

1. What exactly is []?  
2. In a list of values stored in a variable called spam, how would you assign the value 'hello' as the third value? (Assume `[2, 4, 6, 8, 10]` are in spam.)  

3. What is the value of `spam[int(int("3" * 2) / 11)]`? Let's pretend the spam includes the list `['a', 'b', 'c', 'd']` for the next three queries.  
4. What is the value of `spam[-1]`?  
5. What is the value of `spam[:2]`?  
 
6. What is the value of `bacon.index("cat")`? Let's pretend bacon has the list `[3.14, "cat", 11, "cat", True]` for the next three questions.  
7. How does `bacon.append(99)` change the look of the list value in bacon?  
8. How does `bacon.remove("cat")` change the look of the list in bacon?  

10. What are the list concatenation and list replication operators?  
11. What is difference between the list methods append() and insert()?  
12. What are the two methods for removing items from a list?  
13. Describe how list values and string values are identical.  
14. What's the difference between tuples and lists?  
15. How do you type a tuple value that only contains the integer 42?  
16. How do you get a list value's tuple form? How do you get a tuple value's list form?  
17. Variables that "contain" list values are not necessarily lists themselves. Instead, what do they contain?  
18. How do you distinguish between `copy.copy()` and `copy.deepcopy()`?

## Assignment 5 Questions

1. What does an empty dictionary's code look like?  
2. What is the value of a dictionary value with the key `"foo"` and the value `42`?  
3. What is the most significant distinction between a dictionary and a list?  
4. What happens if you try to access `spam['foo']` if spam is `{'bar': 100}`?  
5. If a dictionary is stored in `spam`, what is the difference between the expressions `'cat' in spam` and `'cat' in spam.keys()`?  
6. If a dictionary is stored in `spam`, what is the difference between the expressions `'cat' in spam` and `'cat' in spam.values()`?  
7. What is a shortcut for the following code?  
```
if 'color' not in spam:
    spam['color'] = 'black'
```  
8. How do you `"pretty print"` dictionary values using which module and function?  

## Assignment 6 Questions

1. What are escape characters, and how do you use them?  
2. What do the escape characters `n` and `t` stand for?  
3. What is the way to include backslash characters in a string?  
4. The string `"Howl's Moving Castle"` is a correct value. Why isn't the single quote character in the word Howl's not escaped a problem?  
5. How do you write a string of newlines if you don't want to use the `n` character?  
6. What are the values of the given expressions?  
```
'Hello, world!'[1]
'Hello, world!'[0:5]
'Hello, world!'[:5]
'Hello, world!'[3:]
```  
7. What are the values of the following expressions?  
```
'Hello'.upper()
'Hello'.upper().isupper()
'Hello'.upper().lower()
```  
8. What are the values of the following expressions?  
`'Remember, remember, the fifth of July.'.split()`  
`'-'.join('There can only one.'.split())`  
9. What are the methods for right-justifying, left-justifying, and centering a string?  
10. What is the best way to remove whitespace characters from the start or end?  









