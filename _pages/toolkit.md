---
permalink: /toolkit/
title: "Bioinformatics Toolkit"
author_profile: true
---

Sequence Analysis Tools
BLAST (Basic Local Alignment Search Tool)
Use example: I used BLASTN to compare my phoP gene sequence (687 bp) against the NCBI nr/nt database, interpreting percent identity, query coverage, E‑values, and taxonomic distribution of hits.


Strengths / limitations: BLASTN is fast and reliable for identifying homologs, but high identity does not guarantee identical biological function.


NCBI Genome Browser
Use example: I located phoP on the Salmonella LT2 reference genome, recorded its coordinates, strand orientation, and neighboring genes, and checked operon context.

Strengths / limitations: Provides accurate genomic context, but functional annotation is limited compared to Ensembl.


RefSeq / GenBank
Use example: I retrieved BRCA1 RefSeq mRNA, examined CDS coordinates, and downloaded the FASTA file for sequence inspection.

Strengths / limitations:Stable, curated reference sequences; however, some entries remain provisional.


Databases & Data Retrieval
UniProt
Use example:  I retrieved the reviewed TP53 protein entry, examined functional domains, GO terms, and downloaded the canonical FASTA sequence.
Strengths / limitations: Highly curated and reliable, but not all proteins have reviewed entries.

Data Visualization
R Base Plotting
Use example:  I used base R plotting functions (hist(), plot()) to visualize DNase concentration vs. optical density and to inspect data distributions before analysis.

Strengths / limitations: Simple, fast, built into R; ideal for quick exploratory checks.
Limited styling; requires manual adjustments for publication‑quality figures.
