# J. Peter May - *A Primer on Spectral Sequences*

## Source

J. Peter May, *A Primer on Spectral Sequences*.

https://www.math.uchicago.edu/~may/MISC/SpecSeqPrimer.pdf

## Rights status

Link-only. Public author-hosted PDF; no redistribution license was assumed.

## Full-recall summary

May's primer is the compact reference after the intuition-first readings.

It covers:

1. definitions;
2. exact couples;
3. filtered complexes;
4. products;
5. the Serre spectral sequence;
6. the comparison theorem;
7. convergence proofs.

The exact-couple construction is particularly important.

An exact couple consists schematically of
[
D\xrightarrow{i}D\xrightarrow{j}E\xrightarrow{k}D
]
with exactness at every corner. The composite
[
d=jk:E\to E
]
satisfies (d^2=0). Taking homology produces a **derived exact couple**, and repeating produces the pages (E_r).

So one can view a spectral sequence as a self-renewing exactness machine.

For filtered complexes, May relates this to
[
0\to F_{p-1}A\to F_pA\to F_pA/F_{p-1}A\to0,
]
whose long exact homology sequences fit together into the exact couple.

This is the cleanest formal bridge from Vakil's long/exact-sequence pictures to a genuine spectral sequence.

May also emphasizes multiplicative structure: when the underlying filtered object has a compatible product, the pages inherit products and the differentials satisfy a Leibniz rule. That is a major reason spectral sequences compute more than groups.

## Bibliography in May

1. Saunders Mac Lane, *Homology*, reprint of the 1975 edition, Springer, 1995.
2. J. Peter May, *A Concise Course in Algebraic Topology*, University of Chicago Press, 1999.
3. John McCleary, *A User's Guide to Spectral Sequences*, 2nd ed., Cambridge University Press, 2001.
4. Paul Selick, *Introduction to Homotopy Theory*, Fields Institute Monographs 9, AMS, 1997.
5. Charles A. Weibel, *An Introduction to Homological Algebra*, Cambridge University Press, 1994.

## Thanks

Thank you to **J. Peter May**.

Thank you also to **Saunders Mac Lane**, **John McCleary**, **Paul Selick**, and **Charles A. Weibel** for the works May cites, and again to May for the cited *Concise Course* that supplies part of the surrounding framework.
