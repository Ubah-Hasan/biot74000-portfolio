---
permalink: /toolkit/
title: "Bioinformatics Toolkit"
author_profile: true
---

<!--
  ============================================================================
  SECTION 2: BIOINFORMATICS TOOLKIT  (30 points)
  ============================================================================
  A curated, annotated catalogue of the tools, databases, file formats, and
  methods you worked with in this course. This is the POLISHED version of your
  Course Learning Log — not a copy-paste, but a professional re-write,
  organized by CATEGORY (not by unit).

  FOR EACH ENTRY, INCLUDE:
    - Tool / database name
    - 1–2 sentences describing one specific use example from the course
      that YOU performed
    - One note on a strength or a limitation

  SUGGESTED CATEGORIES (use the ones that fit your work; add or remove as needed):
    Sequence Analysis Tools · Databases & Data Retrieval ·
    Genome & Transcriptome Analysis · Protein Structure & Function ·
    Computational & Scripting Tools · Data Visualization

  Entries copied word-for-word from documentation will not receive full marks —
  use your own words. Quality and honesty matter more than the number of entries.

  HOW TO EDIT:
    - Replace the example entries below with your own.
    - Keep the same simple pattern: a "##" category heading, then one
      "###" heading per tool, then your notes underneath.
    - Delete these grey instruction notes before you submit.
  ============================================================================
-->

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

**Use example:** I used base R plotting functions (hist(), plot()) to visualize DNase concentration vs. optical density and to inspect data distributions before analysis.


**Strengths / limitations:**  Simple, fast, built into R; ideal for quick exploratory checks.
Limited styling; requires manual adjustments for publication‑quality figures.

---

<!--
  Add more categories and entries by copying the pattern above.
  Aim for a toolkit that reads like notes a working professional would keep.
-->
