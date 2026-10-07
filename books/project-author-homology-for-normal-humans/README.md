# Project-author note: Homology for Normal Humans

## Source

Original Tumblr post, 30 August 2015:

https://isomorphismes.tumblr.com/post/127950269154/graded-chain-complex-of-a-simplex-homology

## Why this is a central source for the game

This post already contains most of the bridge from elementary geometric objects to homological algebra.

It begins with a solid triangular pyramid and asks the reader to consider, all at once:

- the 3-dimensional pyramid;
- its 2-dimensional triangular faces;
- its 1-dimensional edges;
- its 0-dimensional vertices.

That collection becomes a graded chain complex.

The boundary maps run downward in dimension:
\[
\cdots
\longrightarrow
C_3
\xrightarrow{\partial_3}
C_2
\xrightarrow{\partial_2}
C_1
\xrightarrow{\partial_1}
C_0
\longrightarrow 0.
\]

For the pyramid the visual story is roughly

\[
\text{pyramid}
\to
\text{faces}
\to
\text{edges}
\to
\text{vertices}
\to
\varnothing.
\]

The defining cancellation law is
\[
\partial_{n-1}\circ\partial_n=0.
\]

A boundary has no boundary.

## The key visual insight

The post emphasizes that a chain complex is not about staring at one object in isolation. One keeps neighboring dimensions in view together.

That suggests a natural game interaction:

1. select a cell;
2. reveal its boundary;
3. apply boundary again;
4. watch the signed pieces cancel.

The player can learn \(\partial^2=0\) before seeing the algebraic notation.

## Exactness, kernels, and “trash”

The post also includes a deliberately non-exact sequence and a kernel picture.

That is useful because the game should not suggest that every sequence is automatically exact.

Given
\[
A\xrightarrow{f}B\xrightarrow{g}C,
\]
the condition
\[
g\circ f=0
\]
only says
\[
\operatorname{im}f\subseteq\ker g.
\]

Exactness at \(B\) requires the stronger equality
\[
\operatorname{im}f=\ker g.
\]

So the player can first learn “everything arriving from two maps ago gets killed two maps later,” then distinguish:

- **chain complex:** everything from the previous map is killed;
- **exact sequence:** everything killed came from the previous map.

That distinction should become a visible gameplay condition.

## Relation to quotienting

The post also points toward free groups, reduction rules, normal subgroups, and quotienting.

This fits the repository's existing conceptual path:

\[
\text{collision}
\to
\text{fiber}
\to
\text{kernel}
\to
\text{quotient}
\to
\text{image}
\to
\text{exactness}
\to
\text{homology}.
\]

Homology is itself a quotient:
\[
H_n
=
\ker\partial_n
\big/
\operatorname{im}\partial_{n+1}.
\]

In words:

- cycles are things whose boundary vanishes;
- boundaries are cycles that already came from one dimension higher;
- homology keeps cycles modulo those already explained as boundaries.

This is another version of “collapse together things that the chosen map/structure does not distinguish.”

## Relation to spectral sequences

The later spectral-sequence material is no longer a conceptual jump once this picture is established.

A filtered complex adds another notion of level. Spectral-sequence pages repeatedly ask which classes survive increasingly long-range boundary information.

Thus the visual path can be:

\[
\text{simplex}
\to
\text{boundary}
\to
\partial^2=0
\to
\text{cycles/boundaries}
\to
H_n
\to
\text{filtered complex}
\to
E_r.
\]

## Bibliographic trail

The post directly links or names:

- Allen Hatcher for algebraic-topology language and notation;
- Tim Gowers for an exposition involving normal subgroups;
- Eilenberg and Mac Lane through the chain-complex / homological-algebra tradition;
- several linked references on grading, free groups, resolutions, and homotopy.

The source should remain the canonical place for its full outbound-link trail rather than copying all linked material here.

## Thanks

This is a project-author source.

Thank you to **Allen Hatcher**, **Timothy Gowers**, **Samuel Eilenberg**, and **Saunders Mac Lane** for the mathematical and expository trail explicitly used in the post.
