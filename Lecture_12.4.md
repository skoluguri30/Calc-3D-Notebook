# Lecture 12.4 The Cross Product

Wednesday 24 January 2018

## Definition

Given two 3D vectors $\vec{u}=<a_1,a_2,a_3>, \vec{v}=<b_1,b_2,b_3>$, the cross product of $\vec{u}$ and $\vec{v}$, denoted by $\vec{u}\times\vec{v}$, is defined as $<a_2b_3-a_3b_2,a_3b_1-a_1b_3,a_1b_2-a_2b_1>$.

The cross product of two 3D vectors outputs a 3D vector (sometimes called vector product).

## Computation

Recall determinant mnemonic for a $2\times2$ matrix. Then recall the determinant of a $3\times3$ matrix.

Recall the standard unit vectors in 3D, i.e. $\vec{i},\vec{j},\vec{k}$.

Now consider this "determinant":
- Take the standard basis vectors to be the first row
- Take the coordinates of vector $\vec{u}$ as the second row
- Take the coordinates of vector $\vec{v}$ as the third row
- Compute the cofactor expansion along the first row

> Fact: The cross product of two vectors is a vector perpendicular to both vectors. We can prove this using what we know about the dot product of two orthogonal vectors.

