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