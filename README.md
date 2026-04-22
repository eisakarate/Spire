# Spire - a Co-HTIS-based document search engine.

Project Spire is a document search engine based on the Co-HITS algorithm.  This project is a continuation of the initial research project completed as part of a master's program in Graph Algorithms.  

## Current Status

The project is currently in a proof-of-concept phase:

- Corpus conversion to a bipartite graph is implemented
- Co-HITS algorithm is implemented
- One-Mode project algorithm is implemented
- A rudimentary `main()` is implemented to connect the three implementations.

## Project Goals

Initial project goals are:

1. Author wiki, citations.
2. Improve the Corpus engine to allow specification of customized `lexicon`.
3. Possibly implement `SQL Parser` to extract database entity infomration from `*.sql` DDL using `Pushdown Automata Finite State Machine`.
4. Improve parameterization for better control over Co-HITS
