# Ravi Vakil - *Puzzling through exact sequences*

## Source

3Blue1Brown guest post:

https://www.3blue1brown.com/blog/exact-sequence-picturebook/

The page links the PDF version of Ravi Vakil's *Puzzling through exact sequences: A Bedtime Story with Pictures*.

## Rights status

Link-only. The work is publicly hosted with Vakil's permission, but no general redistribution license was established here.

## Why it belongs here

The project needs the transition

[
\text{fibers / quotienting}
\longrightarrow
\text{exactness}
\longrightarrow
\text{long exact sequences}
\longrightarrow
\text{spectral sequences}
]

to remain visual.

Vakil's picturebook does that with diagrams rather than asking the reader to begin with a wall of notation.

The central algebraic condition for an exact sequence
[
\cdots\to A\xrightarrow{f}B\xrightarrow{g}C\to\cdots
]
is
[
\operatorname{im}f=\ker g.
]

So everything that arrives in (B) from the left is exactly everything that is killed when moving right.

This is already closely related to the pigeonhole/fiber picture:

- kernels identify what becomes indistinguishable from zero;
- images identify what is actually reached;
- quotient constructions replace a set/group/module by classes that a map can no longer distinguish;
- exactness says that two adjacent descriptions fit with no gap and no excess.

Vakil's visual language is useful because a long exact sequence is not one isolated theorem: it is a chain of these local fitting conditions.

The “chutes and ladders” / zig-zag feeling is especially relevant for later spectral-sequence intuition. A class may have to move across one direction, lift, move in another direction, and continue until an obstruction appears. That is the same qualitative motion that later shows up as zig-zag differentials in a double complex.

## Project connection

Do **not** turn this note into a literal game specification yet.

The currently preserved design idea is only:

- begin with concrete assignment/fibers;
- reuse the same input language for structured maps;
- let exactness become a local “fits perfectly here” condition;
- later connect this to the project's exact double-cover/spinning interaction;
- keep the interaction functorial enough that the same feel survives when the mathematical objects change.

## Bibliography

The public 3Blue1Brown host describes this as a self-contained picturebook companion rather than a bibliographic survey. A separate formal bibliography was not recoverable from the host metadata used in this pass.

## Thanks

Thank you to **Ravi Vakil** for making an unusually visual treatment of exact sequences.

Thank you to **Grant Sanderson / 3Blue1Brown** for hosting the work and making the PDF easy to reach.
