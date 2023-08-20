# Epigenetic_variability_chrX
This repository contains the scripts (R Markdown files) that were used for the analyses accompanying the manuscript "The inactive X chromosome accumulates widespread epigenetic variability with age".

In this manuscript, we systematic annotated, interpretated of age-related differences in DNA methylation at the X chromosome at the level of both differences in mean (age-related differentially methylated CpGs, aDMCs) and differences in variability (age-related variably methylated CpGs, aVMCs).
![](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Figure%20S3.tiff) 

The scripts were run in order (from 1 to 10). The purpose of each script is as follows:

- [Script 1: Prepare X-chromosome methylation data from BIOS biobank](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_01_Xmethdata%20preparation.Rmd)

- [Script 2: aDMCs identification by double generalized linear model (DGLM)](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_02_aDMCs_identification_dglm.Rmd)

- [Script 3: aVMCs identification by double generalized linear model (DGLM)](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_03_aVMCs_identification_dglm.Rmd)

- [Script 4: Compare if DGLM results are robust and convincing](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_04_Sensitivity_analysis_limma.Rmd)

- [Script 5: aDMCs replication based on two external datasets](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_05_aDMCs_validation.Rmd)

- [Script 6: aVMCs replication based on two external datasets](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_06_aVMCs_validation.Rmd)

- [Script 7: Create an annotation file of the Illumina Infinium 450K array with CGI features and XCI status](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_07_annotate_X_CpGs.Rmd)

- [Script 8: Fuctional annotatation of XCI related features of aDMCs and aVMCs](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_08_Functional%20annotation%20of%20aDMCs%20and%20aVMCs.Rmd)

- [Script 9: Test assocaition between aDMCs/aVMCs methylation and X chromosome gene expression](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_09_Association%20with%20gene%20expression.Rmd)

- [Script 10: Identify differentially methylated regions (DMRs) on replicated aDMCs and aVMCs](https://github.com/YunfengLUMC/Epigenetic_variability_chrX/blob/main/Script_10_DMR_identification.Rmd)
