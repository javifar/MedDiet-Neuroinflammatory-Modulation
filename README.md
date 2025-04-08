# 🧬 Mediterranean Diet & Neuroinflammation Gene Expression (PREDIMED Substudy)

This repository contains R scripts and supplementary materials related to the data preprocessing and analysis of the study:

**"Mediterranean Diet Modulation of Neuroinflammation-Related Genes in Elderly Adults at High Cardiovascular Risk"**  
Published in *Nutrients (2024), 16, 3147*.  
[🔗 DOI: 10.3390/nu16183147](https://doi.org/10.3390/nu16183147)

---

## 📖 Study Purpose

This project explores the transcriptional impact of two traditional Mediterranean Diet (MedDiet) interventions—one enriched with **extra-virgin olive oil (EVOO)** and the other with **nuts**—on gene expression related to **neuroinflammation** and **cardiovascular risk**. The analyses were performed using data from a sub-cohort (n = 134) of the larger **PREDIMED trial**.

We evaluated key inflammation-related genes (e.g., *CDKN2A*, *IFNG*, *TGFB2*, *NAMPT*, *NLRP3*) at baseline and after a 12-month intervention using qRT-PCR techniques.

---

## 📦 Required R Packages

Make sure the following R packages are installed:

```r
install.packages(c("haven", "broom", "tidyverse", "nlme", "writexl", "ggthemes"))

