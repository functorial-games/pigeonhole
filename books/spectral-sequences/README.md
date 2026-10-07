# Spectral sequences - reading map

This is a link-first survey. Full texts are not mirrored unless redistribution permission is clear.

## One conceptual sentence

A spectral sequence repeatedly takes homology of successive approximations to a filtered or bigraded object, producing pages
\[
(E_r,d_r)
\]
with
\[
E_{r+1}\cong H(E_r,d_r),
\]
and, under suitable convergence hypotheses, the stable page \(E_\infty\) gives the associated graded pieces of the object one wanted to compute.

A long exact sequence is the right warm-up because a filtration with only a small number of stages already produces exact-sequence bookkeeping. Spectral sequences are what happens when that staged bookkeeping keeps going.

## Read first

### Timothy Y. Chow - *You Could Have Invented Spectral Sequences*

Official AMS issue:
https://www.ams.org/journals/notices/200601/200601FullIssue.pdf

Direct article URL historically used by AMS:
https://www.ams.org/notices/200601/fea-chow.pdf

Local summary:
[../timothy-chow-you-could-have-invented-spectral-sequences/README.md](../timothy-chow-you-could-have-invented-spectral-sequences/README.md)

Best motivation-first entry from filtered complexes.

### Ravi Vakil - *Spectral Sequences: Friend or Foe?*

https://math.stanford.edu/~vakil/0708-216/216ss.pdf

Local summary:
[../ravi-vakil-spectral-sequences-friend-or-foe/README.md](../ravi-vakil-spectral-sequences-friend-or-foe/README.md)

Best double-complex/diagram-chasing bridge. Vakil deliberately proves familiar facts such as the Snake Lemma and Five Lemma using spectral sequences.

### Michael Hutchings - *Introduction to spectral sequences*

https://math.berkeley.edu/~hutching/teach/215b-2011/ss.pdf

Local summary:
[../michael-hutchings-introduction-to-spectral-sequences/README.md](../michael-hutchings-introduction-to-spectral-sequences/README.md)

Starts from the long exact sequence, then filtered complexes, then Serre.

### Ryan Wandsnider - *An Intuitive Introduction to Spectral Sequences*

https://math.uchicago.edu/~may/REU2022/REUPapers/Wandsnider.pdf

Local summary:
[../ryan-wandsnider-intuitive-introduction-to-spectral-sequences/README.md](../ryan-wandsnider-intuitive-introduction-to-spectral-sequences/README.md)

Delays formal notation, walks through Serre computations, then returns to filtrations and exact couples.

## Then use as references

### J. Peter May - *A Primer on Spectral Sequences*

https://www.math.uchicago.edu/~may/MISC/SpecSeqPrimer.pdf

Local summary:
[../j-p-may-primer-on-spectral-sequences/README.md](../j-p-may-primer-on-spectral-sequences/README.md)

Definitions, exact couples, filtered complexes, products, Serre, comparison, convergence.

### Allen Hatcher - *Algebraic Topology*, Chapter 5: Spectral Sequences

https://pi.math.cornell.edu/~hatcher/AT/SSpage.html

About 110 pages centered on the Serre spectral sequence, with Adams and additional topics.

### The Stacks Project - spectral sequences

General definition:
https://stacks.math.columbia.edu/tag/011M

Double complexes:
https://stacks.math.columbia.edu/tag/012X

Useful when exact hypotheses and categorical formulation matter more than pedagogy.

### nLab - spectral sequence

https://ncatlab.org/nlab/show/spectral%2Bsequence

Long reference page tying filtered complexes, double complexes, Grothendieck spectral sequences, stable homotopy, and convergence together.

Introductory companion:
https://ncatlab.org/nlab/show/Introduction%2Bto%2BSpectral%2BSequences

### Niles Johnson - *Constructing Spectral Sequences*

https://nilesjohnson.net/ss-construction.html

A visual aid for the filtered-chain-complex construction, explicitly meant to make the indexing/subquotient construction easier to see.

### Chromotopy - *Spectral sequences on one blackboard*

https://chromotopy.org/blog/spectral-sequences-on-one-blackboard

A compact filtration-first visual account: successive long exact sequences produce the pages and higher differentials.

## Historical and foundational sources

### Barry Mitchell - *Spectral Sequences for the Layman*

*American Mathematical Monthly* 76 (1969), 599-605.

DOI:
https://doi.org/10.2307/2316659

One of the classic beginner expositions; Chow cites it as another beginner-oriented account.

### John McCleary - *A History of Spectral Sequences: Origins to 1953*

In *History of Topology* (1999), pp. 631-663.

Publisher record:
https://www.sciencedirect.com/book/9780444823755

The historical source Chow recommends for how spectral sequences were actually invented.

### John McCleary - *A User's Guide to Spectral Sequences*, 2nd ed.

Cambridge University Press, 2001.

The standard large reference repeatedly recommended by the introductory notes above.

### William S. Massey - *Exact Couples in Algebraic Topology*

Parts I-II:
*Annals of Mathematics* 56 (1952), 363-396.
https://doi.org/10.2307/1969805

Parts III-V:
*Annals of Mathematics* 57 (1953), 248-286.
https://doi.org/10.2307/1969858

Exact couples are one of the cleanest machines that generate spectral sequences.

### Jean-Pierre Serre - *Homologie singulière des espaces fibrés. Applications*

*Annals of Mathematics* 54 (1951), 425-505.

https://doi.org/10.2307/1969485

Foundational source for the Serre spectral sequence.

### J. Michael Boardman - *Conditionally Convergent Spectral Sequences*

*Contemporary Mathematics* 239 (1999).

https://doi.org/10.1090/conm/239/03597

The important warning against treating “eventually the arrows stop” as the whole convergence story.

## Textbook routes repeatedly cited by these notes

- Raoul Bott and Loring W. Tu, *Differential Forms in Algebraic Topology*.
- Phillip Griffiths and Joseph Harris, *Principles of Algebraic Geometry*.
- Saunders Mac Lane, *Homology*.
- Charles A. Weibel, *An Introduction to Homological Algebra*, especially Chapter 5.
- Robert Mosher and Martin Tangora, *Cohomology Operations and Applications in Homotopy Theory*.
- Paul Selick, *Introduction to Homotopy Theory*.

These are commercial books unless an author/publisher supplies an explicitly redistributable copy, so this repository should keep them link/metadata-only.

## Project-level recall

The useful conceptual ladder for this game is:

\[
\text{pigeonhole}
\to
\text{fibers}
\to
\text{quotient by equal images}
\to
\text{image/kernel}
\to
\text{exact sequence}
\to
\text{filtered object / double complex}
\to
\text{successive pages}
\to
E_\infty.
\]

The point is not to make a “spectral sequence simulator” first. The point is to preserve one interactional idea as the objects become richer.
