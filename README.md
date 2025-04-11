# Doctoral Dissertation

Based on the UF dissertation template provided by [UF IT](https://it.ufl.edu/helpdesk/graduate-resources/ms-word--latex-templates/)

## Chapters

1. Introduction and background information

    a. ML in chemistry:

        i. Atomic representation

        ii. Model architecture

        iii. Data quality and availability

    b. ANAKIN-ME

        i. AEVs

        ii. ANI model architecture

        iii. ANI datasets

2. Exploration of atomistic predictions

    a. ANI predictions

        i. Molecular energy as a sum of atomic contributions
   
        ii. Uncertainty in ANI neural network potentials
   
        iii. Flaws in Measuring Uncertainty via Predicted Total Energy
   

    b. Uncertainty of atomic predictions

    c. Need for a practical, physical quantity to estimate uncertainty

3. Trends in atomic force predictions by ANI neural network potentials

    a. Potential solution for an atomistic QBC measure

        i. Force directional predictions

        ii. Force magnitude predictions

    b. Analyzing the uncertainty of force predictions

        i. LUKE: Use the Forces
   
        ii. Drawback: configurational sampling

4. Early Earth chemistry with LAMMPS-ANI

    a. Interface of TorchANI and LAMMPS

    b. ANI-1xnr

    c. The Miller-Urey experiment

        i. CUDA-accelerated molecule finder

        ii. The small early earth system

        iii. The medium early earth system

        iv. The early earth hero run

5. Analysis of organic reactions under primordial earth conditions; Hero Run

    a. Overhauling the MolFind Analysis Tool

        i. Loading simulation data to memory

        ii. Categorical graph matching

        iii. Preprocessing and efficiency

    b. Restarts: quench analysis

    c. Exploring new molecular configurations

    d. Expanding the search

    e. Discussion of results

6. Concluding remarks

    a. Reflection on uncertainty in ANI predictions

    b. Reflection on early earth reactive simulations

8. Future work
