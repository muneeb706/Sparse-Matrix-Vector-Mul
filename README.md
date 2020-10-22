# Sparse-Matrix-Vector-Mul
Parallelized Sparse Matrix Vector multiplication using OpenMP

## Dataset
Experiment is done on the higgs-twitter.mtx data file, this file can be downloaded from [higgs-twitter-dataset](https://suitesparse-collection-website.herokuapp.com/MM/SNAP/higgs-twitter.tar.gz). After downloading the compressed folder search for higgs-twitter.mtx data file and put the file in the same folder where code files are placed.

## Compilation and Execution
Code can be compiled and executed using g++ compiler. Please enter following commands in the terminal after navigating to folder where code files are placed to compile.

### For Serial Program

#### Compile
g++ -o spmv-openmp spmv-openmp.cpp -std=c++11 -fopenmp
#### Execute
./spmv-openmp
