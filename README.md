# Dynamical Mass of a Galaxy Cluster using SDSS Data

This project was completed as part of the **Galaxies (2023)** course at the Indian Institute of Space Science and Technology (IIST) under Dr. Anand Narayanan.

The aim of this assignment is to estimate the **dynamical mass of a galaxy cluster** using spectroscopic redshift data from the Sloan Digital Sky Survey (SDSS).

---

## Project Overview

Galaxy clusters are massive systems bound by gravity. Their total mass can be estimated from the motion of their member galaxies.

In this project, the following steps were carried out:

* Selection of cluster member galaxies using redshift cuts
* Conversion of redshift values to line-of-sight velocities
* Calculation of velocity dispersion
* Estimation of cluster radius
* Computation of dynamical mass using the virial theorem

---

## Method

Cluster galaxies are selected within a redshift range centered around the cluster redshift to remove foreground and background objects.

Redshift values are converted to velocities using:

v = c (z − z_cluster) / (1 + z_cluster)

The velocity dispersion (σ) is calculated from these velocities.

The dynamical mass is then estimated using the virial relation:

M ≈ (3 σ² R) / G

where
σ = velocity dispersion
R = cluster radius
G = gravitational constant

---

## Tools Used

* Python
* NumPy
* Matplotlib
* Jupyter Notebook
* SDSS spectroscopic data

