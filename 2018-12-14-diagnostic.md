---
title: Odds and Ends for Algebra
author: Colton Grainger (MATH 6130)
date: 2018-12-14
macros: true
bibliography: /home/colton/coltongrainger.bib
nonumbering: true
tikz: true
---

## 90 minute practice test

Questions from `2013-mit-18703-midterm2-solns.pdf`.

### Definitions

i. Give the definition of a ring.
ii. Give the definition of an integral domain.
iii. Give the definition of a maximal ideal.

### Sylow theory

i. State the Sylow theorems.

ii. Prove that if $G$ is a group of order $pq$, with $p$ and $q$ distinct primes, then $G$ is not simple.

### Classifying rings

i. Let $R$ be a commutative ring and let $a$ be an element of $R$. Prove that the set $\{ra : r \in R\}$ is an ideal of $R$.

ii. Prove TFAE.

    a. $R$ is a field.
    b. $R$ has no proper ideals.
    c. $0$ is a maximal ideal in $R$.
    d. Every nonzero homomorphism of rings $R \to S$ is a monomorphism.

### Elementwise

i. Let $R$ be an entire ring. If $ab = ac$ for $a \neq 0$ where $a,b, c \in R$, then show that $b = c$.

ii. Show that every finite integral domain is a field.

### Quotient rings

i. Prove that an ideal $\fp$ is prime if and only if $R/\fp$ is entire.

ii. Let $p$ be a prime number. Show that the ring $\ZZ_p \cong \ZZ/p\ZZ$ is a field.

### Mapping into rings

i. State the first isomorphism theorem for rings.

ii. Let $X$ be a set and let $R$ be a ring. Let $F$ be the set of all functions from $X$ to $R$. Let $x \in X$ and let $I$ be the ideal of all functions in $F$ vanishing at $x$. Prove that $I$ is a prime ideal if and only if $R$ is an entire ring.

### the CRT

i. Let $m$ and $n$ be coprime integers. Prove that $\ZZ_{mn} \cong \ZZ_m \oplus \ZZ_n$.

## Rings

### Hierarchy theorem

i. State the "hierarchy theorem".
i. Describe one ring that serves as a "depth separation" at each level of the hierarchy.
i. Show that if $R$ is a PID then every ascending chain condition of ideals eventually stabilizes.
i. Define a Bézout domain.
i. Let $R$ be a PID and let $a,b \in R \setminus \{0\}$. Show that there exists $d \in \mathrm{GCD}(a,b)$ such that $d = ra + sb$ for some $r,s \in R$.

### Prime and maximal ideals

Let $R$ be a commutative unital ring. 

