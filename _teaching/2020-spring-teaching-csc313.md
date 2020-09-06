---
title: "CSC313 Data Structures"
collection: teaching
type: "Undergraduate"
permalink: /teaching/2020-spring-teaching-313
venue: "Notre Dame University-Louaize"
date: 2020-03-01
location: "City, Country"
---
This course provides a detailed coverage of standard data structures with an emphasis on 
complexity analysis. Topics include: Asymptotic analysis, vectors, linked lists, stacks, queues,
trees and balanced trees, hashing, priority queues and heaps, sorting. Standard graph algorithms 
such as DFS, BFS, shortest paths and minimum spanning trees are also covered.
We will be making heavy use of C++ so it is important you read the c++ review early before the course really takes off.

The Lectures section below contains the theoretical concepts and we use pseudo code to illustrate the different operations on data structures and algorithms.

The Code explanation section contains a detailed explanation of the C++ implementation of different 
data stuctures and algorithms.

Finally, the Code section is a repository containing the complete source code of the examples we discuss in class.

[Lectures](/csc313/lectures)
======



[Code explanation](/csc313/README)
======

Code
======


This [repository](https://github.com/NDU-CSC313/inclass) contains all the code that we will be discussing in class. 
__Note__: all header files are in the include directory.
To build the code create a build directory then cd to it and type

> cmake ..

This will create a Visual C++ solution containing multiple projects where each project is an example we discuss in class. Note that many of these projects use different portions of the same source file. Each example is "activated" by enabling a different preprocessor variable. If you select an example project you will see that only the relevant portion of the code is highlighted (i.e. "enabled") by defininng (i.e. #define) a correspoding preprocessor variable and the reset is not.

If you are using Xcode on Mac then type

> cmake -G Xcode ..



