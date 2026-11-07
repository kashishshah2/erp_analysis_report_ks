
# N400 ERP Analysis Report

**PSYC2015 – Data Science for Cognitive Neuroscience and Psychology**

This repository contains a reproducible Quarto analysis
of the N400 event-related potential using the ERP CORE
semantic word-pair dataset.

## View the completed report

[Open my full N400 analysis report](https://kashishshah2.github.io/erp_analysis_report_ks/)

## Analysis

The report examines semantic relatedness effects at
electrode CPz within the 300–500 ms interval.

The analysis includes 39 participants and compares
grand-average waveforms for related and unrelated targets.

## Reproducibility

To reproduce this analysis:

1. Clone the repository.
2. Install the project's Python dependencies and Quarto.
3. Place the supplied raw N400 EEG files in `data/raw/`.
4. Retain the original data licence.
5. Run `quarto render index.qmd`.

## Reference

Kappenman et al. (2021).
ERP CORE: An open resource for human event-related
potential research.
https://doi.org/10.1016/j.neuroimage.2020.117465
