# Review for Midterm 1

## Limit

Consider $\lim_{(x,y)\rightarrow(a,b)} f(x,y)$.

For example, consider $f(x,y)=\frac{x^3-y^3}{x^2+xy+y^2}$. The limit going to $(0,0)$ is $0$.

We can factor to solve it.

What about $f(x,y)=\frac{y^2}{(x-y)^2}$? The limit does not exist.

We can see that by fixing $x=0$ and $y=0$ respectively, it does not reach the same limits.

A stronger method: switching to polar coordinates.

For example, $\frac{sin(x^2+y^2)}{x^2+y^2} = \lim_{r\rightarrow 0} \frac{sin(r^2)}{r^2}$.

Then, we are left with a single variable and we can use L'Hopital's Rule.

Similarly, when we are considering the limit going to $(0,0)$, we can always use this method.

Idea: substitute $x,y$ with $sin,cos$, and ignore the $\theta$ when $r$ is not canceled. Vice versa.

Consider $\frac{x^2-y^6}{xy^3}$. The limit does not exist.

We can show that by taking $x=t^3$ and $y=t$.

## Geometry Intuition

Consider $f(x,z)=4x^2+8x+16z^2$. Graph the level curves.

$$ \begin{align}
  k &= 4x^2 + 8x + 4 - 4 + 16z^2 \\
  k+4 &= 4(x+1)^2 + 16z^2
\end{align} $$

The level curves are ellipses. $k+4\geq0$, $k\geq-4$.

Then, consider $y^2=f(x,z)$, i.e. $y^2=4(x+1)^2+16z^2-4$.

In the $z-y$ plane, $y^2=4+16z^2-4=16z^2$. Try graph this planar curve.

However, the generic curve is such that $x\neq0$. The curve is a bit curvy.

### Generic Intuition

- $x^2+y^2=C$: circle
- $ax^2+by^2=C$: ellipse
- $ax^2+by^2+cz^2=K$: epllipsoid
- $c<0$ above: cone
- $z=x^2+y^2$: paraboloid

### Basic Structures

Consider two points $P(2,3,1), Q(4,-2,-1)$.

A vector $\vec{v}=P-Q=<-2,5,2>$.

Then the line through the points is given by $r(t)=P+t\vec{v}=<2-2t,3+5t,1+2t>$.

For parametric form, extract $x(t), y(t), z(t)$.

For symmetric form, $t=\frac{x-2}{-2}=\frac{y-3}{5}=\frac{z-1}{2}$.

Consider two vectors $\vec{v_1}, \vec{v_2}$ and point $P$.

The normal vector of the plane: $\vec{n}=\vec{v_1}\times\vec{v_2}$.

Take $r_0=\vec{P}$.

Then, the plane is given by $\vec{n}\cdot(\vec{r}-\vec{r_0})=0$.

For three points, choose a base point, do the same thing.

For a line $r(t)=<12-t,1+8t,4+6t>$, the __direction vector__ is given by $\vec{n}=<-1,8,6>$.

For a plane $4x+8y-2z=C$, the normal vector is given by $\vec{n}=<4,8,-2>$.

For two planes $x+y-z=3$ and $3x-2y+6z=4$.

Solve for the intersection by eliminating variables and taking parameter.

In this case, $x=t$, $z=\frac{10-5t}{4}$, and we can then find $y(t)$.

If we have the normal vectors of two planes $n_1,n_2$.

The intersection is given by $r(t)=P_0+t\vec{n_1 \times n_2}$.

This only works for planes because plane intersection gives us lines.

For general surfaces, we have to use the former method of substitution and parametization.

And note, in the general case, we have to be careful of the domain of the parameter.

