Hybrid-perovskites
==================

DFT optimised crystal structures of hybrid halide perovskites, including CH3NH3PbI3 (MAPI).

Fork
------------

This fork has been generated from the original data available at: https://github.com/WMD-Bath/Hybrid-perovskites
In the original files the coordinates of the "A" site cation were split between the periodic boundaries. In order to have a simpler visualization of the data, in this fork, all the coordinates have been shifted. The shift has been made in order to have a particular point of the 'A' cation in the center of the cell. The chosen points are the following:
- MA 		= middle point of C-N bond
- CH(NH2)2 	= C atom
- NH4 		= N atom
- H		= H atom

Source
------------

For the ‘pseudo-cubic’ phases the starting point is a standard cubic perovskite structure (all internal positions fixed by the space group). The 'A' site is replaced by a molecule, which lowers the symmetry and allows distortions of the BX6 octahedra. 

The final structures have been obtained following an iterative procedure with small ion displacements (ISIF2 in VASP) using a Quasi-Newton algorithm and the PBEsol exchange-correlation functional within Density Functional Theory (DFT). 

N.B. For property calculations, always re-optimise a crystal structure using your own calculation setup (and exchange-correlation functional). 

Used in
------------
- "Structural and electronic properties of hybrid perovskites for high-efficiency thin-film photovoltaics from first-principles" APL Materials (2013) DOI: 10.1063/1.4824147

- "Relativistic quasiparticle self-consistent electronic structure of hybrid halide
perovskite photovoltaic absorbers” Physical Review B (2014) DOI: 10.1103/PhysRevB.89.155204

- "Atomistic origins of high-performance in hybrid halide perovskite solar cells" Nano Letters (2014) DOI: 10.1021/nl500390f

Requirements
------------
To open the .cif file, a viewer such as http://jp-minerals.org/vesta/en/.
To run the POSCAR file: a VASP license, and the other required input files (INCAR; KPOINTS and POTCAR)

Disclaimer
----------
This file is not affiliated with *VASP*. Feel free to use and modify, but do so at your own risk.
