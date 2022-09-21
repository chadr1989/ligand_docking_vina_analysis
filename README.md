# ligand_docking_vina_analysis
Set of scripts used to automate ligand-protein docking analysis to create input files and read output files from autodock vina.  There is also a script for cleaning amino acid text sequences for use in alphafold.

amino_acids_checker.ipynb can be used to clean amino acid sequences before input into alphafold.  This ia a simple project that prevents invalid charactrs like [space] or [/n] from ruining your pdb file.

docking_analysis_combined.ipynb can be used to manage inputs and outputs for docking analysis via autodock vina.  The final output will be a dataframe with ligand names and associated docking scores ordered from the most stable to the least stable.
