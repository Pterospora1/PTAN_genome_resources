# MAKER Configuration Files

This directory contains control and log files from the **MAKER genome annotation pipeline** used in the *Pterospora andromedea* (PTAN) project.

## Overview
Annotation of the PTAN genome was performed using **MAKER v2.31.10** (Campbell et al., 2015).  
MAKER integrates evidence-based and ab initio predictions to generate gene models, using RepeatMasker, BLAST, Exonerate, and GeneMark-ES+.

Run 17 produced the final annotation set archived in this repository, but the associated configuration (`.ctl`) and log files are currently being recovered from the original HPC environment.

At present, this folder contains **run 16 control files**, which reflect the near-final pipeline configuration and parameter structure used in run 17.

---

## Contents

| File | Description |
|------|--------------|
| `PTAN_maker_run16_combined_ctl` | Concatinated Options maker_opts.ctl, maker_exe.ctl, and maker_bopts.ctl files listing genome FASTA input, evidence datasets, and output parameters; Execution control file specifying paths to external executables (BLAST, SNAP, Augustus, etc.); BLAST/alignment parameter settings |

---

## Notes on Provenance

- The **final annotation (run 17)** used the same evidence and HMMs as run 16 but incorporated updated GeneMark training and revised repeat masking.
- The HPC directory for run 17 likely contains additional metadata (`maker_run17_master_datastore_index.log`, `.maker.output/` subdirectories, and standard output logs).
- These files will be added here once recovered, ensuring full reproducibility.

---

## Citation
Campbell MS, et al. 2015. MAKER v2: an annotation pipeline and genome-database management tool for second-generation genome projects. *BMC Bioinformatics* 16: 304.
