<h4 align="center">BLAST Query Optimization using<br> Recursive Similarity Search for<br> SARS-CoV-2 Phylogenetic Tree Construction</h4>

--------
This repository contains program that was used as a tool for FASTA sequence extraction and phylogenetic tree construction using BioPython library and was intended as a part of my research and final examination at Information System Management at Gunadarma University.

The project structure consist of four folder/file:
```
├─ 01-inputs
├─ 02-blast-search
├─ 03-fasta-processing
├─ 04-outputs
├─ example_working_directory
├─ main_input.ipynb
└─ main_phylo.ipynb
```
1. [01-inputs](./01-inputs/), contains singular FASTA that was used as an input for BLAST search in the research
2. [02-blast-search](./02-blast-search/), the folder containing search results from each trials
3. [03-fasta-processing](./03-fasta-processing/), this directory store fasta files that has been processed using either this python script itself or from external program (MUSCLE)
3. [04-outputs](./04-outputs/), phylogenetic tree images that was generated from this script
3. [example_working_directory](./example_working_directory/), working directory used in example notebook
3. [main_input.ipynb](./main_input.ipynb), python notebook mainly for fasta reading/parsing, extracting, merging, etc
4. [main_phylo.ipynb](./main_phylo.ipynb), python code to construct phylogenetic tree

You can also read more detailed usage documentation [here](./manual_book/Manual_Book-SARSCoV2_BLAST_Recursive_Phylogenetic-ID.pdf)