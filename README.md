findSCC
=======

graph search of strongly connected components

It is a graph application. With two rounds of DFS, this algorithm can be very fast to find the strongly connected components of direct acyclic graph. (In O(n+m), n represents number of vertices, m stands for number of edges).

The source data should be organised in such a format:

"
edge tail1     edge head1
edge tail2     edge head2
...
"

Note that it should be a direct acyclic graph, which should be satisfied in the data.
