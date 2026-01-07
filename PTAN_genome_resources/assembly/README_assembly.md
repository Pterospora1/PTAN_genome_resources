# Genome Assembly

PacBio long-read sequences were assembled using **Canu** (Koren et al., 2017).  
The resulting *Pterospora andromedea* assembly (**PTAN_assembly_v1**) comprises **75 688 contigs** with a total span of approximately **1.52 Gb**.  
This assembly is publicly available at GenBank under accession **JBTLPU000000000** (version **JBTLPU010000000**).

---

## Access
The full FASTA file (`PTAN_unitigs_final_clean.fasta`) was deposited directly to **GenBank** and is not hosted in this repository due to size constraints.  
Please access it here:

🔗 [GenBank accession JBTLPU000000000](https://www.ncbi.nlm.nih.gov/nuccore/JBTLPU000000000)

---

## File Summary (for reference)

| File (archived at GenBank) | Description |
|-----------------------------|--------------|
| `PTAN_unitigs_final_clean.fasta` | Final decontaminated contig assembly used as input for annotation. |

---

## Assembly Methodology

Assembly was performed using **Canu v2.1.1** (Koren et al., 2017), optimized for PacBio continuous long reads with automatic error correction and repeat separation.  
Subsequent polishing steps were carried out before annotation with **MAKER v2.31.10**.

---

## Citation

Koren S, Walenz BP, Berlin K, Miller JR, Bergman NH, Phillippy AM. 2017.  
*Canu: scalable and accurate long-read assembly via adaptive k-mer weighting and repeat separation.*  
**Nature Methods 14:** 1073–1080.  
[https://doi.org/10.1038/nmeth.4462](https://doi.org/10.1038/nmeth.4462)

---
