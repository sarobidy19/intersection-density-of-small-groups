# Intersection-density-of-small-groups

Let $G$ be a group and $H\leq G$ be a subgroup. We say that $\mathcal{F} \subset G$ is $H$-*intersecting* if for any $g,h \in \mathcal{F}$, there exists a coset $xH \in G/H$ such that $x^{-1}(g^{-1}h) x \in H$. The *intersection density* of the action of $G$ on the left cosets of $H$ by left multiplication is the rational number $$\rho(G,H) = \\{ \frac{|\mathcal{F}|}{|H|} : \mathcal{F} \mbox{ is $H$-intersecting} \\}.$$ The *intersection spectrum* of $G$ is the set

$$ \sigma(G) =\\{ \rho(G,H): H\leq G \\}.$$  

## Aim

The aim of this project is to the find the intersection sepectrum of small groups. Computations were done with **Sagemath**. The results are given in

* [1-100](/1-100/all-files-order-1-100.md)
* [101-200](/201-300/all.md) (non-abelian, <=100 groups for a given order)

Each line of the output looks as follows

|n|k|Description|Details|
|:---|:---|:---:|:--:|

where 

* $n$ is the order of the group, $k$ is its number in the library of ```SmallPermutationGroup(n,k)``` in **Sagemath**.
* **Description** is the structure description of the group.
* **Details** is a link to a file that contains the intersection density of the actions of the group on each of its subgroups.
