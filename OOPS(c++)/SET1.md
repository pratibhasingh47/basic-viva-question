<hr>

## Question 1 -> What is C++ ? What are the advantages of C++ ?

**C++** is a general-purpose programming language and widely used nowadays for competitive programming. It has imperative, object-oriented, and generic programming features. C++ runs on lots of platforms like Windows, Linux, Unix, Mac, etc. But there are the benefits and drawbacks of C++ on the idea of which they will start their new journey of programming. It is one of the oldest and most effective languages that also continues to dominate the realm of programming.

***Advantages of C++:***

* C++ is an object-oriented programming language. It may be a collection of commands, which tell the pc to try to do “something.” This collection of commands is typically called C++ ASCII text files.

* C++ could also be a problem-oriented language that’s much easier to use than the other low-level languages like binary coding. It takes much more space than low-level languages but it’s much easier to understand and learn.

* C++ program has many advantages when it involves programming, All C++ program stand-alone files must use the foremost function to allow the program to start out up and motivate its functions.

* C++ program can support unions and structures that are a mix of stand-alone and put-together files, It uses the standard C++ application mentioned as “.cpp”, C++ uses the reserved library word mentioned as “goto” that’s the same as Java’s continue, or break commands.

* The global data and global functions are used within C++ that aren’t utilized in many other high-level languages within the pc sciences and it is an advantage to the programming languages.

* As C++ doesn’t use the objects, it’s difficult to make the programs that have inheritance data and thus the reformed the programs to contribute to the other data and therefore the programs, it is possible to undertake to the present, however, but is difficult, These inheritance data and programs are mentioned because of the inheritance trees.

* C++ doesn’t support class methods that are faithful away, but class methods are basically functions, and sometimes they’re referred to as functions.

* C++ program uses multi-paradigm programming, Paradigm means the planning of programming, paradigm concerned about the logic, the structure, and procedure of program, C++ program is multi-paradigm means it follows three paradigms Generic, Imperative, Object-Oriented.

* C++ program is useful for low-level programming language and really efficient for general purposes, It offers performance and memory efficiently, It offers high-level abstraction, within the language of the matter domain

* C++ may be a system programming and features a relatively clear and mature standard,

* C++ program supports inline function, C++ supports exception handling, it’s pointer and references, C++ uses cin and cout.

* C++ has a large and mature ecosystem of libraries and frameworks that can be used to accelerate development and simplify tasks like network programming, graphics rendering, and database access.



<hr>

## Question 2 -> What are the different data types present in C++? 

####  **Data Types in C++ are Mainly Divided into 3 Types:**

***1. Primitive Data Types***: These data types are built-in or predefined data types and can be used directly by the user to declare variables. example: int, char, float, bool, etc. Primitive data types available in C++ are: 
* Integer
* Character
* Boolean
* Floating Point
* Double Floating Point
* Valueless or Void
* Wide Character

***2. Derived Data Types***: Derived data types that are derived from the primitive or built-in datatypes are referred to as Derived Data Types. These can be of four types namely: 
* Function
* Array
* Pointer
* Reference

***3. Abstract or User-Defined Data Types***: Abstract or User-Defined data types are defined by the user itself. Like, defining a class in C++ or a structure. C++ provides the following user-defined datatypes:  
* Class
* Structure
* Union
* Enumeration
* Typedef defined Datatype



<hr>

## Question 3 -> What are references in C++ ?

When a variable is declared as a reference, it becomes an alternative name for an existing variable. A variable can be declared as a reference by putting ‘&’ in the declaration. 

Also, we can define a reference variable as a type of variable that can act as a reference to another variable. ‘&’ is used for signifying the address of a variable or any memory. Variables associated with reference variables can be accessed either by its name or by the reference variable associated with it.

***Syntax:*** 
```
data_type &ref = variable;
```


<hr>

## Question 4 -> Define token in C++. 

We have several types of tokens each of which serves a specific purpose in the syntax and semantics of C++. Below are the main types of tokens in C++:

* Identifiers
* Keywords
* Constants
* Strings
* Special Symbols
* Operators


<hr>

## Question 5 -> What do you mean by Call by Value and Call by Reference ? 

**Call by Value in C++**

In the call-by-value method, function arguments are passed by copying the value of the actual parameter, ensuring the original values remain unchanged. The value is copied to the formal parameter.

**Call by Reference in C++**

In the call-by-reference method, the memory address (reference) of the actual parameter is passed to the function, allowing direct access and modification of the original values. The actual and the formal parameters point to the same memory address. Any changes made to the parameters within the function are directly reflected in the original values outside the function.


<hr>

## Question 6 -> What is polymorphism in C++ ? 

The word “polymorphism” means having many forms. In simple words, we can define **polymorphism** as the ability of a message to be displayed in more than one form. A real-life example of polymorphism is a person who at the same time can have different characteristics. A man at the same time is a father, a husband, and an employee. So the same person exhibits different behavior in different situations. This is called polymorphism. Polymorphism is considered one of the important features of Object-Oriented Programming.


<hr>

## Question 7 -> When should we use multiple inheritance ? 

**Multiple inheritance** means that a subclass can inherit from two or more superclasses. C++ allows multiple inheritance, but Java allows only single inheritance, that is, a subclass can inherit only one superclass.

*Multiple inheritance*is useful when a subclass needs to combine multiple contracts and inherit some, or all, of the implementation of those contracts. For example, the AmericanStudent class needs to inherit from both the Student class and the American class. 


<hr>

## Question 8 -> Explain inheritance. And use of inheritance in cpp programming

The capability of a class to derive properties and characteristics from another class is called **Inheritance**. Inheritance is one of the most important features of Object-Oriented Programming. 

Inheritance is a feature or a process in which, new classes are created from the existing classes. When we say derived class inherits the base class, it means, the derived class inherits all the properties of the base class, without changing the properties of base class and may add new features to its own. These new features in the derived class will not affect the base class. The derived class is the specialized class for the base class.

* Sub Class: The class that inherits properties from another class is called Subclass or Derived Class. 
* Super Class: The class whose properties are inherited by a subclass is called Base Class or Superclass. 


<hr>

## Question 9 -> Explain the constructor in C++. 

**Constructor** in C++ is a special method that is invoked automatically at the time of object creation. It is used to initialize the data members of new objects generally. The constructor in C++ has the same name as the class or structure. It constructs the values i.e. provides data for the object which is why it is known as a constructor.

* Constructor is a member function of a class, whose name is the same as the class name.
* Constructor is a special type of member function that is used to initialize the data members for an object of a class automatically when an object of the same class is created.
* Constructor is invoked at the time of object creation. It constructs the values i.e. provides data for the object that is why it is known as a constructor.
* Constructors do not return value, hence they do not have a return type.
* A constructor gets called automatically when we create the object of the class.
* Constructors can be overloaded.
* A constructor can not be declared virtual.


<hr>

## Question 9 -> How many types of constructor ? 

**Constructor** in C++ is a special method that is invoked automatically at the time of object creation. It is used to initialize the data members of new objects generally. The constructor in C++ has the same name as the class or structure. It constructs the values i.e. provides data for the object which is why it is known as a constructor.

* Constructor is a member function of a class, whose name is the same as the class name.
* Constructor is a special type of member function that is used to initialize the data members for an object of a class automatically when an object of the same class is created.
* Constructor is invoked at the time of object creation. It constructs the values i.e. provides data for the object that is why it is known as a constructor.
* Constructors do not return value, hence they do not have a return type.
* A constructor gets called automatically when we create the object of the class.
* Constructors can be overloaded.
* A constructor can not be declared virtual.
