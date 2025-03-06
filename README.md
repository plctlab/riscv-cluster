# riscv-cluster

Towards a million-node RISC-V cluster.

What software or demo do you want to run if you have a RISC-V cluster with more than 1024 RV64GCV cores?

```
Hello everyone,

We PLCT lab has purchased more than 1000 sets of RISC-V equipment (mainly Nezha/D1 development boards), and hope to be able to assemble a RISC-V cluster of ~1024 nodes with cheap network equipment. We hope that this cluster can be used to actually test whether relevant software in the field of high performance computing is ready to be deployed on RISC-V. Please note that this cluster is not intended to achieve performance demonstration. Nor are we using the latest or most powerful RISC-V computing equipment. This test is for feature availability or functional readiness.

We are completely new to the HPC field. You are welcome to send us an email or a PR to tell us which open source software or commercial tool sets should be tested or validated.

After the construction is completed, it will be open to all RVI members through RISC-V Lab before December 1st, 2022.


Current test plan:
- OpenBLAS
- OpenCV
- NCNN
- OpenMPI
- OpenPPL
- CoreNEURON: 
  https://github.com/BlueBrain/CoreNeuron
  optimized for many-core, etc. need a good compiler - Simulator optimized for large scale neural network simulations.
- QuEST: 
  https://github.com/QuEST-Kit/QuEST
  need MPI&OpenMP support, Quantum Gate Simulation 
  CESM: https://github.com/ESCOMP/CESM , need MPI & OpenMP support, Earth Research 
- John: 
  https://github.com/openwall/john , password cracker
- Libgrape: 
  https://github.com/alibaba/libgrape-lite ,  A C++ library for parallel graph processing, MPI
- HiOp
  https://github.com/LLNL/hiop, HiOp - HPC solver for optimization
- Benchmark: HPCG 
  https://github.com/hpcg-benchmark/hpcg
- HPL
  https://netlib.org/benchmark/hpl/ 
- GROMACS
  https://www.gromacs.org/ A free and open-source software suite for high-performance molecular dynamics and output analysis.
 
Please Submit a PR and append the software you want to run on our RISC-V clusters directly.

```
