# Finite maps, pigeonholes, injectivity and surjectivity

This is the short mathematical spine of the repository.

Let
[
f:A\to B
]
be a function between finite sets.

## Pigeonhole principle as failure of injectivity

If
[
|A|>|B|,
]
then no function (A\to B) can be injective.

Equivalently, every such function has distinct (a_1,a_2\in A) with
[
f(a_1)=f(a_2).
]

That is the ordinary pigeonhole principle with:

- elements of (A) = pigeons;
- elements of (B) = holes;
- the fiber (f^{-1}(b)) = all pigeons occupying hole (b).

The dual finite statement is just as useful:

If
[
|A|<|B|,
]
then no function (A\to B) can be surjective. At least one element of (B) is missed.

For equal finite cardinalities,
[
|A|=|B|,
]
a function (f:A\to B) is injective iff it is surjective iff it is bijective.

## Cardinal inequalities and existence of maps

For finite sets:

- an injection (A\hookrightarrow B) can exist iff (|A|\le |B|);
- for nonempty (B), a surjection (A\twoheadrightarrow B) can exist iff (|A|\ge |B|);
- a bijection (A\cong B) can exist iff (|A|=|B|).

The empty-set edge case for surjections should be stated separately: a function (A\to\varnothing) exists only when (A=\varnothing).

A useful logical distinction:

- “(f) is injective” is sufficient to conclude (|A|\le|B|).
- (|A|\le|B|) is necessary for that particular (f) to be injective.
- But (|A|\le|B|) does **not** imply that an arbitrary given (f:A\to B) is injective; it says only that some injection can exist.

The corresponding statements hold for surjectivity with the inequality reversed.

This is a clean place to teach “necessary” and “sufficient” without detached vocabulary.

## Fibers and the generalized pigeonhole principle

The fibers partition (A):
[
A=\coprod_{b\in f(A)}f^{-1}(b).
]

Hence
[
|A|=\sum_{b\in f(A)}|f^{-1}(b)|.
]

If (|A|>k|B|), then at least one fiber has size at least (k+1). More generally, some fiber has size at least
[
\left\lceil \frac{|A|}{|B|}\right\rceil
]
when (B\ne\varnothing).

So pigeonhole counting is already a statement about fiber size.

## Quotient by “has the same image”

Define
[
a_1\sim a_2 \quad\Longleftrightarrow\quad f(a_1)=f(a_2).
]

The equivalence classes are exactly the nonempty fibers of (f). The quotient set (A/{\sim}) is canonically in bijection with (f(A)):
[
A/{\sim}\;\cong\;f(A).
]

This is the set-theoretic template for the first isomorphism theorem.

Every map therefore factors as

[
A\twoheadrightarrow A/{\sim}\xrightarrow{\cong}f(A)\hookrightarrow B.
]

Read left to right:

1. collapse elements that the map cannot distinguish;
2. identify the resulting classes with the actual outputs;
3. include those outputs in the advertised codomain.

That is the bridge from pigeonholes to quotients, kernels/fibers, images, exactness, and later homological constructions.

## Game-design note

The first interaction does not need algebraic vocabulary. Let the player *feel*:

- collision when the codomain is too small;
- unused targets when the codomain is too large;
- exact matching when the sizes agree;
- whole fibers moving as units;
- quotienting as replacing many source objects by one “same destination” class.

Only after that should the same interaction be reused in more structured settings.
