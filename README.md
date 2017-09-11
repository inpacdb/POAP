# POAP

# POAP-Parallelized Open Babel & Autodock suite Pipeline
<img align="center" src="http://www.sankaranethralaya.org/images/research/bioinformatics/poap-logo.jpg">

**POAP: A GNU Parallel based multithreaded pipeline of Open Babeland Autodock suite for boosted HighThroughput Virtual Screening**


POAP tool is a bash shell script based pipeline which can be used to optimize ligands for docking using openbabel and also to perform virtual screening using Autodock Suite. It allows users to interactively choose options for performing ligand optimization for large sets of ligands. POAP uses GNU parallel to perform the fast and efficient way for the completion of jobs by optimally utilising multiple CPU threads, thereby reducing the time effectively. It also quarantines the ligands causing error during preparation, enabling seamless 
operability. POAP implements dynamic filehandling methods for efficient memory usage and data organization.

* **Software Required to run POAP:**
    + GNU Parallel (https://www.gnu.org/software/parallel/)
    + Openbabel (version 2.4.0 or later) (http://openbabel.org/)
    + Autodock Vina (http://vina.scripps.edu/)
    + MGL Tools 1.5.6 or 1.5.7(for AutodockZn)(http://mgltools.scripps.edu/)
    + Autodock Tools 4.2.6 (http://autodock.scripps.edu/)
    + AutodockZn(http://autodock.scripps.edu/resources/autodockzn-forcefield)

* **POAP Installation:**
    + Just unzip and run the bash scripts provided directly to run the program. 

    There is no installation required. 
    Ensure the software required to run POAP are in place.

* **File formats which can be used as input for ligand preparation:**
    + MDL MOL format (mol, mdl, sdf, sd)
    + Sybyl Mol2 format (ml2, sy2, mol2)
    + SMILES format (smi)
    + Protein Data Bank format (pdb)

* **Virtual Screening process:**
    + Virtual screening using Autodock VINA
    + Multiple protein Virtual screening using Autodock VINA
    + Virtual screening using Autodock
    + Multiple protein Virtual screening using Autodock
    + Virtual screening using AutodockZn
    + Multiple protein Virtual screening using AutodockZn 	

This tool is distributed under the GNU General Public License (GPL). This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License. This program is distributed in the hope that it will be useful,but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

**Usage**

Scripts will be available in the directory scripts

cd scripts/

To start ligand preparation you can strat the script by

bash POAP_ligprep.bash -s

To start Virtual Screening pipeline you can start the script by

bash POAP_vs.bash -s

For more information you can type -h or look into the Manual for detailed information on usage and other optional flags available.

**Version**

v1.0

**Authors**

Samdani.A & Umashankar.V

**For queries please contact:**
vumashankar@gmail.com




