# Code: Truncated SVD Image Compression (C)

This folder contains the full C implementation for computing truncated SVD and compressing grayscale images in PGM (P5) format.

---

## Files

- `main.c` — Main program with:
  - PGM image reader/writer
  - Power iteration SVD algorithm
  - Matrix operations (multiplication, transpose, normalization)
  - Reconstruction of Ak = Uk × Σk × Vkᵀ
  - Frobenius norm error calculation
- 'README.md' - This file

---

## Compilation

'''bash
gcc main.c -o main.c -lm
'''

## Usage

'''bash
./main image.pgm 5 20 50 100
'''
