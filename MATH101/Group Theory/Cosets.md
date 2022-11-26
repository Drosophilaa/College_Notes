From [last solution](<Lagrange's Theorem#Generalizing/Proving the Theorem#An important Observation>) we define $<x>$ and $y<x>$ 
Thus, 
$$
<x> \cap \:y<x> = \phi
$$

and so on for "$z$" too
$$
z<x> \cap \: y<x> = \phi
$$

Let $G$ be a group and $S$ be any subset of $G$
Let $y \in G$ be some element.
We define $yS$ to be the set of all elements of the form $yx$ where $x \in S$
$$
yS = \{\:yx \:| \:x \in S \:\}
$$
Note that if $s_{1} \: ,s_{2}$ are distinct elements of $S$ , then $ys_{1} \neq ys_{2}$
Thus the function 
$$
\Phi : S \rightarrow yS 
$$
defined by $\Phi(s)=y$ for $s \in S$ is a one-one function

Any element of $yS$ is of the form $ys$ for some $s \in S$ 
So, $\Phi(s)=ys$

Thus, the function $\Phi$ is a Bijective Function from $S$ to $yS$
>This explains why the element $y, yx,\dots yx^{d-1}$ were all distinct

------------------------------------
### Disjointness Arguments:

Suppse $y,x$ are two elements of $G$. When can we say that 
$$
y<x> \cap \: z<x> \: = \phi
$$
Suppose its not true
Then, $yx^{i}=zx^{j}$ for some $i$ and $j$. So $z=yx^{i-j}$
But, $yx^{i-j} \in y<x> \implies z \in y<x>$

Thus we can say that 
```ad-note
title: Conlusion
If $z \notin y<x>$ , then the sets $y<x>$ and $z<x>$ are disjoints
```


