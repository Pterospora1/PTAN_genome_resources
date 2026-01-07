# Comparative Functional Genomics

Functional annotation and comparative analysis were accomplished with custom BLAST searches for proteins in published biochemical pathways relevant to:

- Heterotrophic carbon fixation  
- Glycolysis and gluconeogenesis  
- Krebs cycle  
- Pentose phosphate and glyoxylate pathways  
- Calvin–Benson–Bassham (CBB) cycle  
- Starch biosynthesis  
- CO₂ assimilation  
- Amino acid and ammonium assimilation  
- Carbon–nitrogen balance  

Domain validation employed **NCBI CD-Search** and **InterProScan**, with unresolved cases evaluated using **HMMER v3.4** and **Pfam-A** profile HMMs.  
Only sequences meeting Pfam gathering thresholds and reciprocal CD-Search support were retained as predicted enzymes.  
Corresponding plant and fungal homologs were identified in the *Hypopitys* GenBank whole genome shotgun assembly (GCA_002855965.1) and *Rhizopogon salebrosus* genome (JGI Project 1039528).

This directory contains results from conserved domain (CD) and InterProScan analyses used to functionally validate predicted enzymes from the *Pterospora andromedea* genome annotation.

Each file lists protein or transcript sequences that were matched to conserved domains in the NCBI Conserved Domain Database (CDD), Pfam-A, or InterPro databases. Only sequences meeting Pfam gathering thresholds and reciprocal CD-Search support were retained.

---

## File Descriptions

| File | Description |
|------|--------------|
| `PTAN_GenBank_proteins_CD_hits_final.fasta` | *Pterospora* protein conserved domain hits |
| `PTAN_GenBank_transcripts_CD_hits_final.fasta` | *Pterospora* transcript conserved domain hits |
| `Mhypo_GenBank_transcripts_CD_hits_final.fasta` | *Hypopitys* transcript conserved domain hits |
| `Rhizopogon_salebrosus_proteins_final.fasta` | *Rhizopogon salebrosus* protein hits |

---

## Citation

Database sources:
- NCBI CDD v3.20  
- Pfam-A release 36.0  
- InterProScan v5.66  
- HMMER v3.4 (Pfam profile validation)
