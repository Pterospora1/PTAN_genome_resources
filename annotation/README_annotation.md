# Genome Annotation

Annotation of the *Pterospora andromedea* genome (assembly accession **JBTLPU000000000**) was performed using **MAKER v2.31.10** (Campbell et al., 2015) with integrated evidence from **RepeatMasker**, **BLAST**, **Exonerate**, and **GeneMark-ES+**.  
Reference protein datasets included *Arabidopsis thaliana*, *Camellia sinensis*, *Hypopitys monotropa*, and *Vaccinium corymbosum*, together with custom GeneMark HMMs.

Functional annotation and comparative analysis were conducted through curated BLAST searches targeting enzymes involved in:
- Heterotrophic carbon fixation  
- Glycolysis / gluconeogenesis and TCA cycle  
- Pentose phosphate and glyoxylate pathways  
- Calvin–Benson–Bassham (CBB) cycle  
- Starch biosynthesis  
- CO₂ assimilation, amino-acid / ammonium assimilation, and C–N balance  

Conserved-domain validation employed NCBI CD-Search and InterProScan; ambiguous hits were re-evaluated using **HMMER v3.4** with **Pfam-A** profile HMMs.  
Only sequences meeting Pfam gathering thresholds *and* reciprocal CD-Search support were retained as confidently predicted enzymes.  
Comparative homologs were identified from *Hypopitys monotropa* (GenBank GCA_002855965.1) and *Rhizopogon salebrosus* (JGI Project 1039528).

---

## Directory Overview

| Subdirectory / File | Description |
|----------------------|-------------|
| **Functional_Domains/** | Protein and transcript datasets with conserved-domain (CD) hits. |
| ├── `PTAN GenBank proteins CD hits final.fasta` | *Pterospora* predicted protein sequences with CD annotations. |
| ├── `PTAN GenBank transcripts CD hits final.fasta` | *Pterospora* predicted transcript sequences with CD annotations. |
| ├── `Mhypo GenBank transcripts CD hits final.fasta` | *Hypopitys monotropa* transcript homologs. |
| ├── `Rhizopogon salebrosus proteins final.fasta` | *Rhizopogon salebrosus* homologs. |
| └── `README_Functional_Domains.md` | Notes and methodology for functional-domain identification. |
| **maker_config_files/** | Configuration files used for MAKER run 16. |
| ├── `PTAN_maker_run16_combined_ctl` | Combined control file including `maker_opts`, `maker_bopts`, and `maker_exe`. |
| └── `README_maker_configs` | Description of MAKER parameters and evidence sources. |
| **ptanmaker17.all.maker.proteins.fasta** | Predicted *Pterospora* protein sequences (MAKER run 17). |
| **ptanmaker17.all.maker.transcripts.fasta** | Predicted *Pterospora* transcript sequences (MAKER run 17). |

---

## Citation

Campbell MS, Holt C, Moore B, Yandell M. 2015.  
*Genome Annotation and Curation Using MAKER and MAKER-P.*  
**Current Protocols in Bioinformatics 48:** 4.11.1 – 4.11.39.  
[https://doi.org/10.1002/0471250953.bi0411s48](https://doi.org/10.1002/0471250953.bi0411s48)

---

## Notes
- The **GFF3** annotation file corresponding to these predictions is archived separately on **Zenodo** (see *Data Availability* in the main repository README).  
- Predicted proteins and transcripts hosted here correspond to the version described in **GenBank JBTLPU010000000**.

---

