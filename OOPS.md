# Object Oriented Programming (OOPs) Concept in Java



## Abstract:

 For the growth of software industry in
future and the advance of software engineering, use
of object-oriented programming (OOP) has increased
in the software real world. Some the important
features that's know is compulsory and that's
features are important to study the depth knowledge
of object-oriented programming in this paper, we
study the concept of object-oriented programming
and its features, advantages, disadvantages, and we
also know the constructor and destructors.

</br>

</br>

## I. Introduction:
As the name suggests, Object-Oriented Programming or OOPs refers to languages that uses objects in programming. Object-oriented programming aims to implement real-world entities like inheritance, hiding, polymorphism etc in programming. The main aim of OOP is to bind together the data and the functions that operate on them so that no other part of the code can access this data except that function.



The fundamental concept in OOP is that; a program is
designed around the data being operated. The basic idea
behind object-oriented languages is to combine both
data and functions into a single unit called object. The
power of object- oriented language is that the
programmer can create modular, reusable code. The
flexibility of program increases so programmer is able to
change or replace modules of a program without
disturbing other part of the program. Software
development speed is increase. Programming using
objects; that are close in the representation of real world
objects. By including these some of the fundamental
features of is OOPs are as follows.


OOP is an strategy for writing software in which data
and behaviour are package together as classes whose
instances are objects. A class is a named software
program representation for an abstraction, an
abstraction is a named collection of attributes and
behavior relevant to modeling a given entity for some
particular purpose, an object is a distinct instance of a
given category that is structurally identical to all
different cases of that class. Software code in OOP is
written to define classes, objects, and manipulate these
objects.

</br>

</br>

## II. Features of Object-Oriented Programming:

