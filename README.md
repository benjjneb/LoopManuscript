# Reproducible Analyses from the LoopSeq Manuscript

This repository hosts the reproducible workflow that performed the analyses presented in the manuscript [Ultra-accurate Microbial Amplicon Sequencing with Synthetic Long Reads](https://www.biorxiv.org/content/10.1101/2020.07.07.192286v1).

Rmarkdown documents are hosted in the root directory. The input sequencing data is not included in the repository for size reasons, and is instead [available from the SRA under BioProject Accession PRJNA644197](https://www.ncbi.nlm.nih.gov/sra/?term=PRJNA644197). Auxiliary data is included in the `Docs/` directory, RDS files holding intermediate data objects suitable for performing the analyses of the processed sequencing data are in the `RDS/` directory, and figures created by the Rmarkdown documents are in the `Figures/` directory. 

You can run these analyses on your own machine by (1) cloning the repository, (2) obtaining the raw sequencing data, (3) modifying the paths defined at the start of each Rmd document, (4) installing required libraries, and (5) pressing Run! Even without the sequencing data, the analysis Rmarkdown document can be run using the stored data objects in the `RDS/` directory.

These Rmarkdown documents have also been rendered into html format, and can be viewed in your web browser:

* [Evaluation of LoopSeq accuracy on Zymo mock community](https://benjjneb.github.io/LoopManuscript/LoopMS_16S_Zymo.html).
* [Evaluation of LoopSeq on Human Fecal samples, and comparison to PacBio](https://benjjneb.github.io/LoopManuscript/LoopMS_16S_Fecal.html).
* [Identifying foodborne pathogen species from retail meat samples using LoopSeq](https://benjjneb.github.io/LoopManuscript/LoopMS_16S_Meat.html).
* [Evaluating the error-free fraction of amplified sequencing reads as a function of read length and technology](https://benjjneb.github.io/LoopManuscript/ErrorFreeByLength.html).

Questions and comments are welcome on the Issues tracker for this repository: https://github.com/benjjneb/LoopManuscript/issues

Benjamin Callahan (benjamin DOT j DOT callahan AT gmail DOT com). Twitter: [\@bejcal](https://twitter.com/bejcal)
