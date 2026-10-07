# Project-author note: What is a “structure-preserving” map?

## Source

Original post, 19 October 2012:

https://isomorphismes.tumblr.com/post/33909584057/the-same-like-how

WordPress archive:

https://isomorphismes.wordpress.com/2012/10/19/the-same-like-how/

## Full-recall summary

The post asks what mathematicians actually mean by saying that a map “preserves structure.”

The central answer is: **preserves which structure?**

Two objects may be regarded as the same with respect to:

- shape;
- colour;
- material;
- cardinality;
- group structure;
- vector-space structure;
- topology;
- differentiable structure;
- metric structure;
- conformal structure;
- some other explicitly chosen invariant.

That means “isomorphic” is never a freestanding visual resemblance claim. It is relative to the category and the morphisms under discussion.

The children's-block example makes this concrete: the same collection can be partitioned into equivalence classes by shape, colour, or material. Each partition forgets different information.

For sets, cardinality gives one equivalence relation:
\[
A\sim B
\quad\Longleftrightarrow\quad
\text{there exists a bijection }A\to B.
\]

For metric spaces, a structure-preserving map must respect whatever metric condition the category requires.

For groups, vector spaces, topological spaces and manifolds, the corresponding homomorphisms / linear maps / continuous maps / smooth maps preserve different kinds of structure.

## Relation to pigeonhole

The pigeonhole game begins in **Set**, where the interesting data are simply:

- source elements;
- target elements;
- which source goes to which target.

Later versions can change the category while preserving the interactional skeleton.

The same player gesture can mean:

- assign pigeons to holes;
- send basis directions through a linear map;
- send group elements through a homomorphism;
- move points through a covering map;
- propagate classes through an exact sequence.

What changes is not the existence of the map but **which properties the map is required to preserve**.

This is the key argument against designing five unrelated minigames.

## Bibliographic / acknowledgment trail

The post explicitly mentions or credits:

- Smeet Bhatt, whose question prompted the exposition;
- John Baez and James Dolan, for the equality/isomorphism discussion;
- Daniel McLaury, for the list of category-specific map/isomorphism pairs.

## Thanks

Thank you to **Smeet Bhatt**, **John Baez**, **James Dolan**, and **Daniel McLaury** for the ideas and prompts named in the original post.
