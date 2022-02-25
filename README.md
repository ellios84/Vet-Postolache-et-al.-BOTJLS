## Population structure and signals of local adaptation in *Eugenia uniflora* L. (Myrtaceae), a widely distributed species in the Atlantic Forest
*Nicole Moreira Vetö, Dragos Postolache, Frank L. Guzman Escudero, Elia Vajana, Ricardo Burgo Braga, Fabiano Salgueiro, Rogério Margisi, Giovanni G. Vendramin, Andreia C. Turchetto-Zolet*


The zipped folders contains all input data and scripts used to run LEA and LFMM analyses (see 'LEA analysis.zip' and 'LFMM analysis.zip', respectively) in Vetö, Postolache et al. (2022).

**LEA analysis.zip**
- *LEA.R*: R script used to run LEA.
- *LEA-Eugenia-LD-pruned-2021-Bonf0.01.html*: report on the analysis with results included.
- *2021_Eugenia_qced_ldpruned_372snp_80ind*: input file for the LEA.R script.
- *str.geno*: inut file for sNMF analysis.
- *snps_list*: SNPs inluded into analysis.
- *LEA_Eugenia_Pvalues 2021.txt*: one-column data frame reporting the p-values derived by LEA analysis (one SNP per line).
- *LEA-outliers-bonf-alpha0.01.txt*: data frame reporting outliers from LEA analysis after Bonferroni correction.

**LFMM analysis.zip**
- *LFMM.R*: R script used to run LFMM.
- *LFMM_Eugenia_LD-pruned-Bonf0.01.html*: report on the analysis with results included.
- *361SNPs_Structure_Eugenia.str*: input file for the sNMF analysis (unlinked loci with LEA outliers excluded).
- *361snps_list.csv*: SNPs undergoing sNMF analysis.
- *Coord_Eugenia_80Indiv_LDpruned.csv*: IDs, FIDs and geographical coordinates of the individuals undergoing LFMM analysis.
- *synthetic_6_PCAVariables_ordered.csv*: population-based environmental characterization for LFMM analysis.
- *snps_list.csv*: the 372 unlinked SNPs undergoing LFMM analysis.
- *lfmm-k3-outliers.txt* & *lfmm-k4-outliers*: outliers from LFMM analysis after correcting for three (*k3*) and four (*k4*) latent factors, respectively.
- *lfmm-outliers.txt*: LFMM results as defined by the shared outliers between the *k3* and *k4* runs (see main text).
- *shared-outliers.txt*: shared outliers between LFMM analysis (lfmm-outliers.txt) and LEA analysis (LEA-outliers-bonf-alpha0.01.txt).
