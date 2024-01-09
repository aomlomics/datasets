# Reference Databases

The table below lists reference databases (fasta+taxonomy or classifier) used by the AOML 'Omics program. All databases listed here have been tested with Qiime2-2023.2 to Qiime2-2023.5.

## Current databases

Title                                         | Type           | Target                                         | Number of sequences    | URL
--------------------------------------------- | -------------- | --------------------------------------------- | ---------------------- | -----
PR2 18S V9 database (dereplicated) | fasta+taxonomy | 18S V9 (protists, some metazoans)    | 19,470  sequences,<br />11,748 taxa                 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10137946.svg)](https://doi.org/10.5281/zenodo.10137946) <br /> Files: pr2_version_5.0.0_SSU_18S-V9_uniq_seqs.qza,<br />pr2_version_5.0.0_SSU_18S-V9_uniq_tax.qza
PR2 18S V9 database (dereplicated) | classifier | 18S V9 (protists, some metazoans)    | 19,470  sequences,<br />11,748 taxa                 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10137946.svg)](https://doi.org/10.5281/zenodo.10137946) <br /> Files: pr2_v5.0.0_SSU_18S-V9_uniq-classifier.qza 
SILVA 16S V4-V5 database (dereplicated)    | fasta+taxonomy | 16S V4-V5 (bacteria, archaea)    | 309,567  sequences,<br />46,254 taxa                 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8302188.svg)](https://doi.org/10.5281/zenodo.8302188) <br /> Files: silva-138_1-99-515f_926r-uniq-seqs.qza,<br />silva-138_1-99-515f_926r-uniq-tax.qza
SILVA 16S V4-V5 classifier: water (saline)<br />(dereplicated)    | weighted naive-bayes classifier  | 16S V4-V5 (bacteria, archaea) from seawater         | 309,567 sequences,<br />46,254 taxa                  |  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8302188.svg)](https://doi.org/10.5281/zenodo.8302188) <br /> File: silva-138_1-99-515f_926r-uniq-water-saline-classifier.qza
SILVA 16S V4-V5 classifier: sediment (saline)<br />(dereplicated) | weighted naive-bayes classifier | 16S V4-V5 (bacteria, archaea) from marine sediments | 309,567 sequences,<br />46,254 taxa             | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8302188.svg)](https://doi.org/10.5281/zenodo.8302188) <br /> Files: silva-138_1-99-515f_926r-uniq-sediment-saline-classifier.qza
Leray COI ([rCRUX](https://github.com/CalCOFI/rCRUX)), excl. Insecta, Amphibia   | fasta+taxonomy | COI with Leray primers (excl. Insecta, Amphibia)    | 848,097 sequences,<br />117,853 taxa                 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10456134.svg)](https://doi.org/10.5281/zenodo.10456134) <br /> Files: COI_rCRUX_filt_20231110.qza,<br />COI_rCRUX_taxonomy_filt_20231110.qza 
Leray COI ([rCRUX](https://github.com/CalCOFI/rCRUX)), excl. Insecta, Amphibia   | naive-bayes classifier | COI with Leray primers (excl. Insecta, Amphibia)    | 848,097 sequences,<br />117,853 taxa                 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10456134.svg)](https://doi.org/10.5281/zenodo.10456134) <br /> Files: COI_rCRUX_filt_20231110-classifier.qza  

## Previous databases

Title                                         | Type           | Target                                         | Number of sequences    | URL
--------------------------------------------- | -------------- | --------------------------------------------- | ---------------------- | -----
SILVA 16S V4-V5 database (not dereplicated)    | fasta+taxonomy | 16S V4-V5 (bacteria, archaea)    | 388,496 sequences,<br />46,254 taxa                 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8301740.svg)](https://doi.org/10.5281/zenodo.8301740) <br /> Files: silva-138_1-99-515f_926r-seqs.qza,<br />silva-138_1-99-515f_926r-tax.qza
SILVA 16S V4-V5 classifier: water (saline)<br />(not dereplicated)    | weighted naive-bayes classifier  | 16S V4-V5 (bacteria, archaea) from seawater         | 388,496 sequences,<br />46,254 taxa                  |  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8301740.svg)](https://doi.org/10.5281/zenodo.8301740) <br /> File: silva-138_1-99-515f_926r-water-saline-classifier.qza
SILVA 16S V4-V5 classifier: sediment (saline)<br />(not dereplicated) | weighted naive-bayes classifier | 16S V4-V5 (bacteria, archaea) from marine sediments | 388,496 sequences,<br />46,254 taxa             | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8301740.svg)](https://doi.org/10.5281/zenodo.8301740) <br /> Files: silva-138_1-99-515f_926r-q2_2023_2-sediment-saline-classifier.qza

