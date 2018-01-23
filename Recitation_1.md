# Recitation 1

This recitation talks about logistics stuff and basic geometric shapes in three dimension space.

## Logistics

TA office: Wean 7209
E-mail: Iganedi@(usual stuff)
Office hour: Mondays 3:30-5:30

## Basics

In three dimensions, we care about functions of three variables, i.e. $f(x,y)=z$

We can think of 3D surfaces as 2D subspaces.

## Basic Shapes in 3D

1. What is this shape? $x^2+y^2=z$

We can decompose the formula into 2D coordinates respectively:

- Consider only variables $x$ and $z$: It appears to be a parabola.
- Consider only variables $y$ and $z$: It appears to be a parabola as well.
- Consider only variables $x$ and $y$: It appears to be circle.

With this method, we can conjure the image of this 3D shape. It is a 3D parabola.

> Note: The "surface" is only the outside boundary, not including the volume inside.

2. What about $x^2+y^2=1$?

This is a cylinder.

> Trick: When one variable is not defined (in this case $z$), we can extend the shape in that direction infinitely.

3. What about $x^2+y^2+z^2=p^2$?

This is a sphere.

4. What about $x+y+z=d$?

This is a plane.

To visualize a plane, we can just pick three points and connect the triangle to visualize.

## Vectors

Vectors are just some "arrows" with a certain "direction".

> Note: Vectors do not include a definition of their basis. That is, you can define the basis of a vector to be whatever basis you want. In fact, an important thing in this course is change of basis.

### Change of Basis

Consider vector $\vec(v)=(2,1)$ in the normal coordinate plane $x_0=(1,0),y_0=(0,1)$. Now change the coordinate into a new basis $x=(1,1),y=(-1,1)$. How do we correspondingly rewrite the vector?

> Since the new basis is orthogonal, we can just project the original vector onto the new basis. We use dot products for the projections.

$$<-1,1>\cdot\vec(v)$$
$$<1,1>\cdot\vec(v)$$

