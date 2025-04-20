# Group-Theory
For doing various calculations in abstract-algebra group theory

## Point, Space Groups, Polytopes
Folder with notebooks for working with rotations, reflections, point groups, space groups, and polytopes (polygons, polyhedra, ...)

## Group-Theory Calculations
Including:
- Construction of groups from both elements and group-operation tables
- Filling out a group with its operation and some starter elements
- Reducng an abelian group to a product of cyclic groups
- Finding conjugacy classes and group characters
- Finding a group's center and whether a subgroup is "normal"
- Finding all subgroups, grouped as sets of conjugate ones (normal: only one)
- Finding the cosets of a subgroup
- Finding the quotient group from dividing a group by a normal subgroup
- Finding the commutator of two subgroups of a group (departure from being commutative)
- Finding composition series:
  - Derived series: each one is the commutator subgroup of the previous one by itself
  - Lower central series: like the above, but of the previous one and the original one
  - Upper central series: find the subgroup whose commutator with the original one is the previous one

## Group-Theory Calculations Test Suite
For testing the functions in "Group-Theory Calculations". For doing this testing, it has constructions of several groups and grouplike objects:
- All one element
- Horizontal and vertical strips
- Maximum and minimum of elements
- Latin squares: they have division and reduced ones have an identity, but need not be associative
- Cyclic (rotate a polygon), dihedral (rotate and reflect a polygon) groups
- Symmetric (all permutations), alternating (all even permutations)
- Signed permutation groups: symmetry group of square, cube, octahedron, and higher-dimensional versions
- Hyperdiamond group: symmetry group of the 4D hyperdiamond or 24-cell

## Group Characters
Something that I have included here because of the nice mathematical patterns that some group-character tables have.

What are group characters? A group can be implemented with a set of matrices, a "representation" (rep), and a rep that cannot be reduced to any other reps is an "irreducible representation" (irrep). The character of a representation is the trace of each element's matric, the sum of each matrix's diagonal elements. Elements in the same "conjugacy class" have the same trace value, so the character values are a matrix with dimensions (irrep) and (class), dimensions with equal length.

Character tables for:
- Cyclic and dihedral groups
- Symmetric and alternating groups
- Signed-permutation groups up to 4 dimensions
- Quaternionic groups
- Icosahedral and hyperdiamond groups

This notebook also discusses some solution techniques, like using quotient-group characters and using constraints on possible character values.

## Finite Simple Groups, Weyl Groups, and Coxeter Groups
Orders (sizes, numbers of elements) of these groups.

Also orders of groups of matrices of modulo-something integers and of finite algebraic fields.

## Generalized Dihedral Groups
For generators a and b, and integers n, m, r, s:
- a^n = e
- b^m = a^s 
- a * b = b * a^r
For some n and m, what constraints on r and s? What conjugacy classes?

## Galois groups of nth roots
The Galois group of a polynomial is, to a first approximation, the group of interchanges of roots of it.

## Braid Groups, Artin Groups
Braid groups? Imagine some parallel strands, and imagine interchanging neighboring ones. Combinations of these interchanges form a group. Artin groups generalize braid groups.
	
## Invariants of Lorentz and Poincare Groups
Strictly speaking, their Lie algebras. These are conserved quantities like total angular momentum.

## Lorentz, Poincare, and Supersymmetry Algebras
Attempts to test commutation and anti-commutation relations for Lorentz (rotations and boosts), Poincare (Lorentz and space and time shifts), and supersymmetry (Poincare and SUSY generators).
