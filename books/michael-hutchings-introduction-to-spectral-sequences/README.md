# Michael Hutchings - *Introduction to spectral sequences*

## Source

Michael Hutchings, *Introduction to spectral sequences*, April 28, 2011.

https://math.berkeley.edu/~hutching/teach/215b-2011/ss.pdf

## Rights status

Link-only. No explicit redistribution license was assumed.

## Full-recall summary

Hutchings starts exactly where this project should start: with the long exact sequence associated to a short exact sequence of chain complexes.

For a subcomplex (F_0C_*subseteq C_*),
[
0\to F_0C_*\to C_*\to C_*/F_0C_*\to0
]
gives a long exact sequence in homology.

A filtration
[
\cdots\subseteq F_{p-1}C_*\subseteq F_pC_*\subseteq F_{p+1}C_*\subseteq\cdots
]
is a many-stage version of the same setup.

Its associated graded pieces are
[
G_pC_*=F_pC_*/F_{p-1}C_*.
]

The first page computes homology of those pieces. Higher differentials measure boundaries that drop through more filtration levels. Each page is a better approximation.

For a bounded filtered complex the process stabilizes and
[
E^\infty_{p,q}\cong G_pH_{p+q}(C_*).
]

The note then develops the Leray-Serre spectral sequence, first for homology and then cohomology/products.

The most useful project bridge is therefore:

**short exact sequence → long exact sequence → filtration → spectral sequence**.

This makes the Vakil exact-sequence picturebook a genuine prerequisite rather than decorative background.

## Bibliography in Hutchings

1. Raoul Bott and Loring W. Tu, *Differential Forms in Algebraic Topology*, Springer GTM.
2. Phillip Griffiths and Joseph Harris, *Principles of Algebraic Geometry*, Wiley.
3. John McCleary, *A User's Guide to Spectral Sequences*, 2nd ed., Cambridge University Press.
4. Jean-Pierre Serre, “Homologie singulière des espaces fibrés. Applications,” *Annals of Mathematics* 54 (1951), 425-505.

## Thanks

Thank you to **Michael Hutchings**.

Thank you also to **Raoul Bott**, **Loring W. Tu**, **Phillip Griffiths**, **Joseph Harris**, **John McCleary**, and **Jean-Pierre Serre** for the sources Hutchings names.
