I implemented Kosaraju's algorithm to find strongly connected components of a given directed graph.

In ***strongly_connected_components.py*** I implement the algorithm using a recursive approach.

My implementation is simple and readable. It runs fast.

However, for massive cases, because of recursion limits, it crashes.


Using stacks instead of recursively calling a function (particularly for depth-first-search parts) solves the problem for humongous input graphs.

I implemented the algorithm, taking an iterative approach, in ***strongly_connected_components_iterative_version.py***

My implementation is simple and readable (I hope).

It runs fantastically for any gigantic graph size.


