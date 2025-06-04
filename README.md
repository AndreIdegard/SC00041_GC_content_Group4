# SC00041 GC Content

## Purpose

This script imports DNA sequencing data. 
It then calculates what proportion of neucleotide bases are either guanine och cytosine in each window of the DNA sequence.
It then plots these proportions (y axis) by window (x-axis) conected by lines.
Finally it saves this plot in /out/output.png

## Instructions for Running Code
To run the code install dependencies listed in environment.yaml
Then paste the paths bellow in the terminal to run it.

### Install dependencies
Dependencies of the script are listed in environment.yaml

### Run the script
python3 gc_content.py data/fasta.fa out/output.png

## What output to expect
The code outputs and saves a plot showing what proportion of nucleotide bases are either guanosine or cytosine in each window of the DNA sequence.
