===================================
Hilbert Space and Quantum Mechanics
===================================

:date: 2020/5/3

Hilbert space is a concept of multilinear algebra, and the tensor product of Hilbert spaces is the "language" that the quantum mechanics speaks. Or more precisely, we usually model quantum phenomena in the language of multilinear algebra. Thus, understanding Hilbert space is a good start and probably a must step to understand the knowledge of quantum mechanices for knowing quantum information and quantum computing.


*************
Relationships
*************

By comparing different relationships, we may figure out the knowledge roadmap. The term "original" and "extended" may or may not in historic sequence. The terms intend to indicate the direction of logic deriviation.


Mathematical Relationships
--------------------------

+------------------+----------------------------------------------------------+
| Original Concept | Extended Concept                                         |
+==================+==========================================================+
| scale, vector    | tensor                                                   |
+------------------+----------------------------------------------------------+
| Hilbert space    | tensor product of Hilbert spaces (still a Hilbert space) |
+------------------+----------------------------------------------------------+
| linear algebra   | multilinear algebra                                      |
+------------------+----------------------------------------------------------+
| vector space     | topological vector space                                 |
+------------------+----------------------------------------------------------+


* Hilbert space is

  * a vector space
  * a topological vector space
  * a complete inner product space


* A topological vector space is both of a vector space and a topological vector space.

  * Hibert space is an example of topological vector space.


Relationship of Quantum Concepts to Mathematics
------------------------------------------------

+---------------------+-----------------------------------------------+-------------------+
| Quantum Concepts    | Mathematics                                   | Example           |
+=====================+===============================================+===================+
| - quantum state     | vector in Hilbert space                       | \|x>              |
| - qubit             |                                               |                   |
+---------------------+-----------------------------------------------+-------------------+
| - two states        | tensor product of two vector in Hilbert space | \|xy>             |
| - bell state        |                                               |                   |
+---------------------+-----------------------------------------------+-------------------+
