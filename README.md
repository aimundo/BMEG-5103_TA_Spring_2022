# BMEG 5103: Introduction to Survival Analysis

This is the page for the Survival Analysis component of BMEG 5103: Design and Analysis of Experiments in Biomedical Research for the Spring of 2022.

## Goals

-  Introduce the concept of "censored data"
-  Familiarize students with the mainstay Statistical tools used to analyze censored data
    - Kaplan-Meier estimator
    - Log-rank test

Additionally, the Kaplan-Meier Survival Curve and associated calcuations will be discussed.

## Materials

This part of the course relies on data to demonstrate how the analyses are performed.

**Slides** can be accesed [here](https://aimundo.github.io/BMEG-5103_TA_Spring_2022/slides/Survival_analysis.html#/title-slide) <br>
**Datasets** can be found [here](https://github.com/aimundo/BMEG-5103_TA_Spring_2022/tree/main/slides/data).

### About the Datasets
 
  - `CRC_data.csv` is a dataset regarding mortality of patients with Dukes' C colorectal cancer. This dataset is used to explain the Kaplan-Meier estimator.
  - `glioma.csv` is a dataset regarding mortality of patients with two types of glioma (astrocytoma and glioblastoma). This dataset is used to explain the Log-rank test.

A third dataset is used to demonstrate the use of Survival curves for three different groups. It is the `colon` dataset from the R package {survival}.

Thes slides for this part of the course were created using [Quarto](https://quarto.org/docs/presentations/), R, and the {tidyverse}, {survival}, and {scico} packages. <br>
The repository with all the data and materials can be accessed [here](https://github.com/aimundo/BMEG-5103_TA_Spring_2022)

### Contact
Questions, comments or suggestions are welcome. aimundo AT uark.edu
