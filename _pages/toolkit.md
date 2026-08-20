---
permalink: /toolkit/
title: "Bioinformatics Toolkit"
author_profile: true
---


_A curated catalogue of the tools, databases, and methods I have worked with,
organized by what they are used for._

## Sequence Analysis Tools

### BLAST (Basic Local Alignment Search Tool)

**Use example:** I used BLASTN to compare my phoP gene sequence (687 bp) against the NCBI nr/nt database, interpreting percent identity, query coverage, E‑values, and taxonomic distribution of hits.


**Strengths / limitations:** BLASTN is fast and reliable for identifying homologs, but high identity does not guarantee identical biological function.


---

### NCBI Genome Browser

**Use example:**  I located phoP on the Salmonella LT2 reference genome, recorded its coordinates, strand orientation, and neighboring genes, and checked operon context.

**Strengths / limitations:** Provides accurate genomic context, but functional annotation is limited compared to Ensembl.

---

### RefSeq / GenBank

**Use example:** I retrieved BRCA1 RefSeq mRNA, examined CDS coordinates, and downloaded the FASTA file for sequence inspection.

**Strengths / limitations:** Stable, curated reference sequences; however, some entries remain provisional.

## Databases & Data Retrieval

### UniProt

**Use example:** I retrieved the reviewed TP53 protein entry, examined functional domains, GO terms, and downloaded the canonical FASTA sequence.

**Strengths / limitations:** Highly curated and reliable, but not all proteins have reviewed entries.

---

## Data Visualization

### R Base Plotting

**Use example:** I used base R plotting functions such as plot() and hist() to quickly explore Aspergillus niger colony diameter across different heavy‑metal concentrations (Ni, Zn, Pb). These initial checks helped me confirm trends and identify any unusual values before generating final figures.

**Strengths / limitations:**  Fast and simple for early exploration; useful for checking raw patterns in diameter vs. concentration.


---

### ggplot2

**Use example:** I used ggplot2 to create the final bar plots, scatter plots, and error‑bar figures showing how A. niger colony diameter changed with increasing metal concentration. This included grouped bar charts for Day 1 vs Day 2 and dose‑response curves for Ni, Zn, and Pb.


**Strengths / limitations:**  Highly customizable and ideal for producing clear, professional figures suitable for assignments and reports.

