---
title: Chaos Theory
description: something
author: Nitica
date: 31 July, 2011
tags: biology
---

Sthitadhi - exponential divergence of infinitesimally close trajectories..
Cantor's dust: self similar structure (Generated by recursively removing the middle 1/3rd of a line segment)- end result is an infinite disconnected number of points
Dimension of this set is not 1('cos it's not the whole line), not 0 cos it isn't a point. Fractal- fractional dimension..
Concept of length- N.(dr^dim) must be finite.. For a st line it's 1.. Cantor's dust - has dim 0.68 (Hausdorff dimension)

Equilateral triangle game- take a point in the interior, find the nearest vertex and double the distance from this vertex to get the next point. If a point goes outside the triangle, you lose. Claim- If you do it randomly, you almost always end up losing.. :(

How can you win?- Don't enter the forbidden area- the middle of the four triangles. To not enter this area, don't enter a similar forbidden area in the other triangles.. Keeps repeating. Forms another self repeating structure.. You do end up with infinite number of points- (Hausdorff dimension = 1.58 < 2)- Sierpinski gasket..

To analyse this, set up a co-ordinate system- 3 co-ordinates for a point even if it's redundant.. x = ratio of distance of point from the nearest base/ total length.. 
Sides have x=0, etc.. vertices have x = 1 etc. For all points- x + y + z= 1.
transformation- every step in the game transforms (x, y, z) to (2x, 2y-1, 2z) if the nearest vertex is y =1.
Binary system of numbers used (She's fond of computing)
An actual example-
x0 = 0.0101
y0 = 0.100111
z0 = 0.000101
After iterations y3 becomes -0.001- you lose!

In binary- doubling numbers only shift the binary point one place.  Therefore the only points that are Sierpinski have the sequence hdf.0dsnjs, ndcb.1ddn, dfkd.0jbcj
CAn be shown that such a sequence retains its form and remains a Sierpinski point..

Butterfly effect- points that start close to a Sierpinski point need not be so themselves. They get kicked out after a number of iterations..
Determinism- started with Newton's laws.
(Seems to) have been dealt with a blow by relativity, QM, chaos..
Chaos isn't against Newton's laws (against determinism) merely because we do not know everything exactly with infinite precision. 
Three body problem- Whoever solves it will be known.
Two methods- differential equations, phase space (introduced by Poincare)
was intrigued by the phase space plot of the problem- didn't want to believe in it, so he abandoned it..
Horizon of predictability- self explanatory.


Sthitadhi-
To quantify chaos- lyapunov exponent
delta xf = exp(lambda t)* delta xi - lambda is called the lyapunov exponent.

What Sthitadhi did-
3d lattice of hard spheres with harmonic potentials.
P(x,t) = G*P(x-dx,t-dt)- L*P(x+dx, t-dt) - the continuum limit gives the diffusion equation, and is a vector eqn in 3d
perturbation given to one sphere (whole sequence)
two baths at const temperature- Maxwelian distribution.. modelled probabilities of collisions b/w 2 spheres, which would impart kinetic energy. (leads to heat conduction) - gave the Fourier heat law.
Infinite lattice- if the initial conditions were given in clusters of three(or above), they spread out in threes(or above)(above initial = above final). Collisions spread out linearly ,(one of 3 ballistic modes of propagation)
In solitons,lossless propagation occurs if v = sec(pi/(2*(n+1))).
another type of lossless propagation- after 4-5 collisions, the particles that were given initial velocities come to rest and the next set of particles get the same initial velocities -- these are compactons. (n particles vibrate, then they stop and the next n are in the same initial conditions)
Measure of some set is non zero. (showed analytically)
Chaos came in somewhere.
