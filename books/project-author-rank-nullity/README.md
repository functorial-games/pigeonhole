# Project-author note: Rank-Nullity Theorem

## Source

Original Tumblr post, 25 March 2014:

https://isomorphismes.tumblr.com/post/80742382617/rank-nullity-theorem

## Why it matters here

This is the missing first-party post that the earlier archive search failed to identify.

Its core picture is that under a linear map, input dimensions have only two fates:

- they contribute to the image;
- they disappear into the kernel.

In finite-dimensional linear algebra, for
\[
T:V\to W,
\]
the precise theorem is
\[
\dim V=\dim\ker T+\dim\operatorname{im}T.
\]

Equivalently,
\[
\operatorname{nullity}(T)+\operatorname{rank}(T)=\dim V.
\]

This is the dimensional shadow of the first isomorphism theorem:
\[
V/\ker T\cong\operatorname{im}T.
\]

The quotient removes exactly the directions that the map cannot distinguish from zero; the surviving quotient directions are the image directions.

## Relation to pigeonhole

Suppose
\[
\dim V>\dim W.
\]

Then
\[
\operatorname{rank}(T)\le\dim W<\dim V,
\]
so
\[
\dim\ker T>0.
\]

Therefore \(T\) cannot be injective.

This is the linear-algebra version of the pigeonhole principle:

- too many independent source directions;
- too few independent target directions;
- some source direction must collapse.

For
\[
T:\mathbf{R}^{172}\to\mathbf{R}^{81},
\]
one gets
\[
\operatorname{nullity}(T)\ge 172-81=91.
\]

It is **exactly** \(91\) only when \(T\) has full rank \(81\), i.e. when the map is surjective onto the 81-dimensional codomain. This is a useful refinement of the intuitive statement in the original post.

## Necessary / sufficient bridge

For finite-dimensional vector spaces with
\[
\dim V=\dim W,
\]
the following are equivalent:

- \(T\) is injective;
- \(\ker T=\{0\}\);
- \(\operatorname{nullity}(T)=0\);
- \(\operatorname{rank}(T)=\dim V\);
- \(T\) is surjective;
- \(T\) is bijective.

When the dimensions are unequal, the implications separate:

- injective \(T:V\to W\) requires \(\dim V\le\dim W\);
- surjective \(T:V\to W\) requires \(\dim V\ge\dim W\).

This is the same inequality logic as finite-set injections and surjections.

## Game-design extraction

A useful interaction does not need to display matrices first.

Represent independent source directions as separate movable “sticks” or lanes. A target with fewer independent slots forces some lanes to collapse into zero or become dependent. The score/state can distinguish:

- survived independently = rank;
- collapsed to zero = nullity;
- target directions never reached = failure of surjectivity.

That turns rank-nullity into the same collision/missed-target language as the finite pigeonhole game.

## Bibliographic trail

The post itself is primarily a first-person exposition rather than a formal literature review. Its tags connect the discussion to:

- diagonalization;
- singular value decomposition;
- eigenvalue decomposition;
- orthonormal / orthogonal bases;
- matrix decompositions.

## Thanks

This is a project-author source.

Thanks also to the generations of linear algebra writers and teachers who developed the rank/nullity, kernel/image and basis-change language this note is using.
