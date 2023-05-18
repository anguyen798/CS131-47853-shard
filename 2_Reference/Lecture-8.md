
[[Lecture-8#^L8-1]]
* 
^L8-1

[[Lecture-8#^L8-2]]
* 
^L8-2

[[Lecture-8#^L8-3]]
* 
^L8-3

[[Lecture-8#^L8-4]]
* 
^L8-4

[[Lecture-8#^L8-5]]
* 
^L8-5

[[Lecture-8#^L8-6]]
* 
^L8-6

[[Lecture-8#^L8-7]]
* Creating and Using Sets
	* To create a set with initial elements, you can specify the elements enclosed in braces, just like in mathematics:
		* `cast = { "Luigi", "Gumbys", "Spiny" }`
	* Alternatively, you can use the set() function to convert any sequence into a set:
		* `names = ["Luigi", "Gumbys", "Spiny"]
		* `cast = set(names)`

^L8-7

[[Lecture-8#^L8-8]]
* 
^L8-8

[[Lecture-8#^L8-9]]
* 
^L8-9


[[Lecture-8#^L8-10]]
* 
^L8-10

[[Lecture-8#^L8-11]]
* 
^L8-11

[[Lecture-8#^L8-12]]
* 
^L8-12

[[Lecture-8#^L8-13]]
* Adding Elements
	* Sets are mutable collections, so you can add elements by using the add() method:
		* `cast = set(["Luigi", "Gumbys", "Spiny"])`
		* `cast.add("Arthur")`
		* `cast.add("Spiny")`
	* Output:
		* `{"Luigi", "Gumbys", "Spiny", "Arthur"`
^L8-13

[[Lecture-8#^L8-14]]
* Removing Elements: discard()
	* The discard() method removes an element if the element exists:
		* `cast.discard("Arthur")`
	*  It has no effect if the given element is not a member of the set:
		* `cast.discard("The Colonel") - has no effect`
^L8-14

[[Lecture-8#^L8-15]]
* 
^L8-15

[[Lecture-8#^L8-16]]
* 
^L8-16

[[Lecture-8#^L8-17]]
* 
^L8-17

[[Lecture-8#^L8-18]]
* 
^L8-18

[[Lecture-8#^L8-19]]
* 
^L8-19

[[Lecture-8#^L8-20]]
* 
^L8-20

[[Lecture-8#^L8-21]]
* 
^L8-21

[[Lecture-8#^L8-22]]
* 
^L8-22

[[Lecture-8#^L8-23]]
* 
^L8-23

[[Lecture-8#^L8-24]]
* 
^L8-24

[[Lecture-8#^L8-25]]
* 
^L8-25

[[Lecture-8#^L8-26]]
* 
^L8-26

[[Lecture-8#^L8-27]]
* 
^L8-27

[[Lecture-8#^L8-28]]
* 
^L8-28

[[Lecture-8#^L8-29]]
* 
^L8-29

[[Lecture-8#^L8-30]]
* 
^L8-30

[[Lecture-8#^L8-31]]
* 
^L8-31

[[Lecture-8#^L8-32]]
* 
^L8-32

[[Lecture-8#^L8-33]]
* 
^L8-33

[[Lecture-8#^L8-34]]
* 
^L8-34

[[Lecture-8#^L8-35]]
* 
^L8-35

[[Lecture-8#^L8-36]]
* 
^L8-36

[[Lecture-8#^L8-37]]
* 
^L8-37

[[Lecture-8#^L8-38]]
* Dictionaries
	* A dictionary is a container that keeps associations between keys and values
	* Every key in the dictionary has an associated value
	* Keys are unique, but a value may be associated with several keys
	* Example (the mapping between the key and value is indicated by an arrow):
^L8-38

[[Lecture-8#^L8-39]]
* 
^L8-39

[[Lecture-8#^L8-40]]
* 
^L8-40

[[Lecture-8#^L8-41]]
* 
^L8-41

[[Lecture-8#^L8-42]]
* 
^L8-42

[[Lecture-8#^L8-43]]
* Accessing Dictionary Values []
	* The subscript operator [] is used to return the value associated with a key
	* The statement
```Python
print("Fred's number is", contacts["Fred"])
```
* Note that the dictionary is not a sequence-type container like a list.
	* You cannot access the items by index or position
	* A value can only be accessed using its associated key
	* `The key supplied to the subscript operator must be a valid key in the dictionary or a KeyError exception will be raised`
^L8-43

[[Lecture-8#^L8-44]]
* 
^L8-44

[[Lecture-8#^L8-45]]
* 
^L8-45

[[Lecture-8#^L8-46]]
* 
^L8-46

[[Lecture-8#^L8-47]]
* 
^L8-47

[[Lecture-8#^L8-48]]
* 
^L8-48

[[Lecture-8#^L8-49]]
* 
^L8-49

[[Lecture-8#^L8-50]]
* 
^L8-50

[[Lecture-8#^L8-51]]
* 
^L8-51

[[Lecture-8#^L8-52]]
* 
^L8-52

[[Lecture-8#^L8-53]]
* 
^L8-53

[[Lecture-8#^L8-54]]
* 
^L8-54

[[Lecture-8#^L8-55]]
* 
^L8-55

[[Lecture-8#^L8-56]]
* 
^L8-56

[[Lecture-8#^L8-57]]
* Common Dictionary Operations (1)
```Python
d = dict()
d = dict(c)
```
* Creates a new empty dictionary or a duplicate copy of dictionary c.

```Python
d = {}
d = {k1: v1, k2: v2, ..., kn: vn}
```
* Creates a new empty dictionary or a dictionary that contains the initial items provided. Each item consists of a key (k) and a value(v) separated by a colon.

```Python
len(d)
```
* Returns the number of items in dictionary d.

```Python
key in d
key not in d
```
* Determines if the key is in the dictionary

```Python
d[key] = value
```
* Adds a new key/value item to the dictionary if the key does not exist. If the key does exist, it modifies the value associated with the key.

```Python
x = d[key]
```
* Returns the value associated with the given key. The key must exist or an exception is raised.

^L8-57

[[Lecture-8#^L8-58]]
* 
^L8-58

[[Lecture-8#^L8-59]]
* 
^L8-59

[[Lecture-8#^L8-60]]
* 
^L8-60

[[Lecture-8#^L8-61]]
* 
^L8-61

[[Lecture-8#^L8-62]]
* 
^L8-62

[[Lecture-8#^L8-63]]
* 
^L8-63

[[Lecture-8#^L8-64]]
* 
^L8-64

[[Lecture-8#^L8-65]]
* 
^L8-65

[[Lecture-8#^L8-66]]
* 
^L8-66

[[Lecture-8#^L8-67]]
* 
^L8-67

[[Lecture-8#^L8-68]]
* 
^L8-68

[[Lecture-8#^L8-69]]
* 
^L8-69

[[Lecture-8#^L8-70]]
* 
^L8-70

[[Lecture-8#^L8-71]]
* 
^L8-71

[[Lecture-8#^L8-72]]
* 
^L8-72

[[Lecture-8#^L8-73]]
* 
^L8-73

[[Lecture-8#^L8-74]]
* 
^L8-74

[[Lecture-8#^L8-75]]
* 
^L8-75

[[Lecture-8#^L8-76]]
* 
^L8-76

[[Lecture-8#^L8-77]]
* 
^L8-77

[[Lecture-8#^L8-78]]
* 
^L8-78

[[Lecture-8#^L8-79]]
* 
^L8-79

[[Lecture-8#^L8-80]]
* 
^L8-80

[[Lecture-8#^L8-81]]
* 
^L8-81

[[Lecture-8#^L8-82]]
* 
^L8-82

[[Lecture-8#^L8-83]]
* 
^L8-83

[[Lecture-8#^L8-84]]
* 
^L8-84

[[Lecture-8#^L8-85]]
* 
^L8-85

[[Lecture-8#^L8-86]]
* 
^L8-86

[[Lecture-8#^L8-87]]
* 
^L8-87

[[Lecture-8#^L8-88]]
* 
^L8-88

[[Lecture-8#^L8-89]]
* 
^L8-89

[[Lecture-8#^L8-90]]
* 
^L8-90

[[Lecture-8#^L8-91]]
* 
^L8-91

[[Lecture-8#^L8-92]]
* 
^L8-92

[[Lecture-8#^L8-93]]
* 
^L8-93

[[Lecture-8#^L8-94]]
* 
^L8-94

[[Lecture-8#^L8-95]]
* 
^L8-95

[[Lecture-8#^L8-96]]
* 
^L8-96

[[Lecture-8#^L8-97]]
* 
^L8-97

[[Lecture-8#^L8-98]]
* 
^L8-98

[[Lecture-8#^L8-99]]
* 
^L8-99

[[Lecture-8#^L8-100]]
* 
^L8-100

[[Lecture-8#^L8-101]]
* 
^L8-101

[[Lecture-8#^L8-102]]
* 
^L8-102

[[Lecture-8#^L8-103]]
* 
^L8-103

[[Lecture-8#^L8-104]]
* 
^L8-104

[[Lecture-8#^L8-105]]
* 
^L8-105

[[Lecture-8#^L8-106]]
* 
^L8-106

[[Lecture-8#^L8-107]]
* 
^L8-107

[[Lecture-8#^L8-108]]
* 
^L8-108

[[Lecture-8#^L8-109]]
* 
^L8-109

[[Lecture-8#^L8-110]]
* 
^L8-110