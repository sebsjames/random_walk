# random_walk

Generate a bee-like random walk, following the description given in:

"An Anatomically Constrained Model for Path Integration in the Bee
Brain", Current Biology 27, 3069-3085, October 23, 2017 (Stone et al.)

DOI: http://dx.doi.org/10.1016/j.cub.2017.08.052

This code uses a version of tk_spline to generate cubic splines.

The class sm::random_walk is provided as the C++20 module
sm.random_walk and must be compiled in conjunction with
sebsjames/maths from https://github.com/sebsjames/maths