# Group's Grimoire
Our group's tools and gadgets for molecular modeling, protein engineering, virtual screening and machine learning

## ProtEngGA
Runs a genetic algorithm for protein design given a reference structure. The population of initial sequences can also be provided, otherwise will use random. The objective function can be chosen, but the default one optimizes ΔGfold.
https://github.com/izzetbiophysicist/prot_eng_GA

## Consensus design
Carries out consensus design given a multifasta and a reference structure. Can also perform hybrid consensus, where the best residues at non-consensus regions are searched using Rosetta design
https://github.com/izzetbiophysicist/consensus_design

## MolDataPrep
Automatic data processing for Machine Learning pipelines for virtual screening (peptides and small molecules). Given a set o FASTA sequences or Smiles and a response variable, can automatically process data for training
https://github.com/izzetbiophysicist/mol_data_prep


## Data Convex Hull
Generates a convex hull around the given data point. Useful for domain applicability analysis
https://github.com/izzetbiophysicist/Data_convex_hull


## DomainFetcher
Fetches segments of PDB structures matching a given PFAM domain
https://github.com/izzetbiophysicist/DomainFetcher

## HeliBO (Helical Binder Optimizer)
Stochastic cyclic optimization of binding free energy of peptide ligands through iterative mutagenesis. Has special parameters for helical peptides, can also be used for other protein binders
https://github.com/jsartori12/HeliBO

## Murcko scaffold frequencies
Calculates the Murcko scaffolds for a given list of compounds and returns the scaffolds along with their frequencies
https://github.com/izzetbiophysicist/Murcko_scaffold_frequencies


## Descriptor converter
Convert an AA sequence into physcicochemial descriptor (zscales or VHSE)
https://github.com/riveros94/descriptor_converter

## Design functions
An assortment of handy protein design functions
https://github.com/izzetbiophysicist/protein_design_functions

## Useful gromacs inputs
Some useful Gromacs stuff for Molecuar dynamics
https://github.com/izzetbiophysicist/useful_gromacs_inputs
