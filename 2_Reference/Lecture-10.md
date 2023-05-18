
[[Lecture-10#^L10-1]]
* 
^L10-1

[[Lecture-10#^L10-2]]
* 
^L10-2

[[Lecture-10#^L10-3]]
* 
^L10-3

[[Lecture-10#^L10-4]]
* 
^L10-4

[[Lecture-10#^L10-5]]
* 
^L10-5

[[Lecture-10#^L10-6]]
* 
^L10-6

[[Lecture-10#^L10-7]]
* 
^L10-7

[[Lecture-10#^L10-8]]
* 
^L10-8

[[Lecture-10#^L10-9]]
* 
^L10-9


[[Lecture-10#^L10-10]]
* 
^L10-10

[[Lecture-10#^L10-11]]
* 
^L10-11

[[Lecture-10#^L10-12]]
* 
^L10-12

[[Lecture-10#^L10-13]]
* 
^L10-13

[[Lecture-10#^L10-14]]
* 
^L10-14

[[Lecture-10#^L10-15]]
* 
^L10-15

[[Lecture-10#^L10-16]]
* 
^L10-16

[[Lecture-10#^L10-17]]
* 
^L10-17

[[Lecture-10#^L10-18]]
* 
^L10-18

[[Lecture-10#^L10-19]]
* 
^L10-19

[[Lecture-10#^L10-20]]
* 
^L10-20

[[Lecture-10#^L10-21]]
* 
^L10-21

[[Lecture-10#^L10-22]]
* 
^L10-22

[[Lecture-10#^L10-23]]
* 
^L10-23

[[Lecture-10#^L10-24]]
* 
^L10-24

[[Lecture-10#^L10-25]]
* 
^L10-25

[[Lecture-10#^L10-26]]
* 
^L10-26

[[Lecture-10#^L10-27]]
* 
^L10-27

[[Lecture-10#^L10-28]]
* 
^L10-28

[[Lecture-10#^L10-29]]
* 
^L10-29

[[Lecture-10#^L10-30]]
* 
^L10-30

[[Lecture-10#^L10-31]]
* 
^L10-31

[[Lecture-10#^L10-32]]
* 
^L10-32

[[Lecture-10#^L10-33]]
* 
^L10-33

[[Lecture-10#^L10-34]]
* 
^L10-34

[[Lecture-10#^L10-35]]
* 
^L10-35

[[Lecture-10#^L10-36]]
* 
^L10-36

[[Lecture-10#^L10-37]]
* 
^L10-37

[[Lecture-10#^L10-38]]
* 
^L10-38

[[Lecture-10#^L10-39]]
* 
^L10-39

[[Lecture-10#^L10-40]]
* 
^L10-40

[[Lecture-10#^L10-41]]
* 
^L10-41

[[Lecture-10#^L10-42]]
* 
^L10-42

[[Lecture-10#^L10-43]]
* 
^L10-43

[[Lecture-10#^L10-44]]
* 
^L10-44

[[Lecture-10#^L10-45]]
* 
^L10-45

[[Lecture-10#^L10-46]]
* 
^L10-46

[[Lecture-10#^L10-47]]
* 
^L10-47

[[Lecture-10#^L10-48]]
* 
^L10-48

[[Lecture-10#^L10-49]]
* 
^L10-49

[[Lecture-10#^L10-50]]
* 
^L10-50

[[Lecture-10#^L10-51]]
* 
^L10-51

[[Lecture-10#^L10-52]]
* 
^L10-52

[[Lecture-10#^L10-53]]
* 
^L10-53

[[Lecture-10#^L10-54]]
* 
^L10-54

[[Lecture-10#^L10-55]]
* 
^L10-55

[[Lecture-10#^L10-56]]
* 
^L10-56

[[Lecture-10#^L10-57]]
* 
^L10-57

[[Lecture-10#^L10-58]]
* 
^L10-58

[[Lecture-10#^L10-59]]
* 
^L10-59

[[Lecture-10#^L10-60]]
* 
^L10-60

[[Lecture-10#^L10-61]]
* 
^L10-61

[[Lecture-10#^L10-62]]
* 
^L10-62

[[Lecture-10#^L10-63]]
* 
^L10-63

[[Lecture-10#^L10-64]]
* 
^L10-64

[[Lecture-10#^L10-65]]
* 
^L10-65

[[Lecture-10#^L10-66]]
* 
^L10-66

[[Lecture-10#^L10-67]]
* 
^L10-67

[[Lecture-10#^L10-68]]
* 
^L10-68

[[Lecture-10#^L10-69]]
* 
^L10-69

[[Lecture-10#^L10-70]]
* 
^L10-70

[[Lecture-10#^L10-71]]
* 
^L10-71

[[Lecture-10#^L10-72]]
* 
^L10-72

[[Lecture-10#^L10-73]]
* 
^L10-73

[[Lecture-10#^L10-74]]
* 
^L10-74

[[Lecture-10#^L10-75]]
* 
^L10-75

[[Lecture-10#^L10-76]]
* 
^L10-76

[[Lecture-10#^L10-77]]
* Summary: Inheritance
	* A subclass inherits data and behavior from a superclass.
	* You can always use a subclass object in place of a superclass object.
	* A subclass inherits all methods that it does not override.
	* A subclass can override a superclass method by providing a new implementation.
	* In Python a class name inside parentheses in the class header indicates that a class inherits from a superclass.
^L10-77

[[Lecture-10#^L10-78]]
* Summary: Overriding Methods
	* An overriding method can extend or replace the functionality of the superclass method.
	* Use the reserved word super to call a superclass method.
	* To call a superclass constructor, use the super reserved word before the subclass defines its own instance variables.
	* The constructor of a subclass can pass arguments to a superclass constructor, using the reserved word super.
^L10-78

[[Lecture-10#^L10-79]]
* Summary: Polymorphism
	* A subclass reference can be used when a superclass reference is expected.
	* Polymorphism (“having multiple shapes”) allows us to manipulate objects that share a set of tasks, even though the tasks are executed in different ways.
	* An abstract method is a method whose implementation is not specified.
^L10-79

[[Lecture-10#^L10-80]]
* Summary: Use Inheritance for Designing a Hierarchy of Shapes
	* The GeometricShape class provides methods that are common to all shapes.
	* Each subclass of GeometricShape must override the draw() method.
	* A shape class constructor must initialize the coordinates of its upper-left corner.
	* Each shape subclass must override the methods for computing the width and height.
	* A Group contains shapes that are drawn and moved together.
^L10-80

