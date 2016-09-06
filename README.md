# Lab 02 -- Chapter 01

## Define the followint terms:
* object-an object is something that has state and behavior.  It is an instance of a class.,
* class-a class is a group of objects that have a like characteristic.  For example, a class could be Animals and some objects in that class would be Cows, Tigers, etc,
* instance-an instance is a concrete occurrence of an oject.  ,
* method-a method is a procedure that is associated with an object.  It defines what the object is doing.,
* signature-a type signature defines the inputs and outputs of a function or a method.,
* parameter-A parameter is  is a special kind of variable, used in a subroutine to refer to one of the pieces of data provided as input to the subroutine.,
* type-a type indicates the possible inputs.  For example, if the type is "int", you can only input integers.,
* state- a state is a technical term for all the stored data,
* source code-source code is computer instructions written in readable computer language.,
* return value- this tells a function to return execution of the program to the calling function, and report the value,
* compiler-The compiler saves the changes made and commits it to the program.

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?

* 0 -int
* "hello" -string
* 101 -int
* -1 -int
* true -boolean
* "33" -string
* 3.1415 -double

## What would you have to do to add a new field, for example one called name, to a circle object?

You would have to add a parameter to the constructor.

## Write the header for a method named send that has one parameter of type String, and does not return a value.

public void send(String mag)


## Write the header for a method named average that has two parameters, both of type int, and returns an int value.

public int average(int num1, int num2)

## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.

It is an object of class Book


## Can an object have several different classes? Discuss.

An object can have several different classes because a class can be a member of another class.  For example, if "car" is in class "Vehicle" and "Vehicle" is in class "Machine", then "car" is in both Vehicle and Machine classes
