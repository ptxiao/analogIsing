# analogIsing
LTspice netlists and problem specifications for the analog Ising machine. This folder contains supporting files for T. Patrick Xiao's PhD Thesis (U.C. Berkeley, Deptartment of EECS, 2019).

Description of the files:
- Ising_8spins.net: LTspice netlist for an analog Ising machine circuit. Implements the coupling matrix in J8.txt, also provided in Appendix G of thesis.
- Ising_32spins.net: LTspice netlist that implements the coupling matrix in J32.txt.
- J8.txt: a list of coupling weights (binary, -1 and +1) for a fully-connected 8-spin Ising problem
- J32.txt: a list of coupling weights (binary, -1 and +1) for a fully-connected 32-spin Ising problem

LTspice netlists were tested on both LTspice IV on Mac OS X and LTspice XVII on Windows 10.
