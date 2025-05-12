# syntaxmachines

This repository covers the computational (non-graphical) part of working with automata. Here range from algorithms of minimisation of automata to synthesis of automata out of a regular expression, and much more.

The language used in this context is Wolfram (Mathematica), due to the convenience of working with nested lists (as discussed later). How the automata will be represented in this language and many more abstractions can be found on "foundations.txt".

Since working with automata requires a strong sense of formal languages, regular languages and many more basic concepts, this knowledge is already assumed. However, even though it's not its main goal, this repository includes a few programs and examples of formal languages.

Why learning automata theory? While many people choose to study this subject as an introduction to the bigger picture of computer science, formal languages and automata theory is a really rich field on its own. For example, in compiler design finite automata are used during lexical analysis to break source code into tokens—like keywords or operators by matching patterns based on regular languages. Automata and its pattern matching capabilities can be used in bioinformatics, where  tehy're used to search for specific DNA sequences within much larger genomic data. Since DNA can be viewed as a long string composed of four characters (A, C, G, T) which are the four nitrogenous bases found in the DNA (uracil only appears in the RNA), automata can efficiently look for known genetic patterns or mutations, which is paramount in understanding genetic markers associated with diseases, including cancer.
