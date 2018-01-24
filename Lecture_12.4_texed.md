# Lecture 12.4 The Cross Product

Wednesday 24 January 2018

## Definition

Given two 3D vectors <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/c11ac14ac5b08aac93d12d395ee4f161.svg?invert_in_darkmode" align=middle width=250.29708pt height=23.48874pt/>, the cross product of <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/62e05a6a03a68c013fd2bcaf8595e812.svg?invert_in_darkmode" align=middle width=10.74777pt height=23.48874pt/> and <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/cd74c822d31d457e590f28706c11499d.svg?invert_in_darkmode" align=middle width=10.74777pt height=23.48874pt/>, denoted by <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/1ce3695d153d9cca81899df04d04a5d3.svg?invert_in_darkmode" align=middle width=39.822915pt height=23.48874pt/>, is defined as <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/9cfb492feecbf1ca87cff92e4aef138f.svg?invert_in_darkmode" align=middle width=292.546155pt height=22.83138pt/>.

The cross product of two 3D vectors outputs a 3D vector (sometimes called vector product).

## Computation

Recall determinant mnemonic for a <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/5642f62a9faca8d26da9e24171f49747.svg?invert_in_darkmode" align=middle width=36.52968pt height=21.18732pt/> matrix. Then recall the determinant of a <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/53e14fe4f3521c64c328f4a15bffeef3.svg?invert_in_darkmode" align=middle width=36.52968pt height=21.18732pt/> matrix.

Recall the standard unit vectors in 3D, i.e. <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/628cef880c1b9fad7ea48d5ab0edad60.svg?invert_in_darkmode" align=middle width=40.43919pt height=32.16444pt/>.

Now consider this "determinant":
- Take the standard basis vectors to be the first row
- Take the coordinates of vector <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/62e05a6a03a68c013fd2bcaf8595e812.svg?invert_in_darkmode" align=middle width=10.74777pt height=23.48874pt/> as the second row
- Take the coordinates of vector <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/cd74c822d31d457e590f28706c11499d.svg?invert_in_darkmode" align=middle width=10.74777pt height=23.48874pt/> as the third row
- Compute the cofactor expansion along the first row

> Fact: The cross product of two vectors is a vector perpendicular to both vectors. We can prove this using what we know about the dot product of two orthogonal vectors.

### Determinant the Direction of the Product Vector

> Note: We know the product vector is perpendicular to the original two vectors. Consider the original vectors defining a plane, the cross product is perpendicular to the plane. But which direction?

We use the Right Hand Rule to determine the direction.
- Take your right hand four fingers pointing to the direction of <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/62e05a6a03a68c013fd2bcaf8595e812.svg?invert_in_darkmode" align=middle width=10.74777pt height=23.48874pt/>
- Curl your hand into the direction of <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/cd74c822d31d457e590f28706c11499d.svg?invert_in_darkmode" align=middle width=10.74777pt height=23.48874pt/>
- Your thumb points to the direction of <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/1ce3695d153d9cca81899df04d04a5d3.svg?invert_in_darkmode" align=middle width=39.822915pt height=23.48874pt/>

> Corollary: The cross product is NOT commutative. In fact, <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/bf5544fdbcdf8919152b8c3e097a4ebd.svg?invert_in_darkmode" align=middle width=112.15908pt height=23.48874pt/>. The two products are of opposite directions.

### Determinant the Magnitude of the Cross Product

<p align="center"><img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/760f99c27b57a08d3e64f8ba82256e36.svg?invert_in_darkmode" align=middle width=139.17783pt height=16.438356pt/></p>

> Corollary: If <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/04f48c58a95935e7e6abb66dbf2064e2.svg?invert_in_darkmode" align=middle width=69.672405pt height=30.52071pt/>, then by the equation above we know <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/ecd7c33119a543347a8feb71d5079b58.svg?invert_in_darkmode" align=middle width=61.23282pt height=22.83138pt/>.

Therefore, if the cross product of two vectors are the zero vector, the two vectors are __parallel__.

> Note: You can use this formula to obtain the angle between two vectors. Generally, we just use the formula for dot product, unless this computation is simpler.

## Properties

- Anti-Commutativity (no commutativity)
- Associativity of scalar
- Distributivity of left associative vector
- Distributivity of right associative vector
- <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/0966879922bdbc1526439c17f16acfc8.svg?invert_in_darkmode" align=middle width=172.62333pt height=24.6576pt/>
- No associativity, but <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/bb267c7ddf5fe61bd8a1664d9551639a.svg?invert_in_darkmode" align=middle width=235.466055pt height=24.6576pt/>

### Theorem (parallelogram)

The magnitude of the cross product of two vectors is equal to the area of the parallelogram determined by the two vectors.

