---
layout:     post
title:      Project of B+ Tree
subtitle:   Implementation of B+ Tree Data Structure 
date:       2018-01-25
author:     shumoyuan
header-img: "img/post-bg-2018.jpg"
tags:
    - Data Structure
    - B Plus Tree
    - Implementation
---

[ProjectPage](https://github.com/shumoyuan/BPlusTree)

The primary value of a B+ tree is in storing data for efficient retrieval in a block-oriented storage context — in particular, file systems. In this project, you’re asked to develop and test a small degree B+ tree used for internal-memory dictionaries (i.e. the entire tree resides in main memory). The data is given in the form (key, value) with no duplicates, you are required to implement an m-way B+ tree to store the data pairs. Note that in a B+ tree only leaf nodes contain the actual values, and the leaves should be linked into a doubly linked list. Your implementation should support the following operations:

1. Initialize (m): create a new m-way B+ tree

2. Insert (key, value)

3. Delete (key)

4. Search (key): returns the value associated with the key

5. Search (key1, key2): returns values such that in the range key1 <= key <= key2



To Complied:
just type "make"in the terminal when the terminal is in this filepath

To use(As instruction):
./bplustree [filename]

Output file:
output_file.txt