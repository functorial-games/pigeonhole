# Project-author archive: intermediate game vocabulary

This note collects older project-author posts that sit between the elementary finite-map game and the later exact-sequence / spectral-sequence material.

They are not all about the pigeonhole principle. They are useful because they supply interaction patterns that preserve the same map/fiber/quotient logic while adding structure.

## 1. Adding Modes — independent pieces that recombine

Original post, 2 October 2012:

https://isomorphismes.tumblr.com/post/32778426504/adding-modes

The post treats an eigenbasis as a collection of separable, independent pieces that can be scaled and added.

The useful game idea is:

- decompose a complicated state into independent modes;
- let each mode evolve or scale separately;
- recombine the modes into the full state.

This is the right bridge from finite pigeons to rank-nullity. In the rank-nullity picture, independent source directions are the things being counted. Some directions survive into the image; some collapse into the kernel.

It also suggests a visual grammar for later chain-complex or spectral-sequence levels: do not show one huge opaque object if it can be displayed as independent pieces whose interactions are then introduced one layer at a time.

### Source trail

The post mentions vibrational modes, eigenbases, wavelets, electromagnetic fields and decomposition of time series. It explicitly credits **Karen Kafadar** for a decomposition example involving Mauna Loa CO₂ data.

## 2. ∂ Campbell’s — boundary as an operator

Archived post, 11 April 2013:

https://isomorphismes.wordpress.com/tag/topology/

The post compares the boundary operator with differentiation and emphasizes the product rule:
\[
\partial(A\times B)
=
(\partial A)\times B
+
(-1)^{\deg A}A\times(\partial B)
\]
up to the relevant chain-sign convention.

The original cylinder example is a concrete way to see that the boundary of a product is assembled from boundaries of its factors.

For the game, this gives a physical interpretation of a chain differential:

- an object has pieces;
- the differential exposes its boundary;
- applying the differential twice kills everything:
  \[
  \partial^2=0.
  \]

That statement is one of the basic engines behind homology and later spectral sequences.

## 3. Rubik’s cube — legal moves and unreachable states

Original post, 14 September 2010:

https://isomorphismes.tumblr.com/post/1120517680/rubik

The post emphasizes that many apparently imaginable cube states are not reachable by legal moves.

Examples include constraints on corner orientation: one cannot twist exactly one corner while leaving everything else fixed.

The point for this repository is not Rubik solving. It is the distinction between:

- a formally describable state;
- a state reachable under the allowed morphisms.

That is a powerful game mechanic.

A later level can display a target configuration and ask whether it lies in the image/orbit of the allowed operations. Failure can come from an invariant rather than from mere shortage of moves.

This is the group-action analogue of asking whether a target is in the image of a function.

### Source trail

The post quotes **György Marx** and mentions **Solomon Golomb** in connection with the structural analogy, alongside **Ernő Rubik** and the cube itself.

## 4. Mirzakhani / moduli spaces — quotienting surfaces by an equivalence

Original post:

https://isomorphismes.tumblr.com/post/124421978549/maryam-mirzakhani-dynamics-on-moduli-spaces-of

The post's glossary describes moduli as “smushing together” objects that are equivalent in the chosen sense.

That is exactly quotient-space language.

For the present game, the key move is:

- start with a large configuration space of surfaces;
- declare some transformations irrelevant;
- quotient by those transformations;
- play on the resulting moduli space.

That is a direct geometric analogue of
\[
A/{\sim}\cong \operatorname{image}
\]
from the set-theoretic first-isomorphism picture.

The post also discusses bundles, genus, loops, homotopy, diffeomorphism/homeomorphism and moving surfaces.

### Source trail

The post centers **Maryam Mirzakhani** and tags **Alexander Eskin** among the surrounding moduli-space/dynamics material.

## 5. Jets, bundles, and maps between spaces

Original post, 27 May 2014:

https://isomorphismes.tumblr.com/post/87048023784/a-jet-can-be-thought-of-as-the-infinitesimal-germ

The post uses a quote describing a jet as an infinitesimal germ of a section of a bundle or map between spaces, then builds a pictorial glossary of maps:

- circle to line;
- line wrapped around circle;
- loops into ambient space;
- homotopies as maps of cubes;
- manifold-to-manifold maps;
- vector fields as assigning a vector to each base point.

This reinforces a useful general rule for the game:

> Keep the map visible.

The objects may become surfaces, bundles, loops, fields or chain groups, but the player should still be able to answer:

- what is the source?
- what is the target?
- what lies over this target point?
- what information is forgotten?
- what structure survives composition?

### Source trail

The quoted jet description is attributed to **Michael Bächtold**, **David Corfield**, and **Urs Schreiber**.

## How these five posts fit the game

A possible progression now has a much more continuous shape:

\[
\begin{aligned}
&\text{finite objects}
\\
&\to \text{collisions / missed targets}
\\
&\to \text{independent modes}
\\
&\to \text{kernel / image}
\\
&\to \text{allowed moves / reachable states}
\\
&\to \text{quotient by irrelevant transformations}
\\
&\to \text{fibers and bundles}
\\
&\to \text{boundary maps}
\\
&\to \text{homology / exactness}
\\
&\to \text{successive pages}.
\end{aligned}
\]

No particular controller gesture or level design is fixed by this. The point is to preserve the mathematical continuity while the interaction is still being discovered.

## Thanks

Thank you to **Karen Kafadar, György Marx, Solomon Golomb, Ernő Rubik, Maryam Mirzakhani, Alexander Eskin, Michael Bächtold, David Corfield**, and **Urs Schreiber** for the work and explanations explicitly present in this archive trail.
