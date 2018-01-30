# Recitation 2

## Dot Products and Cross Products

| Dot Products | Cross Products |
| ------------ | -------------- |
| <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/e91a1615eca7e17bd531e8fcfd94f53b.svg?invert_in_darkmode" align=middle width=273.811725pt height=32.16444pt/> | a vector, pseudo-determinant, <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/4f0a1ba3d074b605185d655f649756bc.svg?invert_in_darkmode" align=middle width=67.84437pt height=24.6576pt/> |
| projection | area of parallelogram, orthogonal to the two vectors |
| dot product is 0: perpendicular | cross product is zero: parallel |

> The volume of a parallelepiped is given by <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/d78b23c8a9a0796b2a0f2977f2c66d74.svg?invert_in_darkmode" align=middle width=63.9639pt height=32.16444pt/>.

## Some Problems

Consider <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/abe59540e06f29f98585ac0758b7b2e6.svg?invert_in_darkmode" align=middle width=66.799755pt height=32.16444pt/>. This is __not__ well-defined.

> It can mean <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/1b483e1608e8c24a957e3ac3238aa65f.svg?invert_in_darkmode" align=middle width=78.55584pt height=32.16444pt/>, or the other way. They might __not__ be equal.

Consider <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/ea2b81f1a15d19eba0e436c0e20ed40b.svg?invert_in_darkmode" align=middle width=50.3613pt height=32.16444pt/>. This is __not__ well-define.

Consider <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/3b42f9a86e48c6a65eb6b2e1392894eb.svg?invert_in_darkmode" align=middle width=67.818465pt height=32.16444pt/>.

> This is 0 because the cross product gives a vector perpendicular to <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/72dfde2d31e141084b736c9a435ad64d.svg?invert_in_darkmode" align=middle width=10.747935pt height=32.16444pt/>.

Consider 4 points in 3D:
- <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/006d1403a90092303085ab506fa043ba.svg?invert_in_darkmode" align=middle width=99.59466pt height=24.6576pt/>
- <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/266f14f321dd6e2f1b965b3574250e69.svg?invert_in_darkmode" align=middle width=99.75339pt height=24.6576pt/>
- <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/2d17bddabc487e9265ce42e0ffe3d5af.svg?invert_in_darkmode" align=middle width=86.580945pt height=24.6576pt/>
- <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/50c349e2a6f5f3775468c59b9fa9665c.svg?invert_in_darkmode" align=middle width=86.96787pt height=24.6576pt/>

Are these points coplanar (they all lie in the same plane)?

> Suppose they are coplanar. Then consider three vectors given by these points. They give a parallelepiped. If they are coplanar, the parallelepiped has volume 0. Use this fact to solve the problem.

Consider the area of parallelogram projected to <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/65f1b48fb5f326a680b0f7393b9d8b6d.svg?invert_in_darkmode" align=middle width=18.044235pt height=14.15535pt/>-plane by points <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/ce774d712c005564956a4eb41f571585.svg?invert_in_darkmode" align=middle width=51.226065pt height=22.46574pt/>.

> We have two vectors <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/046c75231fe47355aff9b3d83818db7e.svg?invert_in_darkmode" align=middle width=279.587055pt height=31.79913pt/>. Their projections onto <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/65f1b48fb5f326a680b0f7393b9d8b6d.svg?invert_in_darkmode" align=middle width=18.044235pt height=14.15535pt/>-plane are simply <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/6b72e652da41d12a49465182e8b35901.svg?invert_in_darkmode" align=middle width=136.986135pt height=21.18732pt/>. Then append 0 to the third coordinates, and do the normal cross product.

