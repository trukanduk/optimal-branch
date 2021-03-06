optimal-branch
==============

A light-weight implementation of Edmond's Algorithm in C++. The alternative implementation uses the Boost Graph Library, which can be cumbersome to use. This version is fully self-contained and contains code that interfaces with MATLAB. 

Edmond's algorithm finds a directed graph with the minimum directed edge weights; it can be understood as a directed version of the minimum spanning tree algorithm. If given as input an undirected graph, Edmond's algorithm is guaranteed to produce the MST. 

This implementation is based on RE Tarjan's refinement of Edmond's original algorithm. Runtime is O(|E|log|V|)

https://cw.felk.cvut.cz/wiki/_media/courses/a4m33pal/cviceni/tarjan-finding-optimum-branchings.pdf
