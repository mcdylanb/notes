# Proof
- a tool to distingiush correct algorithms with incorrect ones

## Parts (Mathematical Proof)
- clear, precise statement of what you're trying to prove
- set of assumptions of things which are taken to be true and henced used sa part of the proof
- chain of reasoning which takes you from these assumptions to the statement you trying to prove.

Expressing Algorithms
- clarity should be the goal 

3 types of language used in expressing Algorithms
1. English
2. Pseudocode
3. a real programming language

Problems and Properties
- we need a careful description of the problem that it is intended to solve.

problem specifications
1. the set of allowed input instances
2. the required properties of the algorithm output 

Common trap in specifying the output requirements of a problem
1. asking an ill defined questions
2. creating compound goals

1.3.1 Demonstrating incorrectness
COunter Example
- best way: prodouce an instance in which it yields an incorrect answer

Good Counter Example Properties
1. Verificability
    - calculate what answer your algorithm will give in this instance
    - display a better answer so as to prove the algo. didn't find it.
2. Simplicity
    - good counter-example have all unnecessary details boiled down
3. Think Small
    - small examples
        - easier to verify and reason about
4. Think Exhaustively 
5. Hunt for the weakness
    - always take the biggest
6. Go for a tie
    - everything is the same size
7. Seek Extremes

1.3.4 Induction and Recursion

Combinational Objects
Name | Meaning | Example
--- | --- | ---
Permutations | arrangements, or orderings of items | Arrangement, ordering, tour, seuence
Subsets | - selections from a set of items - order does not matter | CLuster, committee, packaging, collection, group, selection
trees | Hierarchical relationship between items | hierarchy| hierarchy, ancester , taxonomy, dominance, relationship, descendant relationship 
Graphs | Relationships between arbitrary pairs of objects| Network, Circuit, web, relationship
Points | represents locations in some geometric space | sites, positions, data, records, locations
Polygons |represents region in some geometric space | shapes, regions , configuration, boundaries
Strings| represents sequence of characters or patterns | text characters, patterns, labels