## Population structure and signals of local adaptation in *Eugenia uniflora* L. (Myrtaceae), a widely distributed species in the Atlantic Forest
### Nicole Moreira Vetö, Dragos Postolache, Frank L. Guzman Escudero, Elia Vajana, Ricardo Burgo Braga, Fabiano Salgueiro, Rogério Margisi, Giovanni G. Vendramin, Andreia C. Turchetto-Zolet



The folders **LD analysis.zip**, **LEA analysis.zip** and **LFMM analysis.zip** contain all input data and scripts used to run quality control (QC), linkage disequilibrium (LD), LEA and LFMM analyses in Vetö, Postolache et al. (2022).

**LD analysis.zip**
- *analysis.R/genomics.R*: R scripts used to run QC and LD analysis. 
- *Eugenia.bed/bim/fam/ped/map*: raw molecular file (85 individuals, 523 SNPs).
- *Eugenia_qced.bed/bim/fam*: QC-ed molecular file (80 individuals, 395 SNPs).
- *c1.txt/c2.txt/c3.txt*: individuals belonging to genetic cluster one (c1; 27 individuals), two (c2; 27 individuals) and three (c3; 26 individuals) as defined by discriminant analysis of principal components (DAPC).
- *Eugenia_qced_c1/c2/c3.bed/bim/fam*: molecular files corresponding to genetic cluster one, two and three; input for the within-group LD analyses.
- *ldrm_c1/c2/c3_alpha0.01.txt*: SNPs showing statistical evidence of LD in genetic cluster one, two and three (59, 202 and 181 SNPs, respectively; *p*-value<0.01 after Bonferroni correction).
- *ldrm_shared_0.01.txt*: SNPs showing statistical evidence of LD in all genetic clusters (18 SNPs shared).
- *leq_c1/c2/c3_alpha0.01.txt*: *p*-values for the non-significant pairwise correlation tests among SNPs in genetic cluster one, two and three (*p*-value>0.01 after Bonferroni correction); these files contain the identifiers of the SNPs showing linkage equilibrium in the genetic clusters.  
- *Eugenia_qced_ldpruned.bed/bim/fam/ped/map*: QC-ed molecular file with SNPs in LD excluded (80 individuals, 372 SNPs). 

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
