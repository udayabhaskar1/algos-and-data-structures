# algos-and-data-structures

## Assignment 1
A sparse array is an array in which most elements are empty (in Python, None). A list L can be used to
implement such an array efficiently. In particular, for each nonempty cell A[i], we can store an entry (i,e) in
L, where e is the element stored at A[i]. This approach allows us to represent A using O(m) storage, where
m is the number of nonempty entries in A.


Implementing a SparseArray class based on a linked list. Your class should
support the following methods:
● __init__(n) to construct an initially empty SparseArray of size n
● fill(seq) to fill the SparseArray with data from a given sequence seq
● __getitem__(j) and __setitem__(j, e) to provide standard indexing operations
● __len__() to enable len(A)

Deliverables for the assessment:
1. Pseudocode for the methods of the SparseArray class.
2. An analysis of the efficiency of your algorithms for __getitem__(j), __setitem__(j, e), and fill(seq) in
terms of m , the number of actual non-empty elements, and n , the overall size of the array. You must
provide justification for your analysis.
3. Python code for the SparseArray class. You may use any underlying linked list implementation of
your choice, but should justify whatever you are using.
4. Python code for efficiency experiements.

## Assignment 2

Objective
Efficient searching of databases can be done with the use of high performance data structures which are often used to efficiently perform the necessary operations in a timely manner. We can look at hash tables and trees as some of the most commonly used data structures suitable for this purpose. The objective of this assignment is to analyze these two forms of data structures, make comparisons and explain their significance in their real-world usage.

We evaluate the efficiency of these data structures under set conditions and further explore their implementation and uses.
Data structures to be analyzed
1. Probing Hash Table
2. AVL tree
3. Modified Probing Hash Table
