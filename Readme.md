"testHODLR3D.cpp" performs HODLR3D matrix vector product

It takes these inputs at run time:

cubeRootN: It determines the system size, that is N=pow(cubeRootN,3)

nParticlesInLeafAlong1D: it determines the maximum number of particles in a leaf node, which is pow(nParticlesInLeafAlong1D,3).

L: half side length of the cube which is the computational domain

TOL_POW: tolerance set for ACA routine

Qchoice: Use this to select the kernel you want to use. For various choices look at the kernel.hpp file.

A sample input and output looks like this:

./testHODLR3D 20 6 1 8 0

nLevels: 2

Time taken to construct HODLR3D representation is: 1.78144

Time taken to do Mat-Vec product is: 0.00995999

Memory in GB: 0.00653502

CR: 0.816877

max rank: 108

relative forward error: 1.1891e-09
