# Coarse-Grained Molecular Dynamics Model for P3HT

## Description
This repository contains LAMMPS input scripts, data files, and tabulated interaction
potentials for a coarse-grained (CG) molecular dynamics model of
poly(3-hexylthiophene) (P3HT). The CG model is designed for efficient simulation of
the structural and thermomechanical behavior of conjugated polymers.

## Repository Contents
- LAMMPS input files for CG molecular dynamics simulations
- Coarse-grained topology and data files
- Tabulated interaction potentials used with `pair_style table`

## Software Requirements
- LAMMPS (compiled with `pair_style table`)
- Unix/Linux or macOS environment recommended

## Usage
1. Place the tabulated potential files in the working directory.
2. Load the data file using the `read_data` command.
3. Run simulations using the provided LAMMPS input script.

Simulation temperature, run length, as well as other setting parameters can be adjusted within the input file or
passed as variables at runtime.

## Reference
This CG model is associated with the following published work:

Y. Wang, Z. Li, K. Niu, W. Xia, 
*Energy-renormalized coarse-grained molecular dynamics modeling of conjugated polymers*,  
**Polymer**, 256, 125159 (2022).  
https://doi.org/10.1016/j.polymer.2022.125159

## License
This repository is distributed under the MIT License.

## Data and Code Availability
The exact version of this model corresponding to the published article will be
archived on Zenodo to ensure long-term accessibility and reproducibility.
The Zenodo DOI will be added here after archival.