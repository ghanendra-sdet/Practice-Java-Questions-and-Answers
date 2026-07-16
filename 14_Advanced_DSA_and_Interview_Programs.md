# 📁 Category 14: Advanced DSA & Interview Programs

> Advanced algorithms, complex data structures (Trees, Graphs, Tries), design problems, and Dynamic Programming.

---

## 📋 Table of Contents

- [1. Write a Java program to implement Linear Search](#1-write-a-java-program-to-implement-linear-search)
- [2. Write a Java program to implement Binary Search](#2-write-a-java-program-to-implement-binary-search)
- [3. Write a Java program to implement Bubble Sort](#3-write-a-java-program-to-implement-bubble-sort)
- [4. Write a Java program to implement Selection Sort](#4-write-a-java-program-to-implement-selection-sort)
- [5. Write a Java program to implement Insertion Sort](#5-write-a-java-program-to-implement-insertion-sort)
- [6. Write a Java program to implement Merge Sort](#6-write-a-java-program-to-implement-merge-sort)
- [7. Write a Java program to implement Quick Sort](#7-write-a-java-program-to-implement-quick-sort)
- [8. Write a Java program to implement Heap Sort](#8-write-a-java-program-to-implement-heap-sort)
- [9. Write a Java program to implement Counting Sort](#9-write-a-java-program-to-implement-counting-sort)
- [10. Write a Java program to implement Radix Sort](#10-write-a-java-program-to-implement-radix-sort)
- [11. Write a Java program to implement Bucket Sort](#11-write-a-java-program-to-implement-bucket-sort)
- [12. Write a Java program to implement Binary Tree Traversals (Inorder, Preorder, Postorder)](#12-write-a-java-program-to-implement-binary-tree-traversals-inorder-preorder-postorder)
- [13. Write a Java program to insert a node in a Binary Search Tree (BST)](#13-write-a-java-program-to-insert-a-node-in-a-binary-search-tree-bst)
- [14. Write a Java program to search for a value in a Binary Search Tree (BST)](#14-write-a-java-program-to-search-for-a-value-in-a-binary-search-tree-bst)
- [15. Write a Java program to delete a node from a Binary Search Tree (BST)](#15-write-a-java-program-to-delete-a-node-from-a-binary-search-tree-bst)
- [16. Write a Java program to perform Depth First Search (DFS) on a graph](#16-write-a-java-program-to-perform-depth-first-search-dfs-on-a-graph)
- [17. Write a Java program to perform Breadth First Search (BFS) on a graph](#17-write-a-java-program-to-perform-breadth-first-search-bfs-on-a-graph)
- [18. Write a Java program to represent a graph using Adjacency List and Adjacency Matrix](#18-write-a-java-program-to-represent-a-graph-using-adjacency-list-and-adjacency-matrix)
- [19. Write a Java program to implement Dijkstra's Algorithm for shortest path](#19-write-a-java-program-to-implement-dijkstras-algorithm-for-shortest-path)
- [20. Write a Java program to implement Floyd Warshall Algorithm for all-pairs shortest paths](#20-write-a-java-program-to-implement-floyd-warshall-algorithm-for-all-pairs-shortest-paths)
- [21. Write a Java program to implement Kruskal's Algorithm for Minimum Spanning Tree](#21-write-a-java-program-to-implement-kruskals-algorithm-for-minimum-spanning-tree)
- [22. Write a Java program to implement Prim's Algorithm for Minimum Spanning Tree](#22-write-a-java-program-to-implement-prims-algorithm-for-minimum-spanning-tree)
- [23. Write a Java program to implement Topological Sort on a Directed Acyclic Graph (DAG)](#23-write-a-java-program-to-implement-topological-sort-on-a-directed-acyclic-graph-dag)
- [24. Write a Java program to detect cycles in directed and undirected graphs](#24-write-a-java-program-to-detect-cycles-in-directed-and-undirected-graphs)
- [25. Write a Java program to implement a Trie data structure (insert, search, startsWith)](#25-write-a-java-program-to-implement-a-trie-data-structure-insert-search-startswith)
- [26. Write a Java program to implement a Segment Tree](#26-write-a-java-program-to-implement-a-segment-tree)
- [27. Write a Java program to implement a Fenwick Tree (Binary Indexed Tree)](#27-write-a-java-program-to-implement-a-fenwick-tree-binary-indexed-tree)
- [28. Write a Java program to implement a Stack using an array](#28-write-a-java-program-to-implement-a-stack-using-an-array)
- [29. Write a Java program to implement a Queue using an array](#29-write-a-java-program-to-implement-a-queue-using-an-array)
- [30. Write a Java program to implement a Circular Queue](#30-write-a-java-program-to-implement-a-circular-queue)
- [31. Write a Java program to implement a Singly Linked List (insert, delete, display)](#31-write-a-java-program-to-implement-a-singly-linked-list-insert-delete-display)
- [32. Write a Java program to implement a Doubly Linked List](#32-write-a-java-program-to-implement-a-doubly-linked-list)
- [33. Write a Java program to implement a Circular Linked List](#33-write-a-java-program-to-implement-a-circular-linked-list)
- [34. Write a Java program to detect a loop in a Linked List (Floyd's Cycle Finding Algorithm)](#34-write-a-java-program-to-detect-a-loop-in-a-linked-list-floyds-cycle-finding-algorithm)
- [35. Write a Java program to reverse a Singly Linked List](#35-write-a-java-program-to-reverse-a-singly-linked-list)
- [36. Write a Java program to simulate an LRU Cache (Design and Implementation)](#36-write-a-java-program-to-simulate-an-lru-cache-design-and-implementation)
- [37. Write a Java program to implement a Min Heap](#37-write-a-java-program-to-implement-a-min-heap)
- [38. Write a Java program to implement a Max Heap](#38-write-a-java-program-to-implement-a-max-heap)
- [39. Write a Java program to solve the Sliding Window Maximum problem](#39-write-a-java-program-to-solve-the-sliding-window-maximum-problem)
- [40. Write a Java program to solve the Two Sum problem](#40-write-a-java-program-to-solve-the-two-sum-problem)
- [41. Write a Java program to solve the Three Sum problem](#41-write-a-java-program-to-solve-the-three-sum-problem)
- [42. Write a Java program to find the Longest Substring Without Repeating Characters](#42-write-a-java-program-to-find-the-longest-substring-without-repeating-characters)
- [43. Write a Java program to find the Longest Increasing Subsequence](#43-write-a-java-program-to-find-the-longest-increasing-subsequence)
- [44. Write a Java program to solve the Coin Change problem](#44-write-a-java-program-to-solve-the-coin-change-problem)
- [45. Write a Java program to solve the 0/1 Knapsack problem](#45-write-a-java-program-to-solve-the-01-knapsack-problem)
- [46. Write a Java program to solve the N-Queens problem](#46-write-a-java-program-to-solve-the-n-queens-problem)
- [47. Write a Java program to solve the Sudoku Solver problem](#47-write-a-java-program-to-solve-the-sudoku-solver-problem)
- [48. Write a Java program to solve the Rat in a Maze problem](#48-write-a-java-program-to-solve-the-rat-in-a-maze-problem)
- [49. Write a Java program to solve the Word Search problem](#49-write-a-java-program-to-solve-the-word-search-problem)
- [50. Write a Java program to demonstrate Dynamic Programming Basics (e.g. Fibonacci, Climbing Stairs)](#50-write-a-java-program-to-demonstrate-dynamic-programming-basics-eg-fibonacci-climbing-stairs)

---

## 1. Write a Java program to implement Linear Search

### 📝 Problem Description
Write a Java program to implement: **implement Linear Search**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 2. Write a Java program to implement Binary Search

### 📝 Problem Description
Write a Java program to implement: **implement Binary Search**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 3. Write a Java program to implement Bubble Sort

### 📝 Problem Description
Write a Java program to implement: **implement Bubble Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 4. Write a Java program to implement Selection Sort

### 📝 Problem Description
Write a Java program to implement: **implement Selection Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 5. Write a Java program to implement Insertion Sort

### 📝 Problem Description
Write a Java program to implement: **implement Insertion Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 6. Write a Java program to implement Merge Sort

### 📝 Problem Description
Write a Java program to implement: **implement Merge Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 7. Write a Java program to implement Quick Sort

### 📝 Problem Description
Write a Java program to implement: **implement Quick Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 8. Write a Java program to implement Heap Sort

### 📝 Problem Description
Write a Java program to implement: **implement Heap Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 9. Write a Java program to implement Counting Sort

### 📝 Problem Description
Write a Java program to implement: **implement Counting Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 10. Write a Java program to implement Radix Sort

### 📝 Problem Description
Write a Java program to implement: **implement Radix Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 11. Write a Java program to implement Bucket Sort

### 📝 Problem Description
Write a Java program to implement: **implement Bucket Sort**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 12. Write a Java program to implement Binary Tree Traversals (Inorder, Preorder, Postorder)

### 📝 Problem Description
Write a Java program to implement: **implement Binary Tree Traversals (Inorder, Preorder, Postorder)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 13. Write a Java program to insert a node in a Binary Search Tree (BST)

### 📝 Problem Description
Write a Java program to implement: **insert a node in a Binary Search Tree (BST)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 14. Write a Java program to search for a value in a Binary Search Tree (BST)

### 📝 Problem Description
Write a Java program to implement: **search for a value in a Binary Search Tree (BST)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 15. Write a Java program to delete a node from a Binary Search Tree (BST)

### 📝 Problem Description
Write a Java program to implement: **delete a node from a Binary Search Tree (BST)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 16. Write a Java program to perform Depth First Search (DFS) on a graph

### 📝 Problem Description
Write a Java program to implement: **perform Depth First Search (DFS) on a graph**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 17. Write a Java program to perform Breadth First Search (BFS) on a graph

### 📝 Problem Description
Write a Java program to implement: **perform Breadth First Search (BFS) on a graph**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 18. Write a Java program to represent a graph using Adjacency List and Adjacency Matrix

### 📝 Problem Description
Write a Java program to implement: **represent a graph using Adjacency List and Adjacency Matrix**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 19. Write a Java program to implement Dijkstra's Algorithm for shortest path

### 📝 Problem Description
Write a Java program to implement: **implement Dijkstra's Algorithm for shortest path**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 20. Write a Java program to implement Floyd Warshall Algorithm for all-pairs shortest paths

### 📝 Problem Description
Write a Java program to implement: **implement Floyd Warshall Algorithm for all-pairs shortest paths**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 21. Write a Java program to implement Kruskal's Algorithm for Minimum Spanning Tree

### 📝 Problem Description
Write a Java program to implement: **implement Kruskal's Algorithm for Minimum Spanning Tree**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 22. Write a Java program to implement Prim's Algorithm for Minimum Spanning Tree

### 📝 Problem Description
Write a Java program to implement: **implement Prim's Algorithm for Minimum Spanning Tree**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 23. Write a Java program to implement Topological Sort on a Directed Acyclic Graph (DAG)

### 📝 Problem Description
Write a Java program to implement: **implement Topological Sort on a Directed Acyclic Graph (DAG)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 24. Write a Java program to detect cycles in directed and undirected graphs

### 📝 Problem Description
Write a Java program to implement: **detect cycles in directed and undirected graphs**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 25. Write a Java program to implement a Trie data structure (insert, search, startsWith)

### 📝 Problem Description
Write a Java program to implement: **implement a Trie data structure (insert, search, startsWith)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 26. Write a Java program to implement a Segment Tree

### 📝 Problem Description
Write a Java program to implement: **implement a Segment Tree**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 27. Write a Java program to implement a Fenwick Tree (Binary Indexed Tree)

### 📝 Problem Description
Write a Java program to implement: **implement a Fenwick Tree (Binary Indexed Tree)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 28. Write a Java program to implement a Stack using an array

### 📝 Problem Description
Write a Java program to implement: **implement a Stack using an array**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 29. Write a Java program to implement a Queue using an array

### 📝 Problem Description
Write a Java program to implement: **implement a Queue using an array**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 30. Write a Java program to implement a Circular Queue

### 📝 Problem Description
Write a Java program to implement: **implement a Circular Queue**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 31. Write a Java program to implement a Singly Linked List (insert, delete, display)

### 📝 Problem Description
Write a Java program to implement: **implement a Singly Linked List (insert, delete, display)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 32. Write a Java program to implement a Doubly Linked List

### 📝 Problem Description
Write a Java program to implement: **implement a Doubly Linked List**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 33. Write a Java program to implement a Circular Linked List

### 📝 Problem Description
Write a Java program to implement: **implement a Circular Linked List**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 34. Write a Java program to detect a loop in a Linked List (Floyd's Cycle Finding Algorithm)

### 📝 Problem Description
Write a Java program to implement: **detect a loop in a Linked List (Floyd's Cycle Finding Algorithm)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 35. Write a Java program to reverse a Singly Linked List

### 📝 Problem Description
Write a Java program to implement: **reverse a Singly Linked List**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 36. Write a Java program to simulate an LRU Cache (Design and Implementation)

### 📝 Problem Description
Write a Java program to implement: **simulate an LRU Cache (Design and Implementation)**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 37. Write a Java program to implement a Min Heap

### 📝 Problem Description
Write a Java program to implement: **implement a Min Heap**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 38. Write a Java program to implement a Max Heap

### 📝 Problem Description
Write a Java program to implement: **implement a Max Heap**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 39. Write a Java program to solve the Sliding Window Maximum problem

### 📝 Problem Description
Write a Java program to implement: **solve the Sliding Window Maximum problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 40. Write a Java program to solve the Two Sum problem

### 📝 Problem Description
Write a Java program to implement: **solve the Two Sum problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 41. Write a Java program to solve the Three Sum problem

### 📝 Problem Description
Write a Java program to implement: **solve the Three Sum problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 42. Write a Java program to find the Longest Substring Without Repeating Characters

### 📝 Problem Description
Write a Java program to implement: **find the Longest Substring Without Repeating Characters**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 43. Write a Java program to find the Longest Increasing Subsequence

### 📝 Problem Description
Write a Java program to implement: **find the Longest Increasing Subsequence**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 44. Write a Java program to solve the Coin Change problem

### 📝 Problem Description
Write a Java program to implement: **solve the Coin Change problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 45. Write a Java program to solve the 0/1 Knapsack problem

### 📝 Problem Description
Write a Java program to implement: **solve the 0/1 Knapsack problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 46. Write a Java program to solve the N-Queens problem

### 📝 Problem Description
Write a Java program to implement: **solve the N-Queens problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 47. Write a Java program to solve the Sudoku Solver problem

### 📝 Problem Description
Write a Java program to implement: **solve the Sudoku Solver problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 48. Write a Java program to solve the Rat in a Maze problem

### 📝 Problem Description
Write a Java program to implement: **solve the Rat in a Maze problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

## 49. Write a Java program to solve the Word Search problem

### 📝 Problem Description
Write a Java program to implement: **solve the Word Search problem**.

### 💻 Solution
```java
// Write your Java solution here
```

---
[⬆ Back to Top](#table-of-contents) | [📂 Main README](README.md)

---

