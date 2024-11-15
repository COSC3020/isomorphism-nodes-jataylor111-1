# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

------------------------------------------------------------------------------

This will fall apart in the function mapping, but I'm going to do this via contradiction because if I remember correctly you suggested it for these proofs in general.

First let $A = (V_1, E_1)$ and $B = (V_2, E_2)$ be graphs, where $A$ has more nodes than $B$.

Then, there exists a one-to-one and onto function $f: V_1 \rightarrow V_2$, so we would map the first node of $A$ to the first node of $B$, the second to the second, and so on.

But this is where we get our contradiction.  

Since $A$ contains more nodes than $B$ there are two possible outcomes; first, $A$ maps to multiple nodes in $B$ or, secondly, $A$ has some nodes that just aren't mapped at all.

Finally, because of this issue our function cannot be bijective, which means that two graphs that do not have the same number of nodes cannot be isomorphic.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
