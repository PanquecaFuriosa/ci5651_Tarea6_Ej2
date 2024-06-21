# Tree problem

## Proble:

Let $`A = (N, C)`$ be a tree (note that $`|C| = |N| − 1`$) and a predicate $`p : C → {true, f alse}`$. We want to answer questions that can take one of two forms:
- $`forall(x, y), for x, y ∈ N`$, that says whether to evaluate $`p`$ for all connections between nodes $`x`$ and $`y`$ results in true.
- $`exists(x, y), for x, y ∈ N`$, that tells whether evaluating $`p`$ for any of the connections between nodes $`x`$ and $`y`$ results in true.
  
Design an algorithm that can answer Q queries in any of these ways in time $`O(|N| + Q log |N|)`$, using additional memory $`O(|N|)`$
