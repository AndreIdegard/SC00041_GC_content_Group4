# SC00041 GC Content

## Purpose

This script imports DNA sequencing data. 
It then calculates what proportion of nucleotide bases are either guanine och cytosine in each window of the DNA sequence.
It then plots these proportions (y axis) by window (x-axis) conected by lines.
Finally it saves this plot as "output.png"

## Instructions for Running Code
To run the code install dependencies listed in environment.yaml

The code can then be run using the example below.
### Install dependencies
Dependencies of the script are listed in environment.yaml

### Run the script
Below is an example of how to run the code using the terninal. If the fasta.fa file is in a different directory the file path must be updated. Likewise if you wish to have the plot saved in a different directory (other than /out) please update the file path accordingly.

`python3 gc_content.py data/fasta.fa out/output.png`

## What output to expect
The code outputs and saves a plot showing what proportion of nucleotide bases are either guanosine or cytosine in each window of the DNA sequence.
