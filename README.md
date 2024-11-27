# CommonAssignmentOpenMP
Provide a parallell version of the Tarjan's algorithm to find Strongly Connected Components in a Graph. The implementation MUST use an hibrid  message passing / shared memory paradigm. and has to be implemented by using MPI and openMP.  Students MUST provide parallel processes on different nodes, and each process has to be parallelized by using Open MP (i.e.: MPI will spawn OPENMP-compiled processes). Students can choose the graph allocation method the prefer. They can eventually produce the graph directly in distributed memory (without store anything). Good Graph dimensions are greater than 4GB of data

## Dependencies

* MPICH
* Python3
* OMP

## How to run
Premise: The code for generating directories, tables and plots requires the python interpreter and a library to be installed, matplotlib, with the following command:
pip3 install matplotlib

1.	Navigate to the folder containing the makefile
2.	To clear previously obtained achievements and previous builds, enter the command
make clean
3.	To generate the necessary directories and compile and linking the various source codes, enter the command
make all
4.	To run the algorithm for making tests, producing results, measurements, graphs and tables, enter the command
make test
5.	To clear previously obtained achievements and previous builds, enter the command
make clean

The results of the algorithms can be viewed in the "ResultSCC" folder, divided by optimization and type of graph and size.
The execution times of the algorithms and their average values can be viewed respectively in the "Informations" and "Results" folders, divided by optimization and type of graph and size.
The results in graphical and tabular format can be viewed respectively in the "Plots" and "Tables" folders, divided by optimization and type of graph and size.