i. When is an ideal $\fp$ said to be prime? When is an element $p \in R$ said to be prime? 
i. Prove that a maximal ideal is prime.
i. Prove that every proper ideal is contained in a maximal ideal. (Zorn's lemma.)
i. Prove that an ideal $\fp$ is prime if and only if $R/\fp$ is entire.
i. Prove an ideal $\fm$ is maximal if and only if $R/\fm$ is a field.
i. Prove TFAE.

    a. $R$ is a field.
    b. $R$ has no proper ideals.
    c. $0$ is a maximal ideal in $R$.
    d. Every nonzero homomorphism of rings $R \to S$ is a monomorphism.

i. Define comaximality.
i. State the CRT for the integers and for a general 
i. [@DF04, number 7.4.33] Let $R$ be the ring of continuous functions $C_\RR([0,1])$. For each $c \in [0,1]$, let $M_c = \{f \in R : f(c) =0\}$. (Recall $M_c$ is a maximal ideal.)

    a. Prove that if $M$ is *any* maximal ideal of $R$, then there is a real number $c \in [0,1]$ such that $M = M_c$.
    b. Prove that if $b$ and $c$ are distinct points in $[0,1]$, thne $M_b \neq M_c$.
    c. Prove that $M_c$ is not equal to the principal ideal generated by $x-c$.
    d. Prove that $M_c$ is not a finitely generated ideal.

i. [@DF04, number 7.4.33] Let $R$ be the ring of continuous functions from $C_\RR(\RR)$.

    a. Let $I \subset R$ be the collection of functions $f(x)$ with *compact support*. Prove that $I$ is an ideal of $R$ that is not a prime ideal.
    b. Let $M$ be a maximal ideal of $R$ containing $I$ (properly). Prove that $M \neq M_c$ for any $c \in \RR$.

### Irreducibility criteria

i. Define the field of fractions of an entire ring $R$.
i. State Gauss' lemma.
i. State the Eisenstein criterion.
i. Prove that prime elements are irreducible in an entire ring.
i. In a UFD, prove that irreducible elements are prime. 
i. Prove that if $F$ is a field, then $F[x]$ is a Euclidean domain (hint: use degree as a norm).

## Groups

### Counting arguments and group actions

i. State and prove Lagrange's theorem.
i. Define Normalizers and Centralizers.
i. State Cauchy's theorem.
i. State and prove the Orbit-Stabilizer theorem.
i. State and justify the class equation.
i. State Burnside's counting lemma.
i. State Sylow's theorems.
i. Make a short list of atleast $5$ Sylow theory techniques.
i. Prove there is no simple group of order $120$.

### Group classification

i. Define a simple group.
i. Define a solvable group.
i. State Feit-Thompson's theorem.
i. State Burnside's theorem.
i. State P. Hall's theorem.

### Abelian groups and free groups

i. State the FTFGAG.
i. Classify all abelian groups of order 1500.
i. Define the commutator subgroup.
i. State and prove a universal property for the commutator subgroup.
i. Define a free group.
i. State and sketch the universal property for free groups.
i. Let $F$ be a free group and let $N$ be the subgroup generated by the set $\{x^n : x \in F, n \text{ a fixed integer}\}.$ Show that $N \triangleleft F$.
i. Prove that a free abelian group is a free group if and only if it is cyclic.
i. Show that the cyclic group of order $6$ is the group defined by the generators $a,b$ and the relations $a^2 = b^2 = a^{-1}b^{-1}ab = e$.
i. Prove that $G = \langle x, y : x^3 = y^3 = (xy)^3 = 1\rangle$ is an infinite group as follows. 

    Let $p$ be a prime congruent to $1 \mod 3$ and let $G_p$ be the non-abelian group of order $3p$. Let $a,b \in G_p$ with $\abs{a} = p$ and $\abs{b} = 3$. [@DF04, number 6.3.14] Verify that both $ab$ and $ab^2$ have order $3$. Show that $G_p$ is a homomorphic image of $G$. Argue that $G$ is therefore an infinite group, as there are infinitely many primes $p \equiv 1 \mod 3$. 

### Nilpotence

i. Define a composition series.
i. Define the upper and lower central series.
i. Define nilpotence.
i. Give at least $4$ equivalent criteria to recognize a nilpotent group.
i. Prove that a maximal subgroup of a finite nilpotent group has prime index.

### Semi-direct products

i. Let $K$ and $L$ be groups, let $n$ be a positive integer, let $\rho \colon K \to S_n$ be a homomorphism and let $H$ be the direct product of $n$ copies of $L$. From [@DF04, number 5.1.8], we constructed an injective homomorphism $\psi$ from $S_n$ into $\Aut{H}$ by letting the elements of $S_n$ permute the $n$ factors of $H$. The compositions $\psi \circ \rho$ is a homomorphism from $G$ into $\Aut{H}$. The *wreath product* of $L$ by $K$ is the semidirect product $H \rtimes_\psi K$ with respect to this homomorphism and is denoted by $L \wr K$. Note this wreath product depends on the choice of permutation representation $\rho$ of $K$ --- if none is given explicitly, then $\phi$ is assumed to be the left regular representation of $K$. [@DF04, number 5.5.23]

    (a) Assume $K$ and $L$ are finite groups and $\rho$ is the left regular representation of $K$. We find $\abs{L \wr K}$ in terms of $\abs{K}$ and $\abs{L}$.

    (b) Let $p$ be a prime, let $K = L = Z_p$. Suppose $\rho$ is the left regular representation of $K$. Then $Z_p \wr Z_p$ is a non-abelian subgroup of order $p^{p+1}$ and is isomorphic to a Sylow $p$-subgroup of $S_{p^2}$. [The $p$ copies of $Z_p$ whose direct products makes up $H$ may be represented by $p$ disjoint $p$-cycles; these are cyclically permuted by $K$.]

i. Classify the thirteen isomorphism types of groups of order $56$. *See.* [@DF04, number 5.5.7] 

### Frattini's argument [@DF04, number 6.1.20]

i. State Frattini's argument.
i. Let $p$ be a prime, let $P$ be a $p$-subgroup of the finite group $G$, let $N$ be a normal subgroup of $G$ whose order is relatively prime to $p$, and let $\bar{G} = G/N$. 

    a. With Frattini's argument, $\N { \bar{G} } { \bar{P} } = \overline{\N G P}$.
    b. From above, $\N{\bar{G}}{\bar{P}} = \overline{\N G P}$.

### Common groups

i. Define $S_n$ and describe in detail for $n = 3, \ldots 6$.
i. Define $D_{2n}$ with two presentations.
i. Define $Q_8$ and prove that it is possible to inject $Q_8$ into $S_7$.
i. Define $A_n$ and describe in detail for $n = 4, 5, 6$.
i. Define $V_4$.
i. Given a group $G$, define $\Aut{G}$.
i. Describe the automorphisms of a cyclic group $Z_m$.

## References