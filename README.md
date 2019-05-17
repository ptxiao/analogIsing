# analogIsing
LTspice netlists and problem specifications for the analog Ising machine. This folder contains supporting files for T. Patrick Xiao's PhD Thesis (Department of EECS, UC Berkeley, 2019).

Description of the files:
- Ising_8spins.net: LTspice netlist for an analog Ising machine circuit. Implements the coupling matrix in J8.txt, also provided in Appendix G of thesis.
- Ising_32spins.net: LTspice netlist that implements the coupling matrix in J32.txt.
- J8.txt: a list of coupling weights (binary, -1 and +1) for a fully-connected 8-spin Ising problem. The first two columns list the spin indices. The third column contains the weight value.
- J32.txt: a list of coupling weights (binary, -1 and +1) for a fully-connected 32-spin Ising problem
- MaxCut_g05-60-2.net: LTspice netlist that implements a Max-Cut problem with 60 vertices. The list of weights can be found here: http://biqmac.uni-klu.ac.at/library/mac/rudy/g05_60.2

LTspice netlists were tested on both LTspice IV on Mac OS X and LTspice XVII on Windows 10.
