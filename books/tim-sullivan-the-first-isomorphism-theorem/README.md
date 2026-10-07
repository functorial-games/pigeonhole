# Tim Sullivan - *The First Isomorphism Theorem*

## Source

Tim Sullivan, *The First Isomorphism Theorem*:

https://www.tjsullivan.org.uk/pdf/morphthm2014.pdf

Historical project-author post, 27 December 2012:

https://isomorphismes.wordpress.com/2012/12/27/an-exposition-of-the-first-isomorphism-theorem/

Related earlier Tumblr note about explaining mathematics with concrete objects, including the “horsies and doggies” line:

https://isomorphismes.tumblr.com/post/19299303484/hofstadter-writing

## Rights status

Link-only. No explicit redistribution license for the PDF was established in this pass. Keep our summary here rather than copying the paper.

## Full-recall summary

Sullivan starts with sets rather than groups.

Let (C) be a set of cows and (M) a set of markets. A function
[
f:C\to M
]
assigns each cow its destination.

Instead of sending cows one at a time, group cows that share a destination into pens. For a market (m), its pen is the fiber
[
f^{-1}(m)=\{c\in C:f(c)=m\}.
]

Discard empty markets for the moment and let (P) be the set of nonempty pens. Then the original map factors as

[
C\xrightarrow{\pi}P\xrightarrow{\bar f}f(C)\xrightarrow{i}M,
]

where:

- (pi) sends a cow to its pen and is surjective;
- (ar f) sends a pen to its market and is bijective;
- (i) includes the used markets (f(C)) into (M) and is injective.

The core statement is therefore
[
P\cong f(C).
]

Equivalently, define (c_1\sim c_2) iff (f(c_1)=f(c_2)). Then
[
C/{\sim}\cong f(C).
]

This is already the first isomorphism theorem for **sets**.

The algebraic theorem has the same geometry. A homomorphism identifies source elements that differ by something in its kernel; quotienting by that indistinguishability produces something isomorphic to the image.

For a group homomorphism (arphi:G\to H),
[
G/\ker\varphi\cong\operatorname{im}\varphi.
]

For a linear map (T:V\to W),
[
V/\ker T\cong\operatorname{im}T.
]

In finite-dimensional linear algebra, taking dimensions gives rank-nullity:
[
\dim V
=
\dim\ker T
+
\dim\operatorname{im}T.
]

So the same picture runs:

**objects → fibers → quotient/coimage → image → codomain**.

That is exactly why this paper belongs next to the pigeonhole principle rather than in a disconnected “abstract algebra” folder.

## Connection back to pigeonholes

Pigeonhole says that when the source is larger than the codomain, at least one fiber must contain more than one object.

Sullivan’s factorization says that those fibers are not incidental: they are the equivalence classes one must collapse to make the map injective onto its image.

Thus “two pigeons landed in the same hole” and “two inputs become equal after applying the map” are literally the same event.

## Bibliography

No formal bibliography was recoverable from the indexed public copy during this pass. The source itself remains canonical; if a later source copy exposes a bibliography, add it here rather than guessing.

## Thanks

Thank you to **Tim Sullivan** for the exposition.

Thank you also to **Douglas Hofstadter**, whose concrete-teaching remarks were part of the project author's earlier trail into this material.
