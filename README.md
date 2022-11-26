# daa-assingment-2
## Problem Statement:

##Implement the optimal binary search tree algorithm and demonstrate three test cases.
##We know that in binary search tree, the nodes in the left subtree have lesser value than the root node and the nodes in the right subtree have greater value than the root node.
##The frequency and key-value determine the overall cost of searching a node.
##There is one way that can reduce the cost of a binary search tree is known as an optimal binary search tree.

##Lets consider an example :
##A Phone Book which have name,contact number and frequency(how many times a particular contact number is called) array.Using these information, we are creating a Tree that will produce minimum cost.
##Here, we have added features like call someone, create new contact.
##When we call someone, the name/number is searched in the OBST and the level is returned in which the name/number is found.Also, this operation increases the frequency of that particular person and a new OBST is created with minimum cost.
##When we create a new contact, name and number is taken and added to the respective arrays. Then,a new OBST is created with frequency of ne
wly added contact as 1.
With 'n' different nodes, we can create ![image](https://user-images.githubusercontent.com/112850551/204069635-be66a278-6bd6-4cc4-b99b-656b6abb1c4b.png)different trees.
Thus, we need to find the Tree whose cost can be minimum and this can be done with Optimal Binary Search Tree.

##Printing the OBST with already present information.
![image](https://user-images.githubusercontent.com/112850551/204069958-239f267e-3e78-4286-b6c9-0897607ae04b.png)

![image](https://user-images.githubusercontent.com/112850551/204070018-f0540e80-807f-4ac2-b60a-1953be0b42bb.png)


Calling Operation
## Test Case 1: Name is found and frequency is incremented. OBST updated.

![image](https://user-images.githubusercontent.com/112850551/204070057-aebb0dad-8b61-4723-b8a5-d4d357c56a62.png)




## Test Case 2: Name is not found.
![image](https://user-images.githubusercontent.com/112850551/204070087-4272b5ab-42f3-4150-a696-7bd5b906133a.png)




## Test Case 3: Number is found and Frequency is incremented. OBST updated.
![image](https://user-images.githubusercontent.com/112850551/204070115-0c00a3b2-791e-448e-8ee7-7b3cde435e35.png)




## Test Case 4: Number not found.
![image](https://user-images.githubusercontent.com/112850551/204070135-fe749281-1e6e-4afc-9f5c-9a7bb33fdff8.png)




## Printing the updated OBST and cost,order matrix
![image](https://user-images.githubusercontent.com/112850551/204070151-27415ef8-cfe1-4858-9388-2a6dd97e2bbf.png)




![image](https://user-images.githubusercontent.com/112850551/204070180-4b80cb7f-be55-43f9-bb71-bb0511a1522b.png)




## Creating new contact
![image](https://user-images.githubusercontent.com/112850551/204070203-8059fc1a-25c1-4f03-8e36-291f23b27c49.png)


![image](https://user-images.githubusercontent.com/112850551/204070234-16f1e5fb-3bc8-42df-b799-5362073d1015.png)

![image](https://user-images.githubusercontent.com/112850551/204070248-d62d2bbd-9060-4573-9188-36e26426aa0e.png)



