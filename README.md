# MetaCRAST: reference-guided CRISPR detection in metagenomes
# Introduction
`MetaCRAST` is a tool to detect CRISPR arrays in raw, unassembled metagenomes. 

# Installation
Dependencies: `fasta-splitter.pl`, `cd-hit`

Dependencies (CPAN): Text::Levenshtein::XS, String::Approx, Getopt::Std, Bio::SeqIO, Bio::Perl, MCE, and MCE::Loop

# Usage 
`MetaCRAST` takes **FASTA** files as inputs (both for the CRISPR DRs and the metagenome). Optional arguments are in brackets. 

`MetaCRAST -p patterns.fasta -i infile.fasta -o output_dir [-t] tmp_dir -d dist_allowed [-h] use Hamming Distance [-r] reverse_complement [-l] max_spacer_length [-c] cd_hit_similarity_threshold [-a] total_spacer_cd_hit_similarity_threshold [-n] num_procs`

The required arguments are as follows:
* **`-p`**
* **`-i`**
* **`-o`**
* **`-d`**

And the optional arguments are:
* **`-t`**
* **`-h`**
* **`-r`**
* **`-l`**
* **`-c`**
* **`-a`**
* **`-n`**

# Citation
If you use `MetaCRAST` in published work, please include a reference to my Bioinformatics paper.
