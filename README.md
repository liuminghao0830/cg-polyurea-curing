# LAMMPS input for running bonding simulation by CG model

# PREREQUISITE:
LAMMPS software with USER-REACTION compliled

# INPUT:
bonding-3800v4000i1p1000.lammps - data file containing prepolymer topology as described in paper
map.txt, mol_mixture.txt, mol_pu1000.txt - BOND/REACT command input

# RUN:
unzip potentials.tar.gz

./lmp_exe -i in.lammps
