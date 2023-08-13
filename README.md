# HashTable

# Hash Table with Binary Search Trees (BSTs) Implementation in Java

This project demonstrates the implementation of a Hash Table using Binary Search Trees (BSTs) in Java. The Hash Table allows for efficient storage and retrieval of values using a hashing mechanism, and each slot in the Hash Table is associated with a BST to handle collisions.

## Features

- The `Node` class represents individual nodes in the BST, containing data, and references to left and right nodes.
- The `BST` class implements basic Binary Search Tree operations such as insertion, deletion, searching, and in-order traversal.
- The `BSTHashTable` class combines the concepts of Hashing and BSTs to provide an efficient Hash Table. It supports insertion, deletion, finding, and rehashing to maintain a balanced structure.
- The `TestBST` class provides a simple example of how to use the BST Hash Table by inserting squared values of integers into the table and displaying the structure.

## Usage

The project showcases the usage of a Hash Table with Binary Search Trees for efficient storage and retrieval. The `TestBST` class demonstrates how to create a Hash Table, insert values, and display its structure.

Here's a brief example of usage:

```java
// Create a Hash Table with Binary Search Trees
BSTHashTable ht = new BSTHashTable();

// Insert squared values of integers (1, 4, 9, ..., 81)
for (int i = 1; i <= 10; i++) {
    int value = i * i;
    ht.insert(new Node(value));
}

// Display the Hash Table structure
ht.displayHashtable();

Feel free to explore the code and extend its functionalities as needed. The combination of Hashing and BSTs offers an efficient solution for handling collisions in Hash Tables.

For more details, refer to the source code files provided in the repository.
