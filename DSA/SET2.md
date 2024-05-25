<hr>

## Question 1 -> How to implementa stack using queue ? 

***Using only one queue and make the queue act as a Stack in modified way***

Follow the below steps to implement the idea: 

* The idea behind this approach is to make one queue and push the first element in it. 
* After the first element, we push the next element and then push the first element again and finally pop the first element. 
* So, according to the FIFO rule of the queue, the second element that was inserted will be at the front and then the first element as it was pushed again later and its first copy was popped out. 
* So, this acts as a Stack and we do this at every step i.e. from the initial element to the second last element, and the last element will be the one that we are inserting and since we will be pushing the initial elements after pushing the last element, our last element becomes the first element.