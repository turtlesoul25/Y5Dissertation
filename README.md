# Year 5 Dissertation - Niharika Reddy Peddinenikalva

This GitHub repository contains all the files that were used to implement the two solution algorithms constructed and described in this dissertation for solving the Nurse Rostering Problem.
The key for all files is presented below.

**Heuristic_initial_sols**: All rosters constructed by the Greedy Heuristic.

**Heuristic_soln_post_VNS**: GHVNS rosters obtained after VNS has been applied to the initial feasible solution from 'Heuristic_initial_sols'.

**Instance_dats**: All .dat files for the 24 instances of the Employee Shift Scheduling Benchmark Dataset after preprocessing the relevant '.txt' files in Python.

**Instance_txts**: All original .txt files for the 24 instances of the Employee Shift Scheduling Benchmark Dataset taken from http://www.schedulingbenchmarks.org/nrp/

**RosterSolution_post_VNS**: HIPVNS rosters obtained after VNS has been applied to the initial feasible solution from 'RosterSolutions'.

**RosterSolutions**: All rosters obtained from Xpress for the original model.

**RosterSolutions_RM**: All rosters obtained from Xpress for the relaxed model.

**CheckingSolutions.mos**: Xpress file which loads all .csv rosters to check whether all constraints are satisfied and to calculate all penalties in the objective function for verification.

**Code.ipynb**: Python code for pre-processing .txt files and implementing the Greedy Heuristic as well as Variable Neighbourhood Search.

**NRP.mos**: Mosel file for implementation of the original model in Xpress to obtain an initial feasible solution for HIPVNS.

**NRP_RM.mos**: Mosel file for implementation of the relaxed model in Xpress to obtain an initial feasible solution for HIPVNS.
