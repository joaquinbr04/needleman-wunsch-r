# Needleman–Wunsch Algorithm in R

This repository contains an implementation of the Needleman–Wunsch global sequence alignment algorithm in R.

The project was developed as an exercise for the **Principles of Genome Bioinformatics** course, part of the **Master's Degree in Bioinformatics for Health Sciences at Universitat Pompeu Fabra (UPF)**.

## Description

The script performs a global alignment between two amino acid sequences using:

- The BLOSUM50 substitution matrix
- A linear gap penalty
- Dynamic programming
- A traceback matrix to reconstruct an optimal alignment

The example included in the script aligns the following sequences:

```text
BEAVTY
BEAST
