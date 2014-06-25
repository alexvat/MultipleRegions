MultipleRegions
===============
iHS
===================

In each of the folders, there are 2 kind of files:
1. The files called pvalue_pop_region (e.g. pvaluew0) that have the 3 columns (SNP name \t  iHS score \t pvalue (calculated empirically))
2. The files called missingSNPs_pop (e.g. missingSNPsw) that have 2 columns (Number of Region \t Number of missing score from the iHS output**)

** In the iHS output we don't have always a score for each SNP. This is happening because iHS is skipped is for a SNP if the EHH doesn't reach the value of 0.05 according to Voight et. al 2006.