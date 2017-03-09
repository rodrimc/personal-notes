A deterministic and terminating semantics for the synchronous language Céu
==========

Céu is a reactive synchronous language designed for supporting the
development of safe concurrent programs. The language has been designed
to facilitate the specification of programs that constantly react to
external stimuli (events) and that have concurrent lines of execution.
Céu relies on the synchronous hypothesis, that is, programs produce
output synchronously with their inputs (i.e., conceptually reactions
take no time). The language was originally designed having as main target
embedded systems, but its generic event handling and concurrent built-in 
constructs allow the straightforward use of the language in the development
of a broader range of reactive systems.

In this work we have formalized the denotational semantics of Céu. There are
two main results of this work: i) we have proved that Céu reactions are
deterministic, that is, programs always produce the same output and execute
the same steps for a given sequence of external events; and ii) we have
established the initial steps to prove that Céu reactions are terminating,
that is, they always terminate. 

As future work we intent to finish the termination proof and use a proof 
assistant software to validate our work.
