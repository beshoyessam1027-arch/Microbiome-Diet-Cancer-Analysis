# Transcriptional Response to Broccoli Intervention in Prostate Cancer

## 🔬 Project Overview
This project analyzes RNA-seq data from **Patient 34** (BioProject: PRJEB25542) to investigate how a 12-month diet of high-glucoraphanin broccoli soup affects gene expression in prostate tissue.

## 📊 Dataset Metadata
| Feature | Baseline (Before) | 12 Months (After) |
| :--- | :--- | :--- |
| **Sample Accession** | ERR2399814 | ERR2399815 |
| **Intervention** | None (Baseline) | Broccoli Soup |
| **Tissue** | Prostate Biopsy | Prostate Biopsy |

## 🛠️ Bioinformatics Pipeline
1. **Data Acquisition:** SRA-Toolkit via Galaxy Europe.
2. **Quality Control:** FastQC (Checked for adapters and sequence quality).
3. **Taxonomic/Transcriptomic Profiling:** Kraken2 for classification.
4. **Visualization:** Pavian for Sankey diagrams.

   ## 📊 Statistical Summary (MultiQC)

The MultiQC report aggregates the classification results for both baseline and post-intervention samples. 

### Observation:
- **Host DNA Dominance:** As expected in prostate tissue samples, nearly 100% of reads remain unclassified against the standard microbial database, representing the host (Human) genome.
- **Microbial Presence:** Minor traces of *Aspergillus fumigatus* and other species were detected, providing a baseline for the prostatic microbiome environment.

## 📈 Results (Patient 34 Comparison)
### Before Intervention (Baseline)
![Sankey Before](<img width="1020" height="600" alt="image" src="https://github.com/user-attachments/assets/8bc2f045-5844-4e63-95ef-0545c4a75c95" />)

### After 12-Month Broccoli Diet
![Sankey After](<img width="1020" height="600" alt="image" src="https://github.com/user-attachments/assets/f6f0e1ad-8ab2-4236-a234-48258259a91e" />)

