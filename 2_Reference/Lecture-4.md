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


[[Lecture-7#^L7-1]]
* 

[[Lecture-7#^L7-2]]
* 

[[Lecture-7#^L7-3]]
* 

[[Lecture-7#^L7-4]]
* 

[[Lecture-7#^L7-5]]
* 

[[Lecture-7#^L7-6]]
* 

[[Lecture-7#^L7-7]]
* 

[[Lecture-7#^L7-8]]
* 

[[Lecture-7#^L7-9]]
* 


[[Lecture-7#^L7-10]]
* 

[[Lecture-7#^L7-11]]
* 

[[Lecture-7#^L7-12]]
* 

[[Lecture-7#^L7-13]]
* 

[[Lecture-7#^L7-14]]
* 

[[Lecture-7#^L7-15]]
* 

[[Lecture-7#^L7-16]]
* 

[[Lecture-7#^L7-17]]
* 

[[Lecture-7#^L7-18]]
* 

[[Lecture-7#^L7-19]]
* 

[[Lecture-7#^L7-20]]
* 

[[Lecture-7#^L7-21]]
* 

[[Lecture-7#^L7-22]]
* 

[[Lecture-7#^L7-23]]
* 

[[Lecture-7#^L7-24]]
* 

[[Lecture-7#^L7-25]]
* 

[[Lecture-7#^L7-26]]
* 

[[Lecture-7#^L7-27]]
* 

[[Lecture-7#^L7-28]]
* 

[[Lecture-7#^L7-29]]
* 

[[Lecture-7#^L7-30]]
* 

[[Lecture-7#^L7-31]]
* 

[[Lecture-7#^L7-32]]
* 

[[Lecture-7#^L7-33]]
* 

[[Lecture-7#^L7-34]]
* 

[[Lecture-7#^L7-35]]
* 

[[Lecture-7#^L7-36]]
* 

[[Lecture-7#^L7-37]]
* 

[[Lecture-7#^L7-38]]
* 

[[Lecture-7#^L7-39]]
* 

[[Lecture-7#^L7-40]]
* 

[[Lecture-7#^L7-41]]
* 

[[Lecture-7#^L7-42]]
* 

[[Lecture-7#^L7-43]]
* 

[[Lecture-7#^L7-44]]
* 

[[Lecture-7#^L7-45]]
* 

[[Lecture-7#^L7-46]]
* 

[[Lecture-7#^L7-47]]
* 

[[Lecture-7#^L7-48]]
* 

[[Lecture-7#^L7-49]]
* 

[[Lecture-7#^L7-50]]
* 

[[Lecture-7#^L7-51]]
* 

[[Lecture-7#^L7-52]]
* 

[[Lecture-7#^L7-53]]
* 

[[Lecture-7#^L7-54]]
* 

[[Lecture-7#^L7-55]]
* 

[[Lecture-7#^L7-56]]
* 

[[Lecture-7#^L7-57]]
* 

[[Lecture-7#^L7-58]]
* 

[[Lecture-7#^L7-59]]
* 

[[Lecture-7#^L7-60]]
* 

[[Lecture-7#^L7-61]]
* 

[[Lecture-7#^L7-62]]
* 

[[Lecture-7#^L7-63]]
* 

[[Lecture-7#^L7-64]]
* 

[[Lecture-7#^L7-65]]
* 

[[Lecture-7#^L7-66]]
* 

[[Lecture-7#^L7-67]]
* 

[[Lecture-7#^L7-68]]
* 

[[Lecture-7#^L7-69]]
* 

[[Lecture-7#^L7-70]]
* 

[[Lecture-7#^L7-71]]
* 

[[Lecture-7#^L7-72]]
* 

[[Lecture-7#^L7-73]]
* 

[[Lecture-7#^L7-74]]
* 

[[Lecture-7#^L7-75]]
* 

[[Lecture-7#^L7-76]]
* 

[[Lecture-7#^L7-77]]
* 

[[Lecture-7#^L7-78]]
* 

[[Lecture-7#^L7-79]]
* 

[[Lecture-7#^L7-80]]
* 

[[Lecture-7#^L7-81]]
* 

[[Lecture-7#^L7-82]]
* 

[[Lecture-7#^L7-83]]
* 

[[Lecture-7#^L7-84]]
* 

[[Lecture-7#^L7-85]]
* 

[[Lecture-7#^L7-86]]
* 

[[Lecture-7#^L7-87]]
* 

[[Lecture-7#^L7-88]]
* 

[[Lecture-7#^L7-89]]
* 

[[Lecture-7#^L7-90]]
* 

[[Lecture-7#^L7-91]]
* 

[[Lecture-7#^L7-92]]
* 

[[Lecture-7#^L7-93]]
* 

[[Lecture-7#^L7-94]]
* 

[[Lecture-7#^L7-95]]
* 

[[Lecture-7#^L7-96]]
* 

[[Lecture-7#^L7-97]]
* 

[[Lecture-7#^L7-98]]
* 

[[Lecture-7#^L7-99]]
* 

[[Lecture-7#^L7-100]]
* 

[[Lecture-7#^L7-101]]
* 

[[Lecture-7#^L7-102]]
* 

[[Lecture-7#^L7-103]]
* 

[[Lecture-7#^L7-104]]
* 

[[Lecture-7#^L7-105]]
* 

[[Lecture-7#^L7-106]]
* 

[[Lecture-7#^L7-107]]
* 

[[Lecture-7#^L7-108]]
* 

[[Lecture-7#^L7-109]]
* 

[[Lecture-7#^L7-110]]
* 