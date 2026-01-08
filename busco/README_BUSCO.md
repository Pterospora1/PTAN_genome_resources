# BUSCO Completeness Assessment

BUSCO (**Benchmarking Universal Single-Copy Orthologs**) analyses were used to assess genome completeness for the *Pterospora andromedea* assembly, and for comparison with symbiotic partner genomes (*Hypopitys monotropa* and *Rhizopogon salebrosus*).

All analyses were performed using **BUSCO v5.7.1** (Manni et al., 2021) in genome mode with the appropriate lineage datasets from **OrthoDB v10**.

---

## Input Genomes
| Species | Source | Lineage Dataset | Genome Size | Notes |
|----------|---------|----------------|--------------|-------|
| *Pterospora andromedea* | GenBank JBTLPU000000000 | eukaryota_odb10 | 1.52 Gb | PTAN unitig assembly used as input |
| *Hypopitys monotropa* | GenBank GCA_002855965.1 | embryophyta_odb10 | 2.35 Gb | Whole-genome shotgun assembly |
| *Rhizopogon salebrosus* | JGI Project 1039528 | fungi_odb10 | ~50 Mb | Ectomycorrhizal fungal symbiont |

---

## Summary Results

| Dataset | C: Complete | S: Single | D: Duplicated | F: Fragmented | M: Missing | n (Total BUSCOs) | E-value Threshold |
|----------|-------------|------------|----------------|----------------|--------------|------------------|
| **PTAN_unitigs_eukaryota_BUSCO** | 15.7 % | 15.3 % | 0.4 % | 18.8 % | 65.5 % | 255 | 20.0 % |
| **MHYPO_BUSCO** | 22.3 % | 21.1 % | 1.2 % | 34.0 % | 43.7 % | 1614 | 28.3 % |
| **RHI_BUSCO** | 98.4 % | 97.4 % | 1.1 % | 0.8 % | 0.8 % | 758 | 20.6 % |

*(C = Complete, S = Single-Copy, D = Duplicated, F = Fragmented, M = Missing)*

---

## Interpretation

- The **Rhizopogon salebrosus** genome shows very high completeness (98.4 %), consistent with a well-assembled fungal genome.  
- The **Hypopitys monotropa** genome shows moderate completeness (22.3 %), reflecting challenges in assembly of highly reduced mycoheterotrophic plant genomes.  
- The **Pterospora andromedea** assembly shows 15.7 % completeness within the broad eukaryotic dataset, typical of large, heterotrophic, and partially repetitive genomes.

---

## File Summary

| File | Description |
|------|--------------|
| `BUSCO_summary_table.txt` | Consolidated BUSCO summary across species and datasets. |

All raw BUSCO result folders (e.g. `PTAN_unitigs_eukaryota_BUSCO/`, `MHYPO_BUSCO/`, `RHI_BUSCO/`) are **not included** in this repository due to their size, but are reproducible using the parameters above.

---

## Citation

Manni M, Berkeley MR, Seppey M, Simão FA, Zdobnov EM. 2021.  
*BUSCO Update: Novel and Streamlined Workflows along with Broader and Deeper Phylogenetic Coverage for Scoring of Eukaryotic, Prokaryotic, and Viral Genomes.*  
**Molecular Biology and Evolution 38(10):** 4647–4654.  
[https://doi.org/10.1093/molbev/msab199](https://doi.org/10.1093/molbev/msab199)

---
