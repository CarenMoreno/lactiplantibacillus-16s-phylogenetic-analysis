# lactiplantibacillus-16s-phylogenetic-analysis
Comparative phylogenetic analysis of 16S rRNA sequences from Lactiplantibacillus strains isolated from traditional regional cheeses.
<p align="center">
  <img src="https://img.shields.io/badge/R-%3E%3D4.0-276DC3?style=for-the-badge&logo=R&logoColor=white"/>
  <img src="https://img.shields.io/badge/DOI-10.3390%2Fbiotech13030029-28A745?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/GenBank-CB2%20OQ107531.1-E67E22?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/GenBank-CB12%20OQ107533.1-8E44AD?style=for-the-badge"/>
</p>
<p align="center">
  <em>Biotechnologist and MSc in Bioinformatics - International University of La Rioja (UNIR)</em><br>
  <strong>Caren Moreno</strong> · Bioinformatics · 2026
</p>


# Comparative Phylogenetic Analysis of Lactiplantibacillus 16S rRNA Sequences

Comparative phylogenetic analysis of **Lactiplantibacillus plantarum** strains isolated from traditional regional cheeses using partial 16S rRNA gene sequences deposited in GenBank.

This repository documents a bioinformatics workflow for sequence retrieval, multiple sequence alignment, molecular characterization and phylogenetic inference.

---

## Project Status

🚧 Work in progress

This repository is currently being expanded with additional analyses and visualizations.

---

## Research Context

The analyzed strains were isolated from traditional regional cheeses and were previously characterized during my undergraduate research in Biotechnology.

The corresponding 16S rRNA sequences are publicly available in GenBank and constitute the starting point for a comprehensive phylogenetic analysis.

---

## Planned Workflow

```text
GenBank sequences
        │
        ▼
Sequence quality assessment
        │
        ▼
Multiple sequence alignment
        │
        ▼
Phylogenetic tree reconstruction
        │
        ▼
Sequence similarity analysis
        │
        ▼
Genetic diversity analysis
        │
        ▼
Biological interpretation
```

---

## Repository Structure

```text
lactiplantibacillus-16s-phylogeny
│
├── README.md
│
├── data
│   ├── raw_sequences
│   ├── aligned_sequences
│
├── results
│   ├── blast_results
│   ├── identity_matrix
│   ├── phylogenetic_tree
│   ├── sequence_logo
│
├── figures
│   ├── phylogenetic_tree.png
│   ├── sequence_logo.png
│   ├── heatmap_identity.png
│
├── scripts
│   ├── sequence_download.py
│   ├── alignment.R
│   ├── phylogeny.R
│
└── report
    └── final_report.pdf


figures/
scripts/
report/
README.md
LICENSE
```

---

## Figures

### Study overview

<p align="center">
<img src="figures/workflow.png" width="750">
</p>

### Phylogenetic tree

<p align="center">
<img src="figures/phylogenetic_tree.png" width="750">
</p>

---

## Author

**Caren Moreno**

Biotechnologist

M.Sc. Student in Bioinformatics. International University of La Rioja (UNIR)
