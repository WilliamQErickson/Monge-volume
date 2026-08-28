The Monge polytope M_pq is the set cut out from the standard simplex on p-by-q matrix coordinates by the classical Monge condition: 

M_ij + M_IJ \leq M_iJ + M_Ij, for all i<I and j<J.

The Mathematica notebook in this repo implements a combinatorial formula by Erickson-Jones (2026) for the volume of M_pq, expressed as a sum over what they call "Z-avoiding Delannoy paths" in [p] x [q].

This is a dynamic programming implementation, far faster than enumerating the Delannoy paths.

Assistance from Claude (Anthropic) was used in optimizing the Mathematica code.
