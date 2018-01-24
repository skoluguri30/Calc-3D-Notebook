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

### Determinant the Direction of the Product Vector

> Note: We know the product vector is perpendicular to the original two vectors. Consider the original vectors defining a plane, the cross product is perpendicular to the plane. But which direction?

We use the Right Hand Rule to determine the direction.
- Take your right hand four fingers pointing to the direction of $\vec{u}$
- Curl your hand into the direction of $\vec{v}$
- Your thumb points to the direction of $\vec{u}\times\vec{v}$

> Corollary: The cross product is NOT commutative. In fact, $\vec{u}\times\vec{v}=-\vec{v}\times\vec{u}$. The two products are of opposite directions.

### Determinant the Magnitude of the Cross Product

$$|\vec{u}\times\vec{v}|=|\vec{u}||\vec{v}|\sin{\theta}$$

> Corollary: If $\vec{u}\times\vec{v}=\vec{0}$, then by the equation above we know $\sin{\theta}=0$.

Therefore, if the cross product of two vectors are the zero vector, the two vectors are __parallel__.

> Note: You can use this formula to obtain the angle between two vectors. Generally, we just use the formula for dot product, unless this computation is simpler.

## Properties

- Anti-Commutativity (no commutativity)
- Associativity of scalar
- Distributivity of left associative vector
- Distributivity of right associative vector
- $\vec{u}\cdot(\vec{v}\times\vec{w})=(\vec{u}\times\vec{v})\cdot\vec{w}$
- No associativity, but $(\vec{u}\times\vec{v})\times\vec{w}=(\vec{u}\cdot\vec{w})\vec{v}-(\vec{u}\cdot\vec{v})\vec{w}$

### Theorem (parallelogram)

The magnitude of the cross product of two vectors is equal to the area of the parallelogram determined by the two vectors.

