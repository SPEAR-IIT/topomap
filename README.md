# topomap contains two user-level libraries for topology aware task mapping. 
HierTopoMap - Hierarchical Task Mapping Library
HierTopoMap is a library for static mapping, which implements a set of network and multicore aware topology mapping strategies that are developed in our lab. It accepts an MPI distributed graph communicator as input, and computes an optimized mapping in order to improve the communication performance. It can be used to support rank reordering in MPI topology functions. Currently, HierTopoMap supports InfiniBand-connected supercomputers (i.e., fat-tree topology), Cray XT5 machines (i.e., torus topology with non-contiguous node allocation), and Blue Gene/P systems (i.e., mesh/torus topology with contiguous node allocation).

AnalMap - Analytical Topology Mapping Tool for 3D Mesh/Torus
AnalMap is a topology mapping tool for 3D torus-connected supercomputers. It uses the analytical mapping algorithm, which is inspired by the analytical placement technique for VLSI physical design. It is designed for mapping irregular communication graph onto 3D mesh/torus, and can also handle regular communication graph fairly efficiently. AnalMap takes a topology specification and a communication graph as inputs, and then generates an optimized mapping file, which can be used for IBM Blue Gene/P supercomputers.

The tool was developed by Jingjin Wu and Xuanxing Xiong under the supervision of Zhiling Lan at the Illinois Instiute of Technology.
