# MinimapPool
A parallel alignment program base on minimap2. Supplementary information and program are included.
# Pre-requisite:
- Python3, numpy, mpi4py  
- mpich, gcc compiler
- sratool (https://github.com/ncbi/sra-tools/wiki/01.-Downloading-SRA-Toolkit)
- Linux system (suggested Ubantu)
# running
```
$ mpirun -n your_nodes_number python MPIPool.py file_alignment
```
- your_nodes_number: the number of calculation nodes you hanve or you plan to use
- file_alignment:the file to be aligned, which is avai available in NCBI
- device: cpu
- ref: files to be aligned are here
- minimap2: the original program

# Notes
- Before running the program, please configure the environment.
- The files are large and need to be downloaded by yourself, you can use the sratool.
- The larger the file, the longer the wait time, please be patient.
