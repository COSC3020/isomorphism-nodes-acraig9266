I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice. https://byjus.com/maths/one-to-one-function/ and https://byjus.com/maths/onto-function/ used for one-to-one function and onto function definition.

# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Onto: for every element of B, there is at least one or more than one element matching with A
One-to-one: function that maps all distinct elements of its domain to all distinct elements of its codomain

Consider two graphs, A and B, with n-1 and n nodes respectively. The set of nodes within these graphs are considered the domain (A) and codomain (B). In order for a function to be Onto, each node in B has to be mapped to by at least one node within A. Suppose that node i within graph A maps directly to node i in graph B for i = 1, 2, 3, ..., n-1. Every node within graph A is now mapped to a node in graph B. However, one node in B, node n, is not mapped to by any node in graph A which means it is not onto since all nodes in B must be mapped to. Suppose that node all nodes are mapped as before except now node 1 within graph A maps to node n in graph B. Every node in graph B is now mapped to so the function is onto, but node 1 within graph A is now mapped to nodes 1 and n in graph B meaning the function is no longer one-to-one. When there are more nodes in one graph (B) than another graph (B) it is not possible for the graphs A and B to be isomorphic as no singular function can be both onto and one-to-one for them.
