# embedding-graphs-finite-fields

- embeds the adjacency matrix of a graph into the finite field F_q by viewing edges as bits, writing the bitstring k as an integer, and using that as the exponent of a multiplicative generator
- factors an adjacency matrix U = AA^* using the Hermitian decomposition used for unitary rep'ns of the symmetric group over a finite field. note the adjacency matrix is symmetric and values are in {0,1}, which are in any field
