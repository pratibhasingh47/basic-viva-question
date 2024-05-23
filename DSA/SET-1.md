<hr>

## Question 1 -> What is Data Structure ?

Data structures are essential components that help organize and store data efficiently in computer memory. They provide a way to manage and manipulate data effectively, enabling faster access, insertion, and deletion operations.
Common data structures include arrays, linked lists, stacks, queues, trees, and graphs , each serving specific purposes based on the requirements of the problem. Understanding data structures is fundamental for designing efficient algorithms and optimizing software performance.

<hr>

## Question 2 -> What are linear and non-linear data Structures ?

***Linear Data Structures***: These structures store data in a sequential order this allowing for easy insertion and deletion operations. Examples include arrays, linked lists, and queues.

***Non-Linear Data Structures***: These structures store data in a hierarchical or interconnected manner this allowing for more complex relationships between data elements. Examples include trees, graphs, and hash tables.

<hr>

## Question 3 -> What are the various operations that can be performed on different Data Structures ?

**Operations on different Data Structure:-**

~ ***Traversing***: Traversing a Data Structure means to visit the element stored in it. It visits data in a systematic manner. This can be done with any type of DS. 
Below is the program to illustrate traversal in an array, stack, queue and linkedlist.

~ ***Searching***: Searching means to find a particular element in the given data-structure. It is considered as successful when the required element is found. Searching is the operation which we can performed on data-structures like array, linked-list, tree, graph, etc.

~ ***Insertion***: It is the operation which we apply on all the data-structures. Insertion means to add an element in the given data structure. The operation of insertion is successful when the required element is added to the required data-structure. It is unsuccessful in some cases when the size of the data structure is full and when there is no space in the data-structure to add any additional element. The insertion has the same name as an insertion in the data-structure as an array, linked-list, graph, tree. In stack, this operation is called Push. In the queue, this operation is called Enqueue.

~ ***Deletion***: It is the operation which we apply on all the data-structures. Deletion means to delete an element in the given data structure. The operation of deletion is successful when the required element is deleted from the data structure. The deletion has the same name as a deletion in the data-structure as an array, linked-list, graph, tree, etc. In stack, this operation is called Pop. In Queue this operation is called Dequeue.

<hr>

## Question 4 -> How is an Array different from Linked List ?

***Array***: Arrays store elements in contiguous memory locations, resulting in easily calculable addresses for the elements stored and this allows faster access to an element at a specific index.

***Linked List***: Linked lists are less rigid in their storage structure and elements are usually not stored in contiguous locations, hence they need to be stored with additional tags giving a reference to the next element. 

<img src='./images/img1.png' height=240px width='auto'>

<hr>

## Question 5 -> What is Stack and where it can be used ? 

A stack is a linear data structure in which the insertion of a new element and removal of an existing element takes place at the same end represented as the top of the stack.

Applications of Stack:-
* Infix to Postfix Conversion using Stack.
* Evaluation of Postfix Expression
* Reverse a String using Stack.
* Implement two stacks in an array
* Check for balanced parentheses in an expression. 


<hr>

## Question 6 -> What is a Queue, how it is different from the stack and how is it implemented? 

***Stack***: A stack is a linear data structure in which elements can be inserted and deleted only from one side of the list, called the top. A stack follows the LIFO (Last In First Out) principle, i.e., the element inserted at the last is the first element to come out. The insertion of an element into the stack is called push operation, and the deletion of an element from the stack is called pop operation. In stack, we always keep track of the last element present in the list with a pointer called top.

***Queue***  It is a linear data structure in which elements can be inserted only from one side of the list called rear, and the elements can be deleted only from the other side called the front. The queue data structure follows the FIFO (First In First Out) principle, i.e. the element inserted at first in the list, is the first element to be removed from the list. The insertion of an element in a queue is called an enqueue operation and the deletion of an element is called a dequeue operation. In queue, we always maintain two pointers, one pointing to the element which was inserted at the first and still present in the list with the front pointer and the second pointer pointing to the element inserted at the last with the rear pointer.

Applications of stack:
* Some CPUs have their entire assembly language based on the concept of performing operations on registers that are stored in a stack.
* Stack structure is used in the C++ run-time system.

Applications of queue:
* Queue data structure is implemented in the hardware microinstructions inside a CPU.
* Queue structure is used in most operating systems.

<hr>

## Question 5 -> What is Infix, prefix, Postfix notations?

**Infix** notation is easy to read and understand for humans, but it can be difficult for computers to evaluate efficiently. This is because the order of operations must be taken into account, and parentheses can be used to override the default order of operations.

In **prefix** notation, the operator is written first, followed by its operands. For example, the infix expression “a + b” would be written as “+ a b” in prefix notation.

In **postfix** notation, operands are written first, followed by the operator. For example, the infix expression “5 + 2” would be written as “5 2 +” in postfix notation.


<hr>

## Question 5 -> What is a Linked List and What are its types? 

A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers. In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list. 

Types Of Linked List:
* Singly Linked List - 
It is the simplest type of linked list in which every node contains some data and a pointer to the next node of the same data type. 

*  Doubly Linked List - 
A doubly linked list or a two-way linked list is a more complex type of linked list that contains a pointer to the next as well as the previous node in sequence. 

*  Circular Linked List -
A circular linked list is that in which the last node contains the pointer to the first node of the list. 

*  Doubly Circular linked list -
<!-- A Doubly Circular linked list or a circular two-way linked list is a more complex type of linked list that contains a pointer to the next as well as the previous node in the sequence. The difference between the doubly linked and circular doubly list is the same as that between a singly linked list and a circular linked list. The circular doubly linked list does not contain null in the previous field of the first node -->

* Header Linked List - 
<!-- A header linked list is a special type of linked list that contains a header node at the beginning of the list.  -->