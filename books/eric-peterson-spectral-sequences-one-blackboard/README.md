# Eric Peterson - *Spectral sequences on one blackboard*

## Source

Eric Peterson, 10 March 2011:

https://chromotopy.org/blog/spectral-sequences-on-one-blackboard

## Rights status

Link-only. Public author-hosted article; no redistribution license was assumed.

## Full-recall summary

Peterson starts from the fact that a homology functor turns short exact/cofiber sequences into long exact sequences.

A one-step decomposition is manageable with one long exact sequence. But mathematical objects often arrive with an entire filtration:
\[
\cdots\subset F_{i+1}\subset F_i\subset F_{i-1}\subset\cdots .
\]

Each adjacent pair gives a quotient/cofiber \(F_i/F_{i+1}\), hence a long exact sequence in homology. Put all those exact sequences beside one another and connecting maps link the quotients. Those linking maps form the first differential.

Take homology with respect to that differential: this removes cycles/boundaries already detected one filtration level away.

The survivors admit new maps that reach two filtration levels away. Those are the next differentials. Repeat.

So a spectral sequence is pictured as a mechanism that repeatedly asks:

> Which apparent classes are genuine, and which only look genuine because we have not yet compared far enough across the filtration?

That is an excellent game interpretation.

## Convergence warning

Peterson explicitly warns that convergence is not merely a slogan about “eventually the arrows stop” and points to Boardman's *Conditionally Convergent Spectral Sequences* as the serious treatment.

When convergence behaves well, the stable page gives filtration quotients of the desired homology. One still has an extension problem: the pieces must be reassembled.

## Examples in the article

Peterson sketches:

- the skeletal filtration of a CW complex, recovering cellular homology;
- the Atiyah–Hirzebruch spectral sequence for a generalized homology theory;
- the Serre spectral sequence from a fibration filtered over the base;
- a bar-construction example producing Tor groups;
- a small filtration of \(D^2\) in which two apparent classes kill one another by the next page.

The last example is especially suitable for a game prototype: put two things on the board that look independently alive, then introduce the next-range relation and watch them cancel.

## Bibliographic trail

The article directly invokes:

- J. Michael Boardman, *Conditionally Convergent Spectral Sequences*.
- the Atiyah–Hirzebruch spectral sequence;
- the Serre spectral sequence;
- the bar construction and Tor.

## Thanks

Thank you to **Eric Peterson**.

Thank you also to **J. Michael Boardman**, **Michael Atiyah**, **Friedrich Hirzebruch**, and **Jean-Pierre Serre** for the named constructions and convergence work used in the article's exposition.
