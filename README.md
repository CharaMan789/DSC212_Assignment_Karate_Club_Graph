# DSC212 — Modularity on the Karate Club Graph

Summary of the assignment:
This assignment is about using a quantity called modularity, and this is to analyze which groups of people are more strongly connected than the rest. We analyse the Karate Club graph in the assignment here. Briefly, the procedure we follow - is to consider the adjacency matrix of the graph, and then subtract from it the matrix of expectances of edges of the graph, i.e a random graph with the degree of every node being preserved. Then we analyse the quantity modularity derived from this matrix obtained and our goal is to maximise this modularity. Upon optimizing for it, and relaxing the conditions surrounding the community assignment vector we obtain the eigenvalue equation, from which we obtain the eigenvalues. Then we consider the leading eigen-pair, i.e eigen-value and eigen-vector. If the leading eigenvalue is greater than 0, then splitting the community further (bipartition) increases modularity. Else, there is no improvement in modularity, and hence we must stop the partition. 

**Course**: DSC212 - Graph Theory.
**Institution**: IISER Thiruvananthapuram.
**Author**: Sricharan Pisupati.
