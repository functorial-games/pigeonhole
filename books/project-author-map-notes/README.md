# Project-author map / quotient / isomorphism trail

These are first-party posts from the project's author that belong beside the later textbook-style material. They show that the game idea is not being retrofitted onto an unrelated reading list: the same concerns about maps, fibers, quotienting, invertibility and changing representations were already present in the older notes.

## 1. Sullivan / first isomorphism theorem

27 December 2012:

https://isomorphismes.wordpress.com/2012/12/27/an-exposition-of-the-first-isomorphism-theorem/

The post points directly to Tim Sullivan's cows-and-pens exposition of the first isomorphism theorem.

See the dedicated full-recall note:

[../tim-sullivan-the-first-isomorphism-theorem/README.md](../tim-sullivan-the-first-isomorphism-theorem/README.md)

## 2. “going the long way”

4 January 2013:

https://isomorphismes.wordpress.com/2013/01/04/go-around-it/

This post asks what mathematicians mean by a bijection or homomorphism and treats a map as a way to move a problem into another representation, work there, and return.

Particularly relevant points:

- a bijection gives a “different way of looking at the same thing”;
- the image of a map is treated as the part of the target actually reached;
- monotone maps are used as examples of injective/invertible maps;
- a many-to-one map is contrasted with an injective one;
- composition is treated operationally: pipe the problem somewhere else, do work there, and unpipe it.

That viewpoint is useful for the game because the player does not need to learn “injective” first. They can learn which operations can be reversed and which merge distinct states.

## 3. “Automorphisms”

10 March 2013:

https://isomorphismes.wordpress.com/2013/03/10/automorphisms/

This post explicitly discusses:

- quotienting or passing to equivalence classes;
- a map as assigning members of one set to members of another;
- the ceiling map as a visibly noninjective example because many decimals land on the same integer;
- multiplication by zero as total collapse;
- automorphisms as reversible ways to turn an object around while preserving its structure;
- matrices as concrete representatives of linear transformations.

The ceiling-map example is almost already a pigeonhole game: many inputs visibly collide at one output.

## 4. Baez and Dolan: finite sets, equality and isomorphism

Tumblr post:

https://isomorphismes.tumblr.com/post/30269880365/why-simple-equality-isomorphism

The saved source is John Baez and James Dolan, *From Finite Sets to Feynman Diagrams*. The Tumblr note foregrounds the distinction between literal equality and isomorphism/equivalence and asks why counting statements such as \(6/2=3\) contain structural information rather than merely symbol manipulation.

That belongs here because the pigeonhole principle starts with finite sets but rapidly becomes a statement about what survives under a map.

## 5. Hofstadter / concrete exposition trail

https://isomorphismes.tumblr.com/post/19299303484/hofstadter-writing

This older note is part of the same expositional preference: do not make abstraction harder by refusing concrete objects. Sullivan's cows are useful precisely because the concrete story carries the correct abstract structure.

## Rank-nullity search status

A post explicitly identifiable as the project's own “rank-nullity theorem” excerpt has **not yet been positively recovered** from the public archive/search index. Do not invent a permalink.

The mathematical connection is nevertheless direct:

For a finite-dimensional linear map \(T:V\to W\),
\[
V/\ker T\cong\operatorname{im}T
\]
by the first isomorphism theorem, and taking dimensions gives
\[
\dim V=\dim\ker T+\dim\operatorname{im}T.
\]

So rank-nullity is the dimension-counting shadow of the same quotient/image factorization already represented by cows, pens and markets.

## Thanks

Thank you to **Tim Sullivan**, **Douglas Hofstadter**, **John Baez**, and **James Dolan**, whose work is explicitly linked in this trail.

The remaining prose and older project posts are by the project author and are preserved here as historical design context rather than as external authorities.
