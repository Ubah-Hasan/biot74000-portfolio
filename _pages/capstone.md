---
permalink: /capstone/
title: "Capstone Connection"
author_profile: true
---

<!--
  ============================================================================
  SECTION 4: CAPSTONE CONNECTION  (20 points)  |  Suggested length: 200–300 words
  ============================================================================
  A concise, professional summary of how you applied bioinformatics to your
  capstone project. This draws from your Assignment 2 work — it is a
  professional-context summary, NOT a repeat of the assignment.

  INCLUDE:
    - A 2–4 sentence description of your capstone project (assume a general
      audience who is not in your program)
    - The bioinformatics tool, dataset, or method you applied in Assignment 2,
      and why it was relevant
    - What you found or produced, described in plain language
    - 1–2 sentences on how this bioinformatics component strengthened your capstone
    - (Optional) embedded images or output figures — see the guide for how to
      add an image

  HOW TO EDIT:
    - Replace the placeholder text below with your own.
    - Delete these grey instruction notes before you submit.
  ============================================================================
-->

## My Capstone Project

My Capstone project investigates whether Aspergillus niger can serve as a low‑cost, visual indicator of heavy‑metal contamination in soil. Metals such as lead (Pb), nickel (Ni), and zinc (Zn) accumulate in soil and water systems and normally require expensive analytical instruments (ICP‑MS, IC‑OES) for detection. This matters because accessible screening tools can support early detection in smaller labs without specialized equipment. 

## The Bioinformatics Component

For Assignment 2, I analyzed our capstone’s A. niger colony‑diameter data using R. I imported the raw measurements, cleaned concentration values, corrected data‑type issues, summarized the dataset, and generated visualizations using ggplot2. I also fit linear regression models to examine how colony diameter changed with increasing concentrations of nickel, zinc, and lead.

This analysis showed a clear negative dose‑response trend: as metal concentration increased, colony diameter decreased. Nickel produced the strongest inhibitory effect, which aligned with our capstone decision to expand the nickel experiment with additional concentrations.


## Why It Strengthened My Capstone

Adding this bioinformatics analysis made my capstone stronger by providing quantitative evidence for the inhibitory effects of heavy metals on A. niger. The R workflow allowed me to visualize trends clearly, validate our experimental observations, and support the conclusion that colony diameter can be used as a practical indicator of metal stress.

<!--
  OPTIONAL — to embed an image or figure you produced:
  1. Upload the image file to the images/ folder in your repository.
  2. Add a line like this where you want it to appear (remove the leading
     grey-comment marks):

     ![Short description of the figure](/biot74000-portfolio/images/your-figure.png)

  Make sure the path matches your repository name.
-->
