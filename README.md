# LAMMPS input for CG curing simulations
[![DOI](https://zenodo.org/badge/625440522.svg)](https://zenodo.org/badge/latestdoi/625440522)

### PREREQUISITE:
LAMMPS software with USER-REACTION compliled

### INPUT:
bonding-3800v4000i1p1000.lammps: data file containing prepolymer topology as described in paper

in.lammps: LAMMPS input script

potentials: non-bonded pair potentials calibrated by iterative Boltzmann inversion (IBI)

map.txt, mol_mixture.txt, mol_pu1000.txt: BOND/REACT command input, topolical mapping files

### RUN:
unzip potentials.tar.gz

./lmp_exe -i in.lammps
