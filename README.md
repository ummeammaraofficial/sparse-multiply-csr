# sparse-multiply-csr

Sparse matrix multiplication using CSR (Compressed Sparse Row) format implemented in C

## Overview
This project implements sparse matrix multiplication using the Compressed Sparse Row (CSR) format in C.  

CSR is used to efficiently store and compute operations on matrices with a large number of zero elements.

## Features
- CSR-based sparse matrix representation
- Efficient matrix multiplication
- Memory optimization for sparse data
- Written in pure C (no external libraries)

## Compilation
gcc sparse_multiply.c -o -lm sparse_multiply

## Run
./sparse_multiply

## File Structure
- sparse_multiply.c → main implementation
- README.md → project documentation
