# Doctoral Dissertation

Based on the UF dissertation template provided by [UF IT](https://it.ufl.edu/helpdesk/graduate-resources/ms-word--latex-templates/)

This is not included in the `exampleMasterFile.tex` file, just a remnant from trying to store this locally and on GitHub -- but the compiler on my laptop creates a bunch of files that I got tired of managing and couldn't figure out how to store them all in one `build` directory. 

## Chapters (WIP)

1. Introduction and background information

    a. ML in chemistry:

        - Atomic representation

        - Model architecture

        - Data quality and availability

    b. ANAKIN-ME

        - AEVs

        - ANI model architecture

2. Exploration of atomistic predictions

    a. ANI predictions

        - Total energy as a sum of atomic energies

        - Uncertainty in ANI neural network predictions

        - Exploring the flaws in predicting total energy as a sum of atomic energies

    b. Drawback of atomic energy predictions

    c. Need for a practical, physical quantity to estimate uncertainty

3. Trends in atomic force predictions by ANI neural network potentials

    a. Potential solution

        - Forces

        - Force magnitudes

    b. Analyzing the uncertainty of force predictions

        - Atom isolator

        - Capping atoms

        - Drawback: configurational sampling

4. Simulating and distributing chemical simulations with LAMMPS-ANI

    a. CUDA-accelerated AEV computation

    b. GPU parallelization

    c. ANI-1xnr

    d. The Miller Experiment

6. Analysis of organic reactions under primordial earth conditions; Hero Run

    a. MolFind

        - GraphMatcher

        - Parallelization

    b. 

## File descriptions

* `ufdissertation.cls` -- don't change! This is the class file that describes the formatting. Says to only change if you know what you're doing (I don't).