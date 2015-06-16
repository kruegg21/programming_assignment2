# Traveling-Salesman-Problem

Solves the travelling salesman problem for an undirected and complete graph, using a branch-and-bound method to improve the speed. This program is able
to solve some versions of the problem that are intractable by brute force. Successul with a graph of size 32
during testing. 

The graph should be stored as a text file with each line specifying an edge. The first string in each line should be the starting vertex, the second string should be the destination vertex, and the final string should be a number specifying the length of the edge. For an example, look at the test file p01.txt which is included in the directory

1. make clean
2. make
3. ./tsp < graph_file.txt

