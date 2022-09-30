# ligand_docking_vina_analysis
Set of scripts used to automate ligand-protein docking analysis to create input files and read output files from autodock vina.  There is also a script for cleaning amino acid text sequences for use in alphafold.

amino_acids_checker.ipynb can be used to clean amino acid sequences before input into alphafold.  This ia a simple project that prevents invalid charactrs like [space] or [/n] from ruining your pdb file.

docking_analysis_combined.ipynb can be used to manage inputs and outputs for docking analysis via autodock vina.  The final output will be a dataframe with ligand names and associated docking scores ordered from the most stable to the least stable.

The template file folder contains these scripts and the perl script and the autodock vina executable.  I suggest downloading the most current autodock vina file from https://github.com/ccsb-scripps/AutoDock-Vina/releases

15 min video tutorial (code has been updated/optimized since the video) https://youtu.be/DFJagfPHewk
