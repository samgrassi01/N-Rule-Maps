# N-Rule-Maps
This repository provides the code for implementing n-rule maps over the general space of intersecting lines on the plane.  This software is still in the development phase and any help in fixing bugs or making the software more robust is welcome.  I am also writing this in Julia to increase effeciency, and such code should be posted soon.

The behavior of n-rule maps over the space of intersecting lines on the plane is generally quite robust, and this software provides a platform on which to experiment with n-rule maps in a general way; the user can specify any space and n-rule map and use this software to determine the behavior of the n-rule map over the space through studying orbit data and plots.

Examples of periodic orbits generated by n-rule maps in different spaces are provided in the following images.

<img src="Images/per1500,10lines.png" width="500">

<img src="Images/ang67.png" width="500">


## Documentation and Examples.
For general background into n-rule maps, documentation for code use and examples see the `N-Rule Maps.ipynb` notebook.

### Dependencies
Running this n-rule maps program requires Python 3.x, the Python Math and Random packages, Matplotlib, and NumPy.

## Research Papers
The attachment `Perpindicular Projection Map Research Paper` is math paper studying a specific case of n-rule maps defined over the space of three pairwise nonparallel, nonconcurrent lines in R2.  This paper will appear in the *Journal of Dynamical Systems and Geometric Theories*.  A second paper discussing general n-rule maps in complete generality, as well as their application to problems in Dynamical Systems is being written.
