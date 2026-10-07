# Project-author notes: fibers, fibrations, coverings, and homology

## Sources

### “What is a fibration?”

Project-author notes from 18 March 2013, preserved in the WordPress topology/homotopy archive:

https://isomorphismes.wordpress.com/tag/topology/

The original post summarizes a Niles Johnson explanation.

### Differential topology / Milnor notes

25 February 2013, preserved in the same archive:

https://isomorphismes.wordpress.com/tag/category-theory/

### “nerves of cell complexes”

17 May 2012, preserved here:

https://isomorphismes.wordpress.com/tag/computational-homology/

## Fibers and fibrations

The fibration note starts with products and projections.

For a product
\[
A\times B\to B,
\]
the fiber over \(b\in B\) is
\[
A\times\{b\}.
\]

This is the topological continuation of the elementary fiber
\[
f^{-1}(b)
\]
from a finite-set map.

The post then moves through:

- cylinder;
- Möbius band;
- Hopf-type twisting;
- base space, total space and fiber;
- sphere fibrations such as
  \[
  S^1\to S^3\to S^2.
  \]

The game-level point is that “a hole and the things over it” becomes “a base point and the whole fiber over it.”

## Homology as a functorial translation

The Milnor/differential-topology note emphasizes several categories of spaces and the different notions of sameness appropriate to them.

The key sentence for this repository is the observation that homology relates

- topological spaces with homotopy classes of maps

to

- groups with homomorphisms.

In other words, homology turns a geometric mapping problem into an algebraic mapping problem in a composition-respecting way.

That is precisely the kind of category change the game eventually wants.

## Nerves and covers

The “nerves of cell complexes” note links:

- covering spaces / covers;
- intersections;
- simplices;
- homology;
- set theory;
- computational topology.

The nerve construction replaces a geometric cover by a simplicial combinatorial object recording which covering sets intersect.

This is another good functorial game move:

- detailed geometry in;
- finite combinatorial incidence pattern out;
- preserve enough structure to recover topological information under suitable hypotheses.

## Game-design extraction

The progression can be:

1. finite fibers: several source objects can sit over one target;
2. product fibers: the same fiber repeats uniformly;
3. twisted bundles: locally the same fiber, globally different;
4. coverings: discrete fibers with monodromy/permutation;
5. nerves: replace a cover by an intersection complex;
6. homology: replace a topological object with algebraic invariants/maps.

The interaction can remain “follow what lies over / maps to / survives under translation.”

## Bibliographic trail

These posts explicitly draw on or name:

- **Niles Johnson** for the fibration exposition;
- **John W. Milnor**, especially *Topology from the Differentiable Viewpoint*;
- **David A. Edwards** in the Milnor/category-theory trail.

## Thanks

Thank you to **Niles Johnson**, **John W. Milnor**, and **David A. Edwards** for the sources and explanations named in the archived posts.
