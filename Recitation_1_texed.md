<style>
.acc {color: red}
</style>

# Recitation 1

This recitation talks about <span class='acc'>logistics</span> stuff and basic geometric shapes in three dimension space. <br />
Tuesday 23 January 2018

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Logistics](#logistics)
- [Basics](#basics)
- [Basic Shapes in 3D](#basic-shapes-in-3d)
- [Vectors](#vectors)
  - [Change of Basis](#change-of-basis)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Logistics

TA office: Wean 7209 <br />
E-mail: Iganedi@(usual stuff) <br />
Office hour: Mondays 3:30-5:30 <br />

## Basics

In three dimensions, we care about functions of three variables, i.e. <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/0ed04ca2a2f11ef9f60d5eaf9d444b14.svg?invert_in_darkmode" align=middle width=78.238215pt height=24.6576pt/> <br />
We can think of 3D surfaces as 2D subspaces.

## Basic Shapes in 3D

1. What is this shape? <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/4a2bb1d1e991d6dd7158638a1e1c5a6c.svg?invert_in_darkmode" align=middle width=83.16957pt height=26.76201pt/>

We can decompose the formula into 2D coordinates respectively:

- Consider only variables <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.3951pt height=14.15535pt/> and <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/f93ce33e511096ed626b4719d50f17d2.svg?invert_in_darkmode" align=middle width=8.367645pt height=14.15535pt/>: It appears to be a parabola.
- Consider only variables <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode" align=middle width=8.6493pt height=14.15535pt/> and <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/f93ce33e511096ed626b4719d50f17d2.svg?invert_in_darkmode" align=middle width=8.367645pt height=14.15535pt/>: It appears to be a parabola as well.
- Consider only variables <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.3951pt height=14.15535pt/> and <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode" align=middle width=8.6493pt height=14.15535pt/>: It appears to be circle.

With this method, we can conjure the image of this 3D shape. It is a 3D parabola.

> Note: The "surface" is only the outside boundary, not including the volume inside.

2. What about <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/00660670d67b722210c3fdf69bdc576d.svg?invert_in_darkmode" align=middle width=83.021235pt height=26.76201pt/>?

This is a cylinder.

> Trick: When one variable is not defined (in this case <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/f93ce33e511096ed626b4719d50f17d2.svg?invert_in_darkmode" align=middle width=8.367645pt height=14.15535pt/>), we can extend the shape in that direction infinitely.

3. What about <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/fd2648516f2a9828eff1aca4740dd572.svg?invert_in_darkmode" align=middle width=125.45841pt height=26.76201pt/>?

This is a sphere.

4. What about <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/cef423376d52f38adb349bbc31311708.svg?invert_in_darkmode" align=middle width=97.06785pt height=22.83138pt/>?

This is a plane.

To visualize a plane, we can just pick three points and connect the triangle to visualize.

## Vectors

Vectors are just some "arrows" with a certain "direction".

> Note: Vectors do not include a definition of their basis. That is, you can define the basis of a vector to be whatever basis you want. In fact, an important thing in this course is change of basis.

### Change of Basis

Consider vector <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/ecd1b091a63eca010935a2ce3dc18585.svg?invert_in_darkmode" align=middle width=81.968205pt height=33.99099pt/> in the normal coordinate plane <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/7bfeeed924f59acfb7204bb2c8fbdf80.svg?invert_in_darkmode" align=middle width=156.403995pt height=24.6576pt/>. Now change the coordinate into a new basis <img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/3d5141c8a5ed8cd4b0b3f9f8b8f60236.svg?invert_in_darkmode" align=middle width=155.03037pt height=24.6576pt/>. How do we correspondingly rewrite the vector?

> Since the new basis is orthogonal, we can just project the original vector onto the new basis. We use dot products for the projections.

<p align="center"><img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/47a44fdb40c516a9837f5ca310e1f0c9.svg?invert_in_darkmode" align=middle width=101.708475pt height=21.104985pt/></p>
<p align="center"><img src="https://rawgit.com/SAMFYB/Calc-3D-Notebook/master/svgs/be30ec3f3df8ed29f84a448d898d9904.svg?invert_in_darkmode" align=middle width=88.922955pt height=21.104985pt/></p>

