## Final Paper

Due by the end of the semester.

### How you will be evaluated.

50% results, 50% effort.  Effort can be demonstrated by keeping a log
of what you're doing and why, regardless of success, and adding
that log to the end of the paper.

### Purpose

Read/modify/create a graphics program, or tutorial, and write a paper
on what you learned, did, or tried to do but were unsuccessful.
Please also submit source if you wrote/modified code.
I estimate a 3 page minimum paper per student.

I expect each student to find something they want to learn more about or to do,
and to be self directed toward an objective of their choice, whether it is
reading to learn a new graphics concept, reading to understand how an
implementation works, or writing/modifying code for some decided objective.
Take a look at all of the ideas below, or choose something else.  For the tutorials listed below,
I recommend looking at the objectives and see if anything looks interesting
to you.  For the codes below, I recommend compiling and running many of projects,
see anything you'd like to learn about or change.

With that said, you don't have to stick to one project.  You can try some, do well,
or do poorly, and change projects of study, but document it all.  I recommend
keeping a log of what you're doing, and include that at the end of the paper,
so that I can see what you spent your time on. If you worked on
something for 4-8 hours, were unable to complete what you wanted to do, you need
to write that down and why, and what you learned not to do.
Because if you don't document it, I don't know that you did
it.  Being unsuccessful at a thing or two is good, it means you stretched yourself.
Towards a self-directed objective, failure to achieve the objective can still
be a valuable experience and should be documented and learned from.
I never learned anything of value
from a game of chess in which I won, only those in which I lost.

When you start working on something, I'm available via email to help with
questions/directions.  I expect some people to have difficulty with C, for instance; but
document what you learned.


### Project ideas (in order of perceived difficulty).

#### Study tinyrender or tiny raytracer

https://github.com/ssloy/tinyrenderer/wiki

The wiki on this site is great.  I made a fork of the code on github so that projects can be build with CMake/Visual Studio https://github.com/billsix/tinyrenderer)

Tiny Renderer

How is a triangle rasterized in screen space?  Our
class reduced a set of vertices to NDC, but OpenGL itself fills
the polygons in.  There's a lot of other good material there.  Study something
and write about what you learned.

Tiny Raytracer

The wiki on this site is great.  I made a fork of the code on github so that projects can be build with CMake/Visual Studio https://github.com/billsix/tinyraytracer)

Ray tracing provides better looking graphics than real-time graphics systems.
Tiny raytracer explains how to make a simple raytracer in C++ (https://github.com/ssloy/tinyraytracer/wiki).
Read the tutorials, run the code, what did you learn?
We never covered raytracing in class other than mention the name.  This involves
a bit of math, more than we covered in class.


Tiny Raycaster

https://github.com/ssloy/tinyraycaster/wiki/Part-0:-getting-started  The wiki on this site is great.

It shows how to make a video game like the original Doom game in the mid 1990s

I made a fork of the code on github so that projects can be built easily with CMake/Visual Studio https://github.com/billsix/tinyraycaster)


#### Ray Tracing in One Weekend

Excellent Book Series Full of Code and Explanations

RayTracing in One Weekend

RayTracing: The Next Week

RayTracing: The Rest of Your Life

https://raytracing.github.io/

#### Study Computer Graphics from Scratch

https://gabrielgambetta.com/computer-graphics-from-scratch/

This book covers a lot.  Raytracing, drawing lines in screen space,
filling triangles, shading triangles, etc.  There's a lot to learn
here on topics we haven't talked about.


#### Read a series of OpenGL tutorials and write about what you learned

I've found that reading intro material which was written by different
authors helps me to futher my understanding of fundamentals.

In particular, either study something not covered in class, or discuss
how their explanations differed/compared to mine, and what you learned
in the process.

##### http://opengl-tutorial.org

Language: C

Code: My branch with fixes regarding camera management on Linux https://github.com/billsix/ogl

##### https://www.adriancourreges.com/blog/

Study rendering techniques used by real video games



#### Study "Code the Classics"

Language: Python

Codebase: https://github.com/billsix/Code-the-Classics .  (Original source,
https://github.com/Wireframe-Magazine/Code-the-Classics)  I modified
it in my github to have a requirements.txt file so that visual studio can run
it unmodified, you just need to set the startup project.

There is an book for sale covering these classic games, which
have been written in Python using PyGameZero.  Study the code, all of which is
in 2D.  Study collision detection, imaging, usage of transparency, input.
Study the data structures used and why.
Compare and constrast PyGameZero with glfw and glut.


#### Make your own game/graphics project

Come up with an idea for something you'd like to write and write it.  Perhaps a game,
simulation, 3D graphing calculator, etc.



#### Study a simple implementation of Minecraft in Python and describe how it works.

Language - Python

OpenGL 2.0

https://github.com/billsix/Minecraft (the Python version, based off of
https://github.com/fogleman/Minecraft). I updated it for Visual Studio 2019, and modern Python.

#### PortableGL

A pure software only implementation of OpenGL.  You can
study how any aspect of the opengl library can be implemented.

Built with CMake on Windows, MacOS, and Linux, with example
programs to drive the study of the code.

https://github.com/billsix/PortableGL

#### Study the implementation of pyMatrixStack

https://github.com/billsix/pyMatrixStack

For the reader familiar with linear algebra, study the implementation of pyMatrixStack.
This project contains the product of all of the math that we studied in the first half
of the class, and including matrix definitions of all transformations.


#### Study the implementation of the perspective demo

Language - Python

OpenGL 3.3 Core Profile

https://github.com/billsix/modelviewprojection/blob/master/mvpVisualization/5/demo5.py


#### Upgrade a program from OpenGL2 to OpenGL3.3 core profile.

Language - C++ (for OpenGL Blue book), Python for my modelviewprojection demos.

The pyramid example in Ch8 of the BlueBook would be an excellent one to do,
as it involves simple transformations, simple geometry, lighting, and texturing.


#### Study the implementation of Minecraft in C.

Language - C

OpenGL 3.3 Core Profile (no fixed function code; shader based, which we will cover
soon)

https://github.com/billsix/Craft , modified from https://github.com/fogleman/Craft
to use core profile, and to be easily compiled with Visual Studio 2019 (via
VS2019's cmake integration)



#### Study the McNopper demos

Language - C

OpenGL Core Profile (no fixed function code; shader based, which we will cover
soon)

https://github.com/billsix/McNopperOpenGL

There are a ton of cool demos here, many of which are quite advanced.  One of the
demos shows a cool water effect, and one does order-independent blending.  There's
a lot of cool stuff there to study.
