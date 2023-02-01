This project is a little bit different than the usual projects. The first part is only questions about Python’s specificity like “What would be the result of…”. You should read all documentation first (as usual :)), then take the time to think and brainstorm with your peers about what you think and why. Try to do this without coding anything for a few hours.



Trying examples in the Python interpreter will give you most of the answers without having to think about it. Don’t go this route. First read, then think, then brainstorm together. Only then you can test in the interpreter.



It’s important that you truly understand the reasons behind the answers of all those tasks so that you can apply the same logic to other variables and other variable types.



Note that during interviews for Python positions, you will most likely have to answer to these type of questions.



All your answers should be only one line in a file. No space before or after the answer.

Requirements

Python Scripts

Allowed editors: vi, vim, emacs

All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)

All your files should end with a new line

The first line of all your files should be exactly #!/usr/bin/python3

A README.md file, at the root of the folder of the project, is mandatory

Your code should use the pycodestyle (version 2.8.*)

All your files must be executable

The length of your files will be tested using wc

.txt Answer Files

Only one line

No Shebang

All your files should end with a new line

0. Who am 1?
What function would you use to print the type of an object?
Write the name of the function in the file, without ().

1. Where are you?
How do you get the variable identifier (which is the memory address in the CPython implementation)?
Write the name of the function in the file, without ().

2. right count
In the following code, do a and b point to the same object? Answer with Yes or No.
>>> a = 89
>>> b = 100
3. Right count =
In the following code, do a and b point to the same object? Answer with Yes or No.
>>> a = 89
>>> b = 89

4. Right count =
In the following code, do a and b point to the same object? Answer with Yes or No.
>>> a = 89
>>> b = a

5. Right count =+
In the following code, do a and b point to the same object? Answer with Yes or No.
>>> a = 89
>>> b = a + 1
6. is equal
What do these 3 lines print?
>>> s1 = "Best School"
>>> s2 = s1
>>> print(s1 == s2)

7. Is the same
What do these 3 lines print?
>>> s1 = "Best"
>>> s2 = s1
>>> print(s1 is s2)

8. Is really equal
>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 == s2)

9. Is really the same
What do these 3 lines print?
>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 is s2)

10. And with a list, is it equal
What do these 3 lines print?
>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3] 
>>> print(l1 == l2)

11. And with a list, is it the same

mandatory

Score: 0.0% (Checks completed: 0.0%)

What do these 3 lines print?



>>> l1 = [1, 2, 3]

>>> l2 = [1, 2, 3] 

>>> print(l1 is l2)


11. And with a list, is it the same

mandatory

Score: 0.0% (Checks completed: 0.0%)

What do these 3 lines print?



>>> l1 = [1, 2, 3]

>>> l2 = [1, 2, 3] 

>>> print(l1 is l2)

12. And with a list, is it really equal

mandatory

Score: 0.0% (Checks completed: 0.0%)

What do these 3 lines print?



>>> l1 = [1, 2, 3]

>>> l2 = l1

>>> print(l1 == l2)

13. And with a list, is it really the same

mandatory

Score: 0.0% (Checks completed: 0.0%)

What do these 3 lines print?



>>> l1 = [1, 2, 3]

>>> l2 = l1

>>> print(l1 is l2)

14. List append

mandatory

Score: 0.0% (Checks completed: 0.0%)

What does this script print?



l1 = [1, 2, 3]

l2 = l1

l1.append(4)

print(l2)

15. List add

mandatory

Score: 0.0% (Checks completed: 0.0%)

What does this script print?



l1 = [1, 2, 3]

l2 = l1

l1 = l1 + [4]

print(l2)

16. Integer incrementation

mandatory

Score: 0.0% (Checks completed: 0.0%)

What does this script print?



def increment(n):

    n += 1



a = 1

increment(a)

print(a)

17. List incrementation

mandatory

Score: 0.0% (Checks completed: 0.0%)

What does this script print?



def increment(n):

    n.append(4)



l = [1, 2, 3]

increment(l)

print(l)

18. List assignation

mandatory

Score: 0.0% (Checks completed: 0.0%)

What does this script print?



def assign_value(n, v):

    n = v



l1 = [1, 2, 3]

l2 = [4, 5, 6]

assign_value(l1, l2)

print(l1)

19. Copy a list object

mandatory

Score: 0.0% (Checks completed: 0.0%)

Write a function def copy_list(l): that returns a copy of a list.



The input list can contain any type of objects

Your file should be maximum 3-line long (no documentation needed)

You are not allowed to import any module

20. Tuple or not?

mandatory

Score: 0.0% (Checks completed: 0.0%)

a = ()

Is a a tuple? Answer with Yes or No.


21. Tuple or not?

mandatory

Score: 0.0% (Checks completed: 0.0%)

a = (1, 2)

Is a a tuple? Answer with Yes or No.
22. Tuple or not?

mandatory

Score: 0.0% (Checks completed: 0.0%)

a = (1)

Is a a tuple? Answer with Yes or No.

23. Tuple or not?

mandatory

Score: 0.0% (Checks completed: 0.0%)

a = (1, )

Is a a tuple? Answer with Yes or No.

24. Who I am?

mandatory

Score: 0.0% (Checks completed: 0.0%)

What does this script print?



a = (1)

b = (1)

a is b

Repo:



GitHub repository: alx-higher_level_programming

Directory: 0x09-python-everything_is_object

File: 24-answer.txt

25. Tuple or not

mandatory

Score: 0.0% (Checks completed: 0.0%)

What does this script print?



a = (1, 2)

b = (1, 2)

a is b

26. Empty is not empty

mandatory

Score: 0.0% (Checks completed: 0.0%)

What does this script print?



a = ()

b = ()

a is b

27. Still the same?

mandatory

Score: 0.0% (Checks completed: 0.0%)

>>> id(a)

139926795932424

>>> a

[1, 2, 3, 4]

>>> a = a + [5]

>>> id(a)

Will the last line of this script print 139926795932424? Answer with Yes or No.

28. Same or not?

mandatory

Score: 0.0% (Checks completed: 0.0%)

>>> a

[1, 2, 3]

>>> id (a)

139926795932424

>>> a += [4]

>>> id(a)

Will the last line of this script print 139926795932424? Answer with Yes or No.
