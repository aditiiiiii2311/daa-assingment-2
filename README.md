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

Printing the OBST with already present information.
![image](https://user-images.githubusercontent.com/112850551/204069756-edc48c09-bb28-4e9f-9a96-503fb3e807a1.png)


image

Calling Operation
Test Case 1: Name is found and frequency is incremented. OBST updated.
image

Test Case 2: Name is not found.
image

Test Case 3: Number is found and Frequency is incremented. OBST updated.
image

Test Case 4: Number not found.
image

Printing the updated OBST and cost,order matrix
image

image

Creating new contact
image

image

image
