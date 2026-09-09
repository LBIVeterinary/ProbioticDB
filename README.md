# ProbioSML: A Machine Learning-Derived Genomic Dataset for Probiotic-Associated Bacteria

Welcome to the ProbioSML repository. This project provides a genomic dataset generated from machine learning analyses focused on bacteria frequently reported as probiotics.

This repository is directly associated with the article published in the journal Frontiers in Bioinformatics: 
"A machine learning-derived genomic dataset from bacteria frequently reported as probiotics".
DOI: https://doi.org/10.3389/fbinf.2026.1810235

---

## About the Database

ProbioSML was developed to address the shortage of reusable, large-scale genomic datasets in the field of probiogenomics. It was generated from comparative analyses of bacterial genomes belonging to taxa commonly reported as probiotics, contrasted with reference gut-associated bacteria.

By utilizing pangenomic analysis combined with supervised machine learning algorithms — including Random Forest, Support Vector Machine (SVM), and Logistic Regression —, the most discriminative genomic features between the groups were extracted.

The dataset comprises:
* 1,072 non-redundant protein-coding sequences.
* Gene presence-absence matrices.
* Detailed functional annotations.

## What can this dataset be used for?

ProbioSML is an open-access data resource focused on supporting the bioinformatics and microbial genomics community. It is ideal for:

1. Exploratory Analyses: Investigating genomic and functional patterns associated with bacterial taxa commonly used as probiotics.
2. Comparative Genomics: Conducting genome comparison studies in microbial ecology, exploring adaptation, survival, colonization, and competition capabilities in host-associated environments.
3. Methodological Benchmarking: Serving as a structured dataset to train, validate, or calibrate new machine learning models and feature extraction algorithms in genomics.
4. Hypothesis Generation: Supporting the formulation of new in silico hypotheses that can guide future experimental studies (in vitro and in vivo).

## Limitations and Interpretation (What it is NOT)

To ensure scientific rigor when using these data, it is vital to respect the following premises:

* Not universal causal determinants: The genomic features present in this dataset must not be interpreted as a list of causal genes defining "probiotic functionality". Probiotic effects are highly context-dependent (host and ecology) and strain-specific.
* The data represent genomic patterns and statistical signatures of bacterial taxa frequently used as probiotics, which may also reflect ecological and taxonomic adaptations to specific niches.

## Data Access

The complete final dataset (ProbioSML) is hosted on Zenodo, ensuring persistent access and versioning:
Access ProbioSML on Zenodo: https://doi.org/10.5281/zenodo.14181443

(In this GitHub repository, you can find the scripts [insert links or folders to scripts here, if any] used for feature extraction, data processing, and statistical modeling).

## Citation

If you use this dataset, matrices, or scripts in your research, please cite our work:

> Rodrigues DLN, Sodrzeieski PA, Auger S, Chatel J-M, Benko-Iseppon AM, Azevedo V, Soares SdC and Aburjaile FF (2026). A machine learning-derived genomic dataset from bacteria frequently reported as probiotics. Frontiers in Bioinformatics 6:1810235. doi: 10.3389/fbinf.2026.1810235

DOI:https://doi.org/10.3389/fbinf.2026.1810235
---
Developed by the Integrative Bioinformatics Laboratory (IBL).
