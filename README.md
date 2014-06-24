MultipleRegions
===============

simuMultipleRegions
===================
Here are the simulations for the different regions:
- neutral with 500 regions (neutral500)
- strong selection (Nm=100) in populations with high altitude (W,X) with 250 regions (250Strong)
- moderate selection (Nm=10) in populations with high altitude (W,X) with 250 regions (250Moderate)
- strong selection (Nm=100) in one of the populations with high altitude (X)  with 125 regions (125StrongX)
- strong selection (Nm=100) in one of the populations with high altitude (W)  with 125 regions (125StrongW)
- moderate selection (Nm=10) in one of the populations with high altitude (X)  with 125 regions (125ModerateX)
- moderate selection (Nm=10) in one of the populations with high altitude (W)  with 125 regions (125ModerateW)


In each of the folders, we have:
-  bayesFormat.txt file which contains the allele counts for allele 0 and allele 1 for all the regions and for all the populations. 
The format of the file is as follows: 
Format: Population \t list of allele counts of allele 1 for all loci \t list of allele counts of allele 0 for all loci
Each region has 101 loci. E.g. for the case of 125 regions, for the allele counts of allele 1, we have a list of 125 lists with 101 allele counts each, which correspond to the allele counts of allele 1 of each loci.

- folder with p-values from xp-ehh which were calculated empirically. 
There is one file for each region for the 2 pairwise comparison (Y-X and Z-W) that were conducted (e.g. pvalue_pairwiseComparison_region: pvaluezw0)

Each of the file has the SNP name in the first column, and XP-EHH score in the second and the p-value in the third.

