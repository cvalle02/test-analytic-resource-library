---
title: "Data & Metadata Annotations"
permalink: /data-metadata/
---

## General Notes about the Data and Metadata

- Missing and non-informative responses (e.g., “don’t know” or “refused”), as well as values not defined in or outside the range of the original study investigator-provided data dictionary and datasets, were converted to blank (missing) values within the harmonized data repository. 
- Information on sibling or family linkages, when available, is typically documented in the study metadata rather than as explicit variables in the harmonized datasets.
- Discrepancies may exist between original study investigator-provided data dictionaries and the harmonized datasets. In some cases, errors were identified and corrected in the harmonized files after consultation with the original study investigator; however, the original study investigator-provided datasets and data dictionaries may have been left unchanged.
- In some cases, the original study investigator provided multiple separate variables representing different categories of the same construct (for example, ethnicity recorded across several category-specific indicator variables). During standardization, these were consolidated into a single multi-category variable.
- Variables in the harmonized repository may differ from those in original study investigator-provided data dictionaries and datasets as there were instances when not all data were standardized to the HHEAR Ontology. 

## Core reference documents

- **Master Codebook:** [link](../assets/files/Master_Codebook_Sorted.xlsx)

  The Master Codebook provides a reference of all variables and codes used across the repository, spanning all studies and all harmonized datasets. It is organized into sections to make it easier to identify the types of data available. Codebooks are automatically generated based on the specific studies and datasets selected for download; users should prioritize the study-specific codebook included with their download.

- **Example Codebook:** [link](../assets/files/example_codebook.csv)

  This Example Codebook illustrates the structure and format of a study-specific codebook generated at the time of data download, based on a selection of three studies in the repository. Codebooks generated with a user’s selected studies and datasets are designed to be imported directly into statistical software (e.g., R) and should be used for analysis. Users should rely on the codebook included with their download rather than the Master Codebook when working with data.

- **Notes for Specific Studies:** [link](../assets/files/Study_Notes.csv)

  This CSV file lists all current studies in the repository by their study identifier and indicates whether a study has associated notes or special considerations.


