# lsqt-matlab
A 200-line MATLAB code for a linear-scaling quantum transport method

This code can be used to obtain intrinsic electronic transport properties of large systems described by a real-space tight-binding Hamiltonian together with one or more types of disorder.

The major references for the CUDA implementation are 
* [1] Z. Fan, A. Uppstu, T. Siro, and A. Harju, Efficient linear-scaling quantum transport calculations on graphics processing units and applications on electron transport in graphene, Comput. Phys. Commun. 185, 28 (2014).
* [2] Z. Fan, V. Vierimaa, and Ari Harju, GPUQT: An efficient linear-scaling quantum transport code fully implemented on graphics processing units, arXiv:1705.01387 [physics.comp-ph], to be published in Comput. Phys. Commun.

## File organizations

* This package consists of the following MATLAB functions:
    * lsqt.m                         
    * find_dos.m                      
    * find_vac.m                
    * find_msd.m                
    * find_H.m
    * create_state.m
    * evolve.m      
    * evolvex.m 
    * chebyshev_summation.m 
    * find_moments.m 

* lsqt.m is the driver function which the user will call.

## Purposes of this code

* Help the readers who are interested in this lienar-scaling quantum transport method to thorougly understand it. 

* The students in my course are asked to use the code to reproduce the results in sections 5.1 of Ref. [1] above. 
This is an optional course project.

## Contact

* Zheyong Fan: brucenju(at)gmail.com; zheyong.fan(at)aalto.fi; zheyongfan(at)163.com

