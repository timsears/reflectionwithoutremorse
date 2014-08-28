
This code was forked with the intention to convert it to a usable library. So far it simply builds with cabal and the directory has been reorganized a little. The only focus so far has been on the FreeMonad material. It's definitely not yet ready for hackage but was usable in some toy code I am working on.

*The original readme appears below*

Code accompanying the paper Reflection without Remorse:Revealing a hidden sequence to speed up monadic reflection

This code is organized as follows: 

* The root contains benchmarks, demonstrating how our solution improves performance
* BeforeFix contains the code of various monads before applying our techniques
* AfterFix  contains the code of the same monads with our techniques applied
* Data contains various type-aligned sequences
* CPS contains various continuation passing style constructs

To run the LogicT examples with a two continuation passing implementation do:

cabal install logict
