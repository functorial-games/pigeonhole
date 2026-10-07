# Project-author notes: functoriality, collapsing networks, and spinning holes

## Sources

### “A functor maps dots and arrows…”

12 March 2011:

https://isomorphismes.tumblr.com/post/3812125141/functor

### “Category Theory”

20 May 2010, later substantially amended:

https://isomorphismes.tumblr.com/post/615614573/category-theory

## Core idea

A functor does not merely map objects. It maps

- objects to objects;
- arrows to arrows;

while respecting identity arrows and composition.

Schematically, if
\[
U\xrightarrow{h}V\xrightarrow{g}W
\]
lives in a category \(\mathcal C\), then a functor \(F:\mathcal C\to\mathcal D\) gives
\[
F(U)\xrightarrow{F(h)}F(V)\xrightarrow{F(g)}F(W)
\]
and
\[
F(g\circ h)=F(g)\circ F(h).
\]

The older post uses simple parity/sign examples to make this concrete.

The later amendment is more directly relevant to the current game idea: it describes a smaller network embedding into a larger one without destroying its pattern of arrows, or a larger network collapsing onto a smaller one while maintaining the relationships that matter.

That is exactly the sense in which a later, more complicated game should be a **functorial lift** of the simple pigeonhole game rather than just thematically similar.

## The striking current-project connection

The amended Category Theory post also considers holes/voids in a state space and notes that if those voids spin around one another under the allowed morphisms, that extra motion can be retained with braid/groupoid structure rather than discarded.

That is extremely close to the present “spinning game / exact double cover” direction.

The older note therefore already contains both ingredients:

1. collapse or embed a network without breaking its relational structure;
2. retain braid-like information when holes move around each other.

## Game-design extraction

Start with a finite directed network representing a map.

A “legal translation” into a richer level should preserve:

- which pieces compose;
- which collisions identify objects;
- which distinctions survive;
- which cycles/braids are genuine invariants.

The game can then ask the player to recognize the same relational pattern under a change of category.

Examples:

- finite set map;
- linear map;
- covering map;
- exact-sequence diagram;
- surface with moving punctures;
- double complex.

The visual objects may change drastically while the allowed compositions and obstructions remain recognizable.

## Bibliographic trail

The 2010 post names or alludes to:

- Steve Easterbrook's category-theory tutorial;
- Bill / F. William Lawvere;
- category-theoretic treatments of knots, probability vectors, measured foliations and surfaces;
- Matt Hogancamp in connection with functorial embeddings;
- braid groupoids as the right level of structure for moving holes.

## Thanks

Thank you to **Steve Easterbrook**, **F. William Lawvere**, and **Matt Hogancamp**, whose work is explicitly part of the trail recorded in these posts.

Thanks also to the category-theory community whose object-arrow-composition language makes this project-level reuse precise.
