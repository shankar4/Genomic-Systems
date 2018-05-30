Genomic Wide Association Study (GWAS), AKA Whole Genome association Study (WGAS), summarized from the Wiki reference [here](https://en.wikipedia.org/wiki/Genome-wide_association_study): It is an observational study of genetic variants across the whole genome. Statistical case-control methods are used to associate SNPs and (human) disease phenotypes/biomarkers.  

Sequencing the whole genome of each person in the study is expensive; so, only a subset is measured (using a custom genetic array chip): no CNV and only SNPs with enough variation in the reference population. A custom built **microarray** is then used to perform restricted genotyping for each person. Thus, GWAS does not directly genotype all variation in the genome. However, imputation of the genotypes to a reference panel, as from the HapMap project or the 1000 Genomes project, boosts the coverage of genomic variation. 

About 1 million SNPs are tabulated for comparison between the case and control groups. High Odds ratio (>1) with significant P-value (from a simple chi-squared test) is required to associate that SNP with a specific disease. Wiki article example for CAD (coronary artery disease): G-allele of SNP1 (*rs1333049*) was found in 52.6% of cases vs 44.6% of controls. Corresponding P-value was 5.0 x 10 <sup>-15</sup>. 











Related terms:
* Haplotype - a group of alleles inherited together from a single parent. They are conserved across many generations. 1000 Genomes Project is an example; it also means a set of linked SNP alleles that occur together (at a high statistical significance). The HapMap project is using this for links to diseases; genetic test companies use this term to refer to specific mutations (e.g., STR mutation). 
* Imputation - statistical inference of unobserved genotypes. Starting with known haplotypes in a population (as with HapMap or the 1000 Genomes project), genetic variants are statistically associated with a phenotype. GWAS uses imputation to increase the coverage of SNPs, beyond those included in the microarray. Also, imputation allows overlap and meta-analysis of datasets obtained from different arrays. 
