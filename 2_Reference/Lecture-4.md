[[Lecture-4#^L1-1]]

[[Lecture-4#^L1-2]]

[[Lecture-4#^L1-3]]

[[Lecture-4#^L1-4]]

[[Lecture-4#^L1-5]]

[[Lecture-4#^L1-6]]

[[Lecture-4#^L1-7]]

[[Lecture-4#^L1-8]]

[[Lecture-4#^L1-9]]

[[Lecture-4#^L1-10]]

[[Lecture-4#^L1-50]]
Comparing Adjacent Values
• Get first input value
•Use while to determine if there are more to check
• Copy input to previous variable
• Get next value into input variable
• Compare input to previous, and output if same
```Python
value = int(input("Enter a value: "))
inputStr = input("Enter a value: ")
while inputStr != "“ :
	previous = value
	value = int(inputStr)
	if value == previous :
		print("Duplicate input")
	inputStr = input("Enter a value: ")
```

[[Lecture-4#^L1-51]]
Grades Example
••••Open the file:
• Grades.py
Look carefully at the source code.
The maximum possible score is read as user input
• There is a loop to validate the input
The passing grade is computed as 60% of the available points

[[Lecture-4#^L1-52]]
The for Loop

[[Lecture-4#^L1-53]]
The for Loop
•Uses of a for loop:
• The for loop can be used to iterate over the contents of any
container.
• A container is is an object (Like a string) that contains or stores a
collection of elements
• A string is a container that stores the collection of characters in the
string

[[Lecture-4#^L1-54]]
An Example of a for Loop
•••Note an important difference between the while loop and the for loop.
In the while loop, the index variable i is assigned 0, 1, and so on.
In the for loop, the element variable is assigned stateName[0],
stateName[1], and so on.
```Python
stateName = "Virginia"
i = 0
while i < len(stateName) :
	letter = stateName[i]
	print(letter)
i = i + 1
```

```Python
stateName = "Virginia"
for letter in stateName :
	print(letter)
```

[[Lecture-4#^L1-55]]
The for Loop (2)
•Uses of a for loop:
• A for loop can also be used as a count-controlled loop that iterates
over a range of integer values.

```Python
i = 1
while i < 10 :
	print(i)
	i = i + 1
```

```Python
for i in range(1, 10) :
	print(i)
```

[[Lecture-4#^L1-56]]
Syntax of a for Statement (Container)
• Using a for loop to iterate over the contents of a container, an element
at a time.


[[Lecture-4#^L1-57]]

[[Lecture-4#^L1-58]]

[[Lecture-4#^L1-59]]

[[Lecture-4#^L1-60]]