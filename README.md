First we create an adjacency matrix B for an undirected random graph, where we do not allow self-loops. The entries of B are equal to 1 with probability p. Also, note that B is symmetric since the graph is undirected. Then we compute the eigenvalues of B - p * E, where E is the matrix of all ones.

Finally we scale the eigenvalues by the appropriate constants, and then plot a histogram based on the scaled eigenvalues. The usual semicircle p.d.f. of $1/(2*\pi) \sqrt(4-x^2)$ is also plotted, and we see that the histogram and the p.d.f. seem to agree.
