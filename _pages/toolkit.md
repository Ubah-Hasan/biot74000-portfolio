---
permalink: /toolkit/
title: "Bioinformatics Toolkit"
author_profile: true
---

## Bioinformatics Toolkit

Category 1 — Sequence Analysis & Genome Interpretation
BLASTN — Status: Complete
Use example: I used BLASTN to compare my phoP gene sequence (687 bp) against the NCBI nr/nt database, interpreting percent identity, query coverage, E‑values, and taxonomic distribution of hits.
Strength / limitation: BLASTN is fast and reliable for identifying homologs, but high identity does not guarantee identical biological function.

NCBI Genome Browser — Status: Complete
Use example: I located phoP on the Salmonella LT2 reference genome, recorded its coordinates, strand orientation, and neighboring genes, and checked operon context.
Strength / limitation: Provides accurate genomic context, but functional annotation is limited compared to Ensembl.

RefSeq / GenBank — Status: Draft
Use example: I retrieved BRCA1 RefSeq mRNA, examined CDS coordinates, and downloaded the FASTA file for sequence inspection.
Strength / limitation: Stable, curated reference sequences; however, some entries remain provisional.

Category 2 — Protein Structure & Functional Annotation
UniProtKB / SwissProt — Status: Complete
Use example: I retrieved the reviewed TP53 protein entry, examined functional domains, GO terms, and downloaded the canonical FASTA sequence.
Strength / limitation: Highly curated and reliable, but not all proteins have reviewed entries.

AlphaFold — Status: In‑Progress
Use example: I examined the predicted NPR3 structure and interpreted pLDDT confidence scores to identify stable vs disordered regions.
Strength / limitation: Extremely accurate for many proteins, but low-confidence regions require cautious interpretation.

InterPro — Status: Draft
Use example: I confirmed NPR3 protein domains using integrated signatures from Pfam and InterPro.
Strength / limitation: Integrates multiple annotation sources, but some predictions lack experimental validation.

Category 3 — Transcriptomics & Functional Genomics
DESeq2 — Status: Draft
Use example: I interpreted differential expression results by examining log₂ fold change and adjusted p‑values to identify significantly regulated genes.
Strength / limitation: Robust statistical modeling, but sensitive to low-count genes and normalization quality.

GO Enrichment Analysis — Status: In‑Progress
Use example: I explored enriched GO Biological Process terms to understand functional themes in differentially expressed gene lists.
Strength / limitation: Provides biological context, but enriched terms show correlation, not causation.

Volcano Plot — Status: Draft
Use example: I interpreted volcano plots to identify genes with strong expression changes and statistical significance.
Strength / limitation: Easy visualization of patterns, but subtle biological changes may be overlooked.

Category 4 — Computational Tools, Automation & Data Processing
RStudio — Status: In‑Progress
Use example: I ran provided R scripts for data transformation and visualization, learning how input files are read and processed.
Strength / limitation: User-friendly and reproducible, but requires correct file paths and familiarity with R syntax.

Command Line — Status: Draft
Use example: I practiced basic navigation and executed provided commands to run scripts and inspect directories.
Strength / limitation: Powerful for automation, but has a steep learning curve for beginners.
