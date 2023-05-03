Download Link: https://assignmentchef.com/product/solved-cs2040c-assignment-3-binary-search-tree
<br>
Your tasks in a summary, implement the followings:

<ol>

 <li>In-order and post-order traversals</li>

 <li>The height of each node and the size of the tree</li>

 <li>Searching for minimum and maximum of a tree</li>

 <li>Check if an element exist in the tree</li>

 <li>The successor function</li>

 <li>AVL tree balancing</li>

</ol>

<strong><u>You can assume that a tree is not empty (size &gt; 0) for Tasks 3 and 5</u></strong>. Therefore, you code should work for the rest even if the tree has no node. First, please aim at finishing Tasks 1 to 4. Tasks 5 and 6 could be considered as more difficult.

Over all, you are allowed to (and you should) add more member variables and functions to the two given classes. However, remember to copy and paste the code for the class definitions also.

In order to avoid lengthy wording, “BST” stands for Binary Search Tree in this worksheet.

<h1>Skeleton Code</h1>

You are given three files with some basic implementations of a binary search tree:

<ul>

 <li>cpp, BST.h, BST.hpp</li>

</ul>

The following functionalities are already implemented for you:

<ul>

 <li>Basic insertion without balancing</li>

 <li>Print out all the nodes according to pre-order traversal</li>

 <li>Print out the tree structure with a 90 degree anti-clockwise rotation</li>

</ul>




<h1>Task 1 In-order and Post-order Traversals</h1>

The pre-order traversal is implemented for you. Your job is to implement the in-order and post order traversal.

Sample output:




<h1>Task 2 Size of the Tree and Height of Node</h1>

The size of the tree is the number of the elements being inserted into the tree. Currently, the <strong>_size</strong> member is zero and not set correctly. So does the height of each node (<strong>_height</strong>). Here is the correct sample input if you implemented them correctly.

<h1>Task 3 Search Min/Max</h1>

Uncomment testSearchMinMax() in main(). Implement the functions searchMin() and searchMax() in BST. Here is the sample output for the tree in the code:




<h1>Task 4 Search for an Element in the Tree</h1>

Uncomment testExist() in main(). Similar to the Linked List assignment, implement a function exist(x) to return true if x is in the tree, and false otherwise.




<h1>Task 5 Successor</h1>

Uncomment testSuccessor() in main(). Implement the function successor(x) in BST such that it will return the successor of x:




<h1>Task 6 AVL Tree Balancing</h1>

If you have reached this point, congratulation! However, here is the “final boss” you have to fight. Your tree should work fine so far for the above functionalities. <strong>At this point, we highly recommend you to save and backup all your work so far</strong>. Zip them up and copy them to a safe location.

Uncomment testInsertion2 () in main()and you will get a skewed tree like this. This is because the balancing has not been implemented yet.




In order to balance the tree, you should

<ul>

 <li>Implement the left and right rotations (refer to the notes and Lab 4 slides)</li>

 <li>Add additional code in the insertion function to balance the tree after insertion.</li>

</ul>

If you have implemented correctly, your tree in the “Insertion Test 2” should be the same as the one before.







<h1>Final Result</h1>

If you have implemented everything correctly, your final output should be like this





