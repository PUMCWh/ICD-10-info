# ICD-10-info
# Supplementary Data for "Multimorbidity Profiles in Patient Population from Central China"

This repository contains supplementary data for the study titled "Multimorbidity Profiles in Patient Population from Central China: A Study Based on Electronic Health Records".

---

## Description

This dataset provides a comprehensive list of all International Classification of Diseases, Tenth Revision (ICD-10) three-character codes that appeared in our study cohort. The data were derived from the electronic health records (EHRs) of nearly 3.2 million individuals in Yichang City, Central China, from 2016 to 2023.

This file serves as a supplement to **Supplementary Table S25** in the main publication's supplementary materials, which lists only the top 50 most prevalent codes.

---

## Files

* `icd10_code_list_full.csv`: The complete list of ICD-10 codes, their descriptions, chapter/block information, and prevalence in the study population.

---

## Data Dictionary

The `.csv` file contains the following columns:

| Column Name         | Description                                                                 |
| ------------------- | --------------------------------------------------------------------------- |
| `code`              | The three-character ICD-10 code.                                            |
| `prevalence`        | The prevalence of the condition in the overall study population (%).          |
| `description`       | The full English description of the ICD-10 code.                            |
| `chapter`           | The numerical chapter of the ICD-10 classification.                         |
| `chapter_description` | The full description of the ICD-10 chapter.                                 |
| `block`             | The code range for the block within the chapter that the code belongs to.     |

---
