# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Plagarism Statement

All exercises must contain the following statement:
“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”

## Note
I did not complete this excersise last semester, so I am attempting this completely from scratch.

## Answer
As long as the two graphs follow the rules for determining isomorphism there isn't anything that says that must be completely connected. For example, say that you have your two graphs $A$ and $B$, graph $A$ is comprised of 4 total nodes(named $e,f,g,h$), which connections between nodes $e$ and $f$, $g$ and $h$. Graph $B$ is also comprised of 4 total nodes(named $1,2,3,4$), with connection between nodes $1$ and $2$, $3$ and $4$. Right away we can see that there are the same total amounts of nodes, which is a point towards isomorphism. Beyond that, we can map one graph on to the other, and check the connections to check for isomorphism. That would mean that the corresponding node pairs are $e$ and $1$, $f$ and $2$, $g$ and $3$, $h$ and $4$. With this we see that any connections that either graph has are identical to the other graph, which means that they are in fact isomorphic, and because both graphs aren't completely connected with there being no connection between either nodes $e$ or $f$ to $g$ or $h$ and their counterparts $1$ or $2$ to $3$ or $4$, we see that isomorphism does not require two graphs to be completely connected.
