---
title: "Most popular Java interview questions"
date: 2022-02-01T01:17:00+10:00
author: zhengchengc
draft: false
---

## Algorithms and Data structure
### 1. ArrayList
- ArrayList inherits AbstractList class and implements the List interface.
- ArrayList is initialized by the size. However, the size is increased automatically if the collection grows or shrinks if the objects are removed from the collection.
- Java ArrayList allows us to randomly access the list.
- ArrayList can not be used for primitive types, like int, char, etc. We need a wrapper class for such cases.
- ArrayList in Java can be seen as a vector in C++.
- ArrayList is not Synchronized. Its equivalent synchronized class in Java is Vector.
  
### 2. Difference between ArrayList and LinkedList
| No. | Key | ArrayList | LinkedList |
|-----|-----|-----------|------------|
| 1 | Internal Implementation | ArrayList internally uses a dynamic array to store its elements. | LinkedList uses Doubly Linked List to store its elements. |
| 2 | Manipulation | ArrayList is slow as array manipulation is slower. | LinkedList is faster being node based as not much bit shifting required. |
| 3 | Implementation | ArrayList implements only List. | LinkedList implements List as well as Queue. It can acts as a queue as well. |
| 4 | Access | ArrayList is faster in storing and accessing data. | LinkedList is faster in manipulation of data. |

### 3. MergeSort
### 4. How concurrency is achieved.


## Java related questions
### 1. Why do you think Java is popular?
### 2. Immutability
### 3. Are Non-primitive datatypes like Integer, Double etc immutable or mutable ?
### 4. Threading using Runnable, Thread class and the interviewer was trying to go into details of executable framework.
### 5. Difference between StringBuilder and StringBuffer.
### 6. Can a single .java file contain multiple public classes.
### 7. What is a constructor?
### 8. What is the difference between equals() and ==
### 9. What is polymorphism
### 10. Java 8, Lambda functions, Metaspace,default and static methods in interfaces, new date-time APIs, improvement in Collections APIs and Concurrency package
### 11. difference between abstract class and interface
### 12. the concept of hashCode and equals method
### 13. working of the GC
### 14. working of thread executors
### 15. difference between Collection and Collections
### 16. the concept of inheritance
### 17. the difference between list and set
### 18. why strings are immutable
### 19. why char[] is better than String for passwords
### 20. does JVM virtualization impacts performance
### 21. What are the things that need to be aware when use Serializable



## Architecture questions
### 1. How does a microservice architecture work? What are the advantages and disadvantages?
### 2. What tools did you use to track any production issues?
### 3. Did you work on building pipelines? What is CI/CD?

## SDLC questions
### 1. Explain the whole process from development to deployment.
### 2. If you by mistake deploy a bug on prod, what would you do to resolve it?

## Behavior questions
### 1. What are your weaknesses and strengths?
