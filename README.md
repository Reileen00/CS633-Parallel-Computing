Contains Assignments of the course CS633-Parallel Computing
Parallel Computing - HaloFlow §
CS 633 Course Project, Parallel Computing Jan’26 - Apr’26
• Implemented a distributed 3D MPI stencil computation
with domain decomposition, performing configurable d-point
neighbor averaging and isovalue counting across time steps.
• Optimized inter-process communication using non-blocking 6-
face halo exchanges with Isend/Irecv, overlapping communication with computation to reduce synchronization overhead.
• Deployed and benchmarked the implementation on the PARAM
Rudra cluster using SLURM, evaluating scalability across 32–
96 processes and varying 3D data sizes.
