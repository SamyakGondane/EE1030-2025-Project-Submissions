# Image Compression Using Truncated SVD

This repository contains the full C implementation of image compression using **truncated Singular Value Decomposition (SVD)** as part of the Matrix Theory (AI1000) course project.

## Author
**Samyak Gondane**\\
Course: Matrix Theory (AI1000)\\
Submission: November 2025

---

## Project Structure

SoftwareAssignment/\\
├── codes/ # Contains all C source files\\
├── figs/ # Reconstructed images (JPG format)\\
├── tables/\\
│   ├── Comparison of Algorithms.tex\\
│   ├── Error analysis einstein.tex\\
│   ├── Error analysis globe.tex\\
│   └── Error analysis greyscale.tex\\
├── report.pdf\\
└── README.md\\


---


## Project Summary

This project demonstrates how truncated SVD can be used to compress grayscale images by approximating the original image matrix using only the top-k singular values and vectors. The implementation is done entirely in C, including:

- Reading and writing binary PGM images
- Computing top-k SVD using power iteration
- Reconstructing compressed images
- Calculating Frobenius norm error

---

## Deliverables

- Full C source code (`codes/`)
- Reconstructed images for various k values (`figs/`)
- Error analysis in LaTeX format (`tables/table.tex`)
- Final report with algorithm explanation, results, and reflections (`report.pdf`)
- This README
