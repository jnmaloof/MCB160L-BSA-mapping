# Mapping mutants by Bulk Segregant Analysis and Illumina Sequencing
# Day 3: Find Candidate Regions and Genes

## Intro

 
## Run SHOREmap 

We have already identified SNPs where Col and Ler differ for you.  These are in the `insert file name`

This will highlight regions of the genome where the allele frequency skews towards homozygous Columbia.

The app will run the following steps:

* __SHOREmap convert__ will convert the vcf file into a format that SHOREmap understands
* __SHOREmap extract__ will extract the F2 sequence to only retain positions where Col and Ler differ
* __SHOREmap outcross__ actually does the analysis and produced plots to visualize candidate regions

---

## Run SHOREmap annotate

Which of the possible mutations is likely to actually cause the mutant phenotype?  __SHOREmap annotate__ identifies which candidate SNPS are in genes and predicted to cause coding changes.

