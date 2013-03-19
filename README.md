WebGL Experiments
==================
This repository contains my experiments learning 3D graphics and WebGL.

[Flying Cubes] [1]
--------
An interactive simulation of flying cubes written in WebGL. The user can
turn gravity on and off, simulate black hole gravity at the center of the
universe, decelerate the flying cubes, and change the tilt and zoom of
the camera.

The controls are:
* g : Toggle gravity
* c : Apply black hole gravity 
* b : Brakes - deccelerate the cubes
* arrows : Rotate the perspective
* < and > : Zoom in and out

After a first attempt at this project using the Three.js library I realized
Three was abstracting away too much of the details for me to really understand
what was going on. I tried again using the tutorials I went through at
www.learningwebgl.com as a starting point. If anyone sees any egregious bad
practices please let me know - I kindof just wing it when it comes to javascript!

LaTeX
-----
There are a lot of new concepts and WebGL process specifics that I've found hard
to absorb quickly. To help myself learn faster and retain what I learn longer
I created a LaTeX note sheet. Hopefully I can synthesize what's important and 
improve my notes iteratively as my understanding grows.

Thanks
------
Many thanks to the following resources:
* www.http://learningwebgl.com
* http://www.opengl-tutorial.org/ 
* WebGL: Up And Running - by Tony Parisi

[1]: http://flyingcubes.davidmoench.com
