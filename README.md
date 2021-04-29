# Supplemental materials for Blagrove & Barribeau (unpubl)

## Abstract
Mosquito-borne infectious diseases cause wide-spread loss of life and livelihood often in low-income settings. However, control of mosquito-vectored viral diseases such as West Nile virus (WNV) and Japanese encephalitis virus (JEV) remains challenging. Here we use an existing feature of the insect immune system to effectively vaccinate *Culex quinquefasciatus* mosquitoes against WNV infection. We find that priming mosquitoes by exposure to inactivated WNV reduces their likelihood of developing transmissible infections of WNV after live infection. We used RNA sequencing to identify gene expression in response to WNV and JEV infection, and the role of prior priming exposure on constitutive and induced expression on infection. Infection with either Flavivirus causes broad suppression of gene expression. WNV and JEV infection resulted in suppression of different suites of genes with notable immune genes, such as antimicrobial peptides, being strongly suppressed on WNV infection. We hypothesise   that the increased resistance to WNV infection seen in primed mosquitoes may be the result of priming nullifying the immune suppression found in non-primed WNV-fed mosquitoes, potentially through greater expression of mRNA regulatory genes such as cap-binding proteins in primed mosquitoes.


## UpSet results
UpSet is an interactive, web based visualization technique designed to analyze set-based data. UpSet visualizes both, set intersections and their properties, and the items (elements) in the dataset. Please see the project website at [http://vcg.github.io/upset/about](http://vcg.github.io/upset/about) for details about the technique, publications and videos.

The interactive version of our results can be accessed at [https://bite-and-sting.github.io/mosquitoPriming/](https://bite-and-sting.github.io/mosquitoPriming/).

## Supplementary tables and figures
in ```SupplementsGit``` directory you can find:
1. ST1_DE_tables.xlsx which contains tabs for each comparison and the differentially expressed genes from edgeR analyses.
2. ST2_GO_tables.xlsx which similarly contains tabs for different comparisons and the overrepresented gene ontology terms produced by topGO.
3. ST3_SharedDELit.xlsx Which compares our differentially expressed genes to that from Bartholomay et al. (2010), Science; Shin et al. (2014), BMC Genomics; Paradkar et al (2015), PLoS Pathogens.
4. ST4_SharedGOLit.xlsx The same as 3 but for GO terms.
5. ST5_cemitool.xlsx Which holds the results tables for each module from the network analysis in CemiTool.
6. ST6_TaxaLevel2.tsv which describes the microbial diversity of bacteria and viruses identified from idSeq.
7. Fig8_AD_deplot.pdf which shows differential expression of mosquitoes primed and infected with WNV vs unprimed uninfected controls.  