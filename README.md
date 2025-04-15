
# To get tsds of full-length elements
get location of full length element and TSD locations using `getfulllengthlocation.R` script
and get fasta from the location table 
and do muscle to do alignment
```
module load muscle

muscle -align fam1679full.fasta -output fam1679full.fasaln.fasta -html fam1679full.aln.html
muscle -align fam1679fullTSD.fasta -output fam1679fullTSD.fasaln.fasta 
```
And draw sequence logo from weblogo using these alignments. 
