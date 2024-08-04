---
title: Phenotype-driven variant prioritization tools
date: 2022-02-01
external_link: 
url_pdf: uploads/Phenotype_driven_variant_prioritization_tools.pdf
tags:
  - Transcriptomics
  - RNA-seq
  - dilated cardiomyopathy
  - genome-scale metabolic models

image:
  caption: 'FBA analysis in DCM patients.'
  focal_point: ""
  preview_only: false
---

RNA-sequencing dataset analysis and metabolic pathway analysis of patients with dilated cardiomyopathy

### Summary
  
#### **Background**
Dilated cardiomyopathy (DCM) is a heart condition characterized by dilation of the left or both ventricles, resulting in a weakened heart muscle and reduced pumping ability. It is a major cause of heart failure and often leads to heart transplantation. DCM affects males more frequently and severely than females. Recent studies suggest that energy metabolism alterations, including a shift from fatty acid oxidation (FAO) to glycolysis, are involved in DCM. However, sex-related differences in cardiac energy metabolism in DCM are not well understood. This study aims to explore these differences using genome-scale metabolic models (GEMs) to analyze gene expression and metabolic pathways in male and female DCM patients.

#### **Materials and Methods**
- **Data Collection:** RNA sequencing data from 366 heart tissue biopsies (166 DCM patients, 200 controls) from the MAGNet consortium was used.
- **Data Pre-processing:** Log2-transformed Counts Per Million (CPM) values were normalized using the Trimmed Means of Means (TMM) method.
- **Differential Expression Analysis:** Genes with different expression levels between DCM patients and controls were identified using linear and empirical Bayes statistical modeling.
- **Gene Set Enrichment Analysis (GSEA):** Enriched metabolic pathways were identified using the KEGG and WikiPathways databases.
- **Context-Specific GEMs:** The Gene Inactivity Moderated by Metabolism and Expression (GIMME) algorithm was used to create GEMs for male and female DCM and control groups.
- **Flux Variability Analysis (FVA):** FVA was performed to identify sex-related differences in six key metabolic subsystems: citric acid cycle, pyruvate metabolism, glutamate metabolism, FAO, glycolysis/gluconeogenesis, and oxidative phosphorylation.
- **Quality Checks:** Sanity checks ensured model functionality, and differences were visualized using the Virtual Metabolic Human website.

#### **Results**
- **Differential Expression:** 8429 differentially expressed genes (DEGs) were identified in females and 6928 in males. Many DEGs were common between sexes, but some were unique.
- **Pathway Enrichment:** KEGG and WikiPathways analysis revealed that enriched pathways related to immune response, energetics, metabolism, and signal transduction were prevalent in both sexes. Specific energy metabolism pathways, including FAO and glycolysis, were further investigated.
- **Metabolic Models:** Initial inspections showed more active FAO, glutamate metabolism, and glycolysis pathways in females. FVA confirmed that certain reactions carried flux only in female DCM models, suggesting a metabolic 'feminization' in male DCM hearts.
- **Limitations:** The study acknowledged a lack of in vivo validation studies, highlighting the need for further research to confirm these findings.

These findings indicate significant sex-related differences in cardiac energy metabolism in DCM patients, with potential implications for personalized treatment strategies.