![This is an image](https://static.javatpoint.com/images/java-oops.png)

### A. Class:
A class is a user defined data type which contains data
members and member function to operate on those data
member. It is a collection of similar kind of objects. A
class is a generic definition of an object. It is a blue print
of an object. Class is an extension of structure used in C
language. In the structure we can combine different data
element as a single entity. In the class we can also
combine different data element as well as member
function. Class is a user defined data type in which we
can declare variables as well as functions. Class is the
very essential part of object-oriented programming. The
class is used to implement encapsulation, data
abstraction, and data hiding.


```
Class class_name
{
Private:

Variable declaration

Function declaration

Public:

Variable declaration

Function declaration
};
```

The class specifies the type and scope of its members.
The keyword class name is an abstract data type. The
body of a class is Class indicates that the name which
follows class name. The enclosed within the curly braces
followed by a semicolon i.e. the end of a class
specification. The body of a class contains declaration of
variables and functions, collectively known as members.
The variables declared inside a class are known as data
members, and functions are known as member functions
These members are generally grouped underneath two
sections, private and public, which define the visibility of
members. Object oriented programming uses modular
programming using this data type called classes.
Defining variables of a class data type is known as class
instantiation or objects.
</br>

</br>

### B. Object:
Objects are basic run time entities in an object-oriented
programming. Each object contains data and code to
manipulate that data. Objects can have interaction
barring having to understand details about the statistics
or code. In structured programming a problem is
approached by using dividing it into functions. Unlike
this, in object-oriented programming the trouble is
divided into objects. Thinking in phrases of objects as a
substitute than functions makes the designing of
program simpler.

For example:

**Int x;**

int is a class and x is an object of that class. From the int
class, we can create several objects (variables). The int
class indicates what kind of data an object of its type can
hold and what operations (addition, subtraction, etc.)
can be performed on this data. A class is thus a
description of number of similar objects. It specifies
what data and what functions will be included in objects
of that class. Instead of standard class like int you can
think of user-defined class like employee from which
objects like, el, e2, e3 can be created through a
statement,

**employee e1, e2, e3;**

Objects basic run type entities of object-oriented
programming. It may represent a person, a bank account
or any item that the program must be handled. A class
specification only declares the structure of objects and it
must be instantiated in order to make use of the services
provided by it. This process of creating objects or class
variables of the class is called class instantiation. Actually
object is variable of class through which we can access
(or handled) the data and members of the class.
Whenever object is created it takes space in memory for
its different members. We can access member using
object similar to the structure in C.
</br>

</br>


### C. Inheritance:

Inheritance is an important pillar of OOP(Object-Oriented Programming). It is the mechanism in java by which one class is allowed to inherit the features(fields and methods) of another class.

Important terminology:

- Super Class: The class whose features are inherited is known as superclass(or a base class or a parent class).
- Sub Class: The class that inherits the other class is known as a subclass(or a derived class, extended class, or child class). The subclass can add its own fields and methods in addition to the superclass fields and methods.
- Reusability: Inheritance supports the concept of “reusability”, i.e. when we want to create a new class and there is already a class that includes some of the code that we want, we can derive our new class from the existing class. By doing this, we are reusing the fields and methods of the existing class.

How to use inheritance in Java

The keyword used for inheritance is extends.
```
Syntax :

class derived-class extends base-class
{
   //methods and fields
}
```
</br>

</br>



### D. Abstraction:
Data abstraction provides the foundation for
object-oriented programming. In addition to providing
fundamental data types, object-oriented programming
languages allow us to define our own data types, called
user-defined or abstract data types. ln the C
programming language, related data items can be
organized into structures. These structures are capable
operate only with data item. In C++, in addition to
supplying this kind of data structure, also enable us to
implement a set of operations that can be applied to the
data elements. The data element and the set of
operations applicable to the data element together shape
the abstract data type.

 To guide data abstraction, a
programming language should supply a assemble that
can be used to encapsulate the data elements and
operations that make up an abstract data type. In C++,
this construct is known as a class. An instance of a class
is called an object. Classes are composed of data
elements called data members (member variables) and
member functions (methods) that define the operations
that can be carried out on the data members. ln one
sentence, the technique of creating new data types that
are well suited to an application to be programmed is
known as data abstraction.

Example -

```
abstract class Shape
{
    int color;

    // An abstract function
    abstract void draw();
}

```

Following are some important observations about abstract classes in Java.

   1. An instance of an abstract class can not be created.
   2. Constructors are allowed.
   3. We can have an abstract class without any abstract method.
   4. Abstract classes can not have final methods because when you make a method final you can not override it but the abstract methods are meant for overriding.
   5. We are not allowed to create object for any abstract class.
   6. We can define static methods in an abstract class.

   </br>

</br>


### E. Polymorphism:
Polymorphism means the ability to take more than one
from. Polymorphism is one of the crucial features of the
object-oriented programming. The word polymorphism
is made up of two Greek words: "poly" and "morphism".
"Poly" means many and "morphism" means forms, so
polymorphism means many forms. In object forms. C++
has four mechanisms that help us to implement oriented
programming way, it simply means one name multiple
polymorphism as Function Overloading, Operator
Overloading, Template and Virtual function.

![This is an image](https://static.javatpoint.com/cpp/images/cpp-polymorphism.png)

</br>

</br>

### F. Encapsulation:
Encapsulation is mechanism that binds the data and
functions together. This mechanism keeps both data and
functions safe from outside interference and misuse. The
advantage of encapsulated code is that user knows how
to access it, there is no need of implementation details. In
C++ points of view encapsulation is class. The purpose of
the class is to encapsulate the complexity and hide the
complexity of implementation inside the class. This
insulation of the data from the direct access by the
programmer is called data hiding. Actually some
information of the object are made hidden from the
outside world so that only the member functions of the
same class can access the hidden data and no one from
outside is allowed to access it. The information hiding is
implemented using the three visibility modes as private,
public and protected.

</br>

</br>

## III. Advantages of OOP:
OOP offers several benefits to the programmers as well
as the user. Some advantages are as follows:
- Security is the first main advantage of OOP. The
data and functions are combined together in the
form of class.
- Using inheritance we can eliminate redundant
code and extend the use of existing class.
- We can build programs from the standard
working modules that communicate with one
another. This leads to saving of development
time and increase high productivity.
- The concept of data hiding helps the
programmer to build secure programs, so that
data of one class will be secure from the other
parts of the program.
- Software complexity can be easily managed.
- Massage passing teaching for communication
Between objects makes the interface description
with the external system much simpler form.

</br>

</br>

## IV. Disadvantages of OOP:

The OOP languages have the following disadvantages.
- The message base communication between
many objects in a complex system is difficult to
trace and debug.
- It requires more memory to process at a great
speed.
- It runs at slower than the traditional
programming languages.
- It works on objects and everything of the real
world is not possible to divide into neat classes
and subclasses.
- The reusability of code is not possible, and it
requires extra overhead to develop a new code
on the basis of the existing code.

</br>

</br>

## V. Constructors:
Constructor is a special member function of a class
which initializes itself when an object of class is created.
It is special function because its name is same as the
class name. The task of the constructor is to initializes
the object of the class. It is called constructor because it
constructor the value of data members. Some time it is
known as dynamic initialization of object. Constructor is
a special member function which enables, an object to
initialize itself when it is created. This is known as
automatic initialization of objects. Whenever we create
an object of the class the constructor is automatically
invoked.

Suppose we have a class with the name integer and
having two private data member m and n. If we want to
initialize m and n, then can define constructor as follows.

```
class integer
{
int m, n;
public:
integer (void); //constructor defined.
};
integer :: integer (void) //constructor body
{
M = 0;
N = 0;
}

```
</br>

</br>

## VI. Destructors:
Destructor is use to destroy the object that have been
created by a Constructor. Like a constructor, the
destructor is a member function whose name as the
same as class name but is preceded by a tiled (). A
Destructor never takes any argument and it does not
return any value. It is invoked implicitly by the compiler
while exit from the program.
Actually destructor clear or clean memory storage i.e. it
Works as a garbage collector. It is good programming
practice to declare destructor to release memory space
for future use.

</br>

</br>

 ## VII. Conclusion:
We have to study in above research paper, what exactly
the object-oriented programming(OOPs) is, there
features and we also study the use of OOPs in future. The
programming languages before OOP system were not
easy to understand. The large code converts into short
code by using this OOPs concept. With the use of feature
like class, objects, encapsulations, polymorphism,
inheritance, and abstraction it can be seen that
development of software is increase by using these
capabilities.

</br>

</br>

## References:
[1] Mr. Rushikesh S. Raut, Research Paper on Object-Oriented Programming (OOP), International Research Journal of Engineering and Technology (IRJET).

(https://www.irjet.net/archives/V7/i10/IRJET-V7I10247.pdf)

[2] Object Oriented Programming (OOPs) Concepts, Geeks for Geeks.

(https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/?ref=lbp)