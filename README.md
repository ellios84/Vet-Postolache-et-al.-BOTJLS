# Vet-et-al.-BOTJLS

The zipped folders contains all input data and scripts to reproduce LEA and LFMM analyses (see 'LEA analysis.zip' and 'LFMM analysis.zip', respectively) as performed in Vetö, Postolache et al. - BOTJLS.

LEA analysis.zip
- LEA.R: R script for LEA analysis.
- LEA-Eugenia-LD-pruned-2021-Bonf0.01.html: report on LEA analysis with results included.
- 2021_Eugenia_qced_ldpruned_372snp_80ind: input file for LEA.R script.
- str.geno: inut file for sNMF analysis.
- snps_list: SNP IDs inluded into analysis.
- LEA_Eugenia_Pvalues 2021.txt: one-column data frame reporting p-values as derived by LEA analysis (one SNP per line).
- LEA-outliers-bonf-alpha0.01.txt: data frame reporting outliers from LEA analysis after Bonferroni correction for multiple testing.

**LFMM analysis.zip
- *LFMM.R*: R script for LFMM analysis. 
- *LFMM_Eugenia_LD-pruned-Bonf0.01.html*: report on LFMM analysis with results included.
- *361SNPs_Structure_Eugenia.str*: input file for sNMF analysis as based on unlinked loci.
- *361snps_list.csv*: IDs of unlinked SNPs.
- *Coord_Eugenia_80Indiv_LDpruned.csv*: IDs, FIDs and geographical coordinates of the individuals undergoing LFMM analysis.
- *synthetic_6_PCAVariables_ordered.csv*: population-based environmental characterization for LFMM analysis.
- *snps_list.csv*: IDs of the 372 SNPs undergoing LFMM analysis.
- *lfmm-k3-outliers.txt* & *lfmm-k4-outliers*: outliers from LFMM analysis with correction for 3 and 4 latent factors, respectively.
- *lfmm-outliers.txt*: LFMM results as defined by the shared outliers between the K=3 and K=4 runs.
- *shared-outliers.txt*: shared outliers between LFMM analysis (lfmm-outliers.txt) and LEA analysis (LEA-outliers-bonf-alpha0.01.txt)
