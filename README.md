#This is a proposal for BIOL_7180 Scripting for Biologists

This project was formed by Yu Sun and Boyuan Wang.


Structural variations (SVs) contribute to the variability of our genome and are often associated with disease. 
In general, people used a program called "Breakdancer" that provides genome-wide detection of structural variants from next generation paired-end sequencing reads.
Specifically, breakdancer identifies five types of structural variants(SVs): insertions(INS), deletions(DEL), inversions(INV), inter- and intra-chromosomal translocations(ITX/CTX).
Here, we sift through the raw output for each chromosome to summarize the results by a Perl script.
The aim is calculate the characteristic value of the variant type detected in each chromosome.
