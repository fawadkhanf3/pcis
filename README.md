# pcis - Toolbox for computing Polyhedral Controlled-Invariant Sets

This is an ongoing effort to combine code for polyhedral synthesis methods (subsume the repositories `cps-inv`, `multi-cinv` and parts of `mkz`). List of capabilities:

 - Pre algorithms via robust counterpart and intersection/projection
 - Invariance algorithm with termination guarantee
 - Measurable and non-measurable disturbance
 - Parametrized/disturbed A matrix
 - State-dependent disturbance

## Requirements
 - Recent version of Matlab and MPT 3.0 (http://control.ee.ethz.ch/~mpt).

## Installation
Add the `lib` folder to the Matlab path. Execute `runtests` in the `tests` folder to make sure everything works correctly. Optional: set up MPT to use a commercial solver.

## TODO list

 - Add 3D ACC example
 - Work out theory for w,v disturbance that is both p-dependent and x-dependent. Is there a conflict? 

## Longer term objectives

 - Implementation of `minHRep` that scales with size of output as opposed to input
 - `Pre` with pre-defined template with complexity bound
 - Algorithms for merging non-convex polyhedral unions