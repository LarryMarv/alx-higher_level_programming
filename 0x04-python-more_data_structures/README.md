vigation
0x04. Python - More Data Structures: Set, Dictionary
Python
 By: Guillaume
 Weight: 1
 Ongoing second chance project - started Dec 5, 2023 10:00 PM, must end by Dec 8, 2023 10:00 PM
 An auto review will be launched at the deadline
In a nutshell…
Auto QA review: 0.0/139 mandatory & 0.0/48 optional
Altogether:  0.0%
Mandatory: 0.0%
Optional: 0.0%
Calculation:  0.0% + (0.0% * 0.0%)  == 0.0%
Resources
Read or watch:

Data structures
Lambda, filter, reduce and map
Learn to Program 12 Lambda Map Filter Reduce
man or help:

python3
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
Why Python programming is awesome
What are sets and how to use them
What are the most common methods of set and how to use them
When to use sets versus lists
How to iterate into a set
What are dictionaries and how to use them
When to use dictionaries versus lists or sets
What is a key in a dictionary
How to iterate over a dictionary
What is a lambda function
What are the map, reduce and filter functions
Copyright - Plagiarism
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.
Requirements
General
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the pycodestyle (version 2.8.*)
All your files must be executable
The length of your files will be tested using wc
Quiz questions
Question #0
What do these lines print?

>>> a = { 'id': 89, 'name': "John" }
>>> a.get('age')

Not found


89


12


Nothing


‘age’

Question #1
What do these lines print?

>>> for i in ["Hello", "Holberton", "School", 98]:
>>>     print(i, end=" ")

1 2 3 4


Hello Holberton School 98


0 1 2 3

Question #2
What do these lines print?

>>> for i in [1, 2, 3, 4]:
>>>     print(i, end=" ")

0 1 2 3 5


1 2 3


0 1 2 3


1 2 3 4

Question #3
What do these lines print?

>>> for i in range(1, 4):
>>>     print(i, end=" ")

0 1 2 3


1 2 3 4


1 2 3

Question #4
What do these lines print?

>>> a = { 'id': 89, 'name': "John", 'projects': [1, 2, 3, 4] }
>>> a.get('projects')

[1, 2, 3, 4]


[1]


list


Nothing


‘projects’

Question #5
What do these lines print?

>>> for i in [1, 3, 4, 2]:
>>>     print(i, end=" ")

1 2 3 4


1 3 4 2


0 1 2 3


1 3 4 2 0

Question #6
What do these lines print?

>>> a = { 'id': 89, 'name': "John", 'projects': [1, 2, 3, 4], 'friends': [ { 'id': 82, 'name': "Bob" }, { 'id': 83, 'name': "Amy" } ] }
>>> a.get('friends')[-1].get("name")

[ { ‘id’: 82, ‘name’: “Bob” }, { ‘id’: 83, ‘name’: “Amy” } ]


Amy


Bob


Nothing


89

Question #7
What do these lines print?

>>> a = { 'id': 89, 'name': "John" }
>>> a['id']

‘id’


a[‘id’]


89


John


id

Question #8
What do these lines print?

>>> a = { 'id': 89, 'name': "John" }
>>> a.get('id')

‘id’


a[‘id’]


89


John


id

Question #9
What do these lines print?

>>> for i in range(0, 3):
>>>     print(i, end=" ")

0 1 2 3


0 1 2


1 2 3

Question #10
What do these lines print?

>>> a = { 'id': 89, 'name': "John" }
>>> a.get('age', 0)

Nothing


0


‘age’


89

Question #11
What do these lines print?

>>> a = { 'id': 89, 'name': "John", 'projects': [1, 2, 3, 4] }
>>> a.get('projects')[3]

[4]


[1, 2, 3, 4]


3


[3]


4

Please make sure to validate all quiz questions before moving on to project tasks
Copyright © 2023 ALX, All rights reserved.


