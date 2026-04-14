# GC_Skew_Project

> With Yoonho Choi — Starting from 2023

---

## Overview

This project provides tools for analyzing GC skew and GC difference across genomic sequences, which are useful for identifying replication origins and strand asymmetries.

**Key Metrics:**

- **GC Skew** = (G − C) / (G + C)
- **GC Difference** = (G − C)

---

## Data

### Download

FASTA files can be downloaded from [NCBI](https://www.ncbi.nlm.nih.gov/). Whole genome sequences are recommended.

### Recommended Datasets

The following genome types tend to show clear, interpretable GC skew patterns:

- **Archaea**
- **Bacteria**
- **Mitochondria**
- **Chloroplast**

> **Note:** General eukaryotic sequences are compatible with the pipeline, but they often fail to demonstrate significant GC skew patterns due to their size and complexity.
