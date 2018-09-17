---
title: Actions and Subgroups
author: Colton Grainger (MATH 6130 Algebra)
date: 2018-09-16
bibliography: /home/colton/Downloads/coltongrainger.bib
macros: true
---

\setcounter{section}{2}

## Assignment due 2018-09-19

### [@DF04, number 2.1.8]

Let $H$ and $K$ be subgroups of $G$. We have that $H \cup K$ is a subgroup if and only if either $H \subset K$ or $K \subset H$.

### [@DF04, number 2.1.9]

Let $G = GL_n(\FF)$ where $\FF$ is an field. We define the *special linear group* 
$$SL_n(\FF) = \{A \in GL_n(\FF) : \det(A) =1\}.$$

We have that $SL_n(\FF) \le GL_n(\FF)$.

### [@DF04, number 2.1.14]

The set $\{ x \in D_{2n} : x^2 = 1\}$ is not a subgroup of $D_{2n}$ (where $n\ge 3$).

### [@DF04, number 2.2.6]

Let $H$ be a subgroup of the group $G$. 

(a) $H \le N_G(H)$. We show that this is not necessarily true if $H$ is not a subgroup.

(b) $H \le C_G(H)$ if and only if $H$ is abelian.

### [@DF04, number 2.2.10]

Let $H$ be a subgroup of order $2$ in $G$. Then $N_G(H) = C_G(H)$.

If $N_G(H) = G$ then $H \le Z(G)$.

### [@DF04, number 2.2.12]

Let $R$ be the set of all polynomials with integer coefficients in the independent variables $\{x_j\}_1^4$. That is, members of $R$ are finite sums of elements of the form $ax_1^{r_1}x_2^{r_2}x_3^{r_3}x_4^{r_4}$ where $a \in \ZZ$ and $r_j \in \ZZ_{\ge 0}$.

Each $\sigma \in S_4$ gives a permutation of $\{x_1, x_2, x_3, x_4\}$ by defining $\sigma \cdot x_j = x_{\sigma(j)}$. This extends naturally to a map from $R$ to $R$ by defining $$\sigma\cdot p(x_1,x_2,x_3,x_4) = p(x_{\sigma(1)},x_{\sigma(2)},x_{\sigma(3)},x_{\sigma(4)})$$ for all $p(x_1,x_2,x_3,x_4) \in R$ (that is, $\sigma$ simply permutes the indices of the variables). 

(a) Let $p = p(x_1,x_2,x_3,x_4)$ be the polynomial 
$$12x_1^5x_2^7x_4 - 18x_2^3x_3 + 11x_1^6x_2x_3^3x_4^{23}$$
and consider the permutations $\sigma = (1 \, 2 \, 3\, 4)$ and $\tau = (1\, 2\, 3)$. We compute:

    - $\sigma \cdot p$
    - $\tau \cdot (\sigma \cdot p)$
    - $(\tau \circ \sigma)\cdot p$
    - $(\sigma \circ \tau)\cdot p$

(b) This definition gives a left subgroup action of $S_4$ on $R$.
(c) We exhaustively list all permutations in $S_4$ that stabilize $x_4$. They form a subgroup isomorphic to $S_3$.
(d) We list all permutations in $S_4$ that stabilize $x_1 + x_2$. They form an abelian subgroup of order $4$.
(e) We list all permutations in $S_4$ that stabilize $x_1x_2 + x_3x_4$. They  form a subgroup isomorphic to the dihedral group of order $8$.
(f) The permutations in $S_4$ that stabilize the element $(x_1 + x_2)(x_3 + x_4)$ are the same as those in part (e).

### [@DF04, number 2.3.25]

Let $G$ be a cyclic group of order $n$ and let $k$ be an integer relatively prime to $n$. The map $x \mapsto x^k$ is surjective.

### [@DF04, number 2.4.3]
### [@DF04, number 2.4.12]
### [@DF04, number 2.4.15]
### [@DF04, number 2.4.16]
### Maximal subgroups in a finite group

A finite group with no more that two maximal subgroups is cyclic.

## References