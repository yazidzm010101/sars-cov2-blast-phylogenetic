<h4 align="center">BLAST Query Optimization using<br> Recursive Similarity Search for<br> SARS-CoV-2 Phylogenetic Tree Construction</h4>

--------
This repository contains program that was used as a tool for FASTA sequence extraction and phylogenetic tree construction using BioPython library and was intended as a part of my research and final examination at Information System Management at Gunadarma University.

The project structure consist of four folder/file:
```
├─ 01 - Inputs
├─ 02 - BLAST Similarity Search
├─ 03 - Preprocessed FASTA Search Results
├─ 04 - Outputs
├─ main_input.ipynb
└─ main_phylo.ipynb
```
1. [Datasets]("./01 - Inputs/"), contains singular FASTA that was used as an input for BLAST search in the research
2. [Outputs]("02 - BLAST Similarity Search"), the folder containing search results from each trials
3. [01_input.ipynb]("./03 - Preprocessed FASTA Search Results"), this directory store fasta files that has been processed using either this python script itself or from external program (MUSCLE)
3. [01_input.ipynb]("./04 - Outputs"), phylogenetic tree images that was generated from this script
3. [01_input.ipynb](./main_input.ipynb), python notebook mainly for fasta reading/parsing, extracting, merging, etc
4. [02_phylogenetic.ipynb](./main_phylo.ipynb), python code to construct phylogenetic tree

You can also read more detailed usage documentation [here](#)