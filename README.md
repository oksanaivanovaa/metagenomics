# Metagenomics
3 semester at ITMO, Metagenomics course

Short pipelines.
Assignment one.

Data are the 16S rRNA sequenced amplicons of V3-V4 hypervariable regions.
Raw reads were cut from primers using primercut.py.

Usage:

primercut.py -f forvard_seq -r reverse_seq -m 1 raw/S100* noprimer/S100_fwd.fastq noprimer/S100_rev.fastq 
primercut.py -f forvard_seq -r reverse_seq -m 1 raw/S101* noprimer/S101_fwd.fastq noprimer/S101_rev.fastq


Next OTU production was made using script_one.sh with qiime2 package.

