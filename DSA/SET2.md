<hr>

## Question 1 -> How to implementa stack using queue ? 

***Using only one queue and make the queue act as a Stack in modified way***

Follow the below steps to implement the idea:- 

* The idea behind this approach is to make one queue and push the first element in it. 
* After the first element, we push the next element and then push the first element again and finally pop the first element. 
* So, according to the FIFO rule of the queue, the second element that was inserted will be at the front and then the first element as it was pushed again later and its first copy was popped out. 
* So, this acts as a Stack and we do this at every step i.e. from the initial element to the second last element, and the last element will be the one that we are inserting and since we will be pushing the initial elements after pushing the last element, our last element becomes the first element.


<hr>

## Question 2 -> How to implement a queue using a stack ?  

***First approach: Making a dequeue operation costly***

- If we implement the Queue using Stack by making a dequeue operation costly means that time complexity in enqueue operation would be O(1) and the time complexity in dequeue operation would be O(n).

- In this case, when we insert the elements in the stack then the elements are added on the top of the stack so it takes O(1) time.

- In case of dequeue operation, we need to consider two stacks named as Stack1 and Stack2. First, we insert the elements in the Stack1 and then we remove all the elements from the Stack1. Once all the elements are popped from the Stack1 then they are added in the Stack2. The topmost element would be popped out from the Stack2 and then all the elements from the Stack2 are moved back to Stack1. Here, dequeue operation is performed two times on the data so time complexity is O(n).

***Second Approach: Making an enqueue operation costly.***

- If we implement the Queue using Stack by making a enqueue operation costly means that time complexity in enqueue operation would be O(n) and the time complexity in dequeue operation would be O(1).

- First, we will consider two stacks named as stack1 and stack2. In case of enqueue operation, first all the elements will be popped from the stack1 and push it into the stack2. Once all the elements from the stack1 are pushed into the stack2, then the new element is added in the stack1. After adding the new element in the stack1, all the element are moved back from stack1 to stack2. Here, the time complexity of enqueue operation would be O(n).

- In stack1, the oldest element would be at the top of the stack, so time taken to perform a dequeue operation would be O(1).


<hr>

## Question 3 -> How to check if a given Binary Tree is BST or not? 

A **Binary Search Tree (BST)** is a node-based binary tree data structure that has the following properties. 

* The left subtree of a node contains only nodes with keys less than the node’s key.
* The right subtree of a node contains only nodes with keys greater than the node’s key.
* Both the left and right subtrees must also be binary search trees.
* Each node (item in the tree) has a distinct key.


<hr>

## Question 4 -> What is linear search and its time complexity ? 

A ***Linear Search*** checks one by one each element of the array, without jumping to any item. It searches the element in the array until a match is found. If the match is found then it returns the index of the item otherwise it returns the -1. The worst-case complexity of the Linear Search Algorithm is O(N), where N is the total number of elements in the list. 


<hr>

## Question 5 -> What is binary search algorithm and its time complexity ? 

***Binary Search Algorithm*** is a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N). 


<hr>

## Question 6 -> Which data structure is used for dictionary and spell checker ?

For a dictionary and spell checker, a commonly used data structure is a **trie** (also known as a prefix tree). 


<hr>

## Question 7 -> Types of trees ? 

* ***Binary tree***: In a binary tree, each node can have a maximum of two children linked to it. Some common types of binary trees include full binary trees, complete binary trees, balanced binary trees, and degenerate or pathological binary trees.

* ***Ternary Tree:*** A Ternary Tree is a tree data structure in which each node has at most three child nodes, usually distinguished as “left”, “mid” and “right”.
  
* ***N-ary Tree or Generic Tree***: Generic trees are a collection of nodes where each node is a data structure that consists of records and a list of references to its children(duplicate references are not allowed).
  

<hr>

## Question 7 -> Application of linkedlist ? 

* ***Binary tree***: In a binary tree, each node can have a maximum of two children linked to it. Some common types of binary trees include full binary trees, complete binary trees, balanced binary trees, and degenerate or pathological binary trees.

* ***Ternary Tree:*** A Ternary Tree is a tree data structure in which each node has at most three child nodes, usually distinguished as “left”, “mid” and “right”.
  
* ***N-ary Tree or Generic Tree***: Generic trees are a collection of nodes where each node is a data structure that consists of records and a list of references to its children(duplicate references are not allowed).
