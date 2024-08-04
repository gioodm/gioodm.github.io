---
title: Hemoglobin Complex Analysis
date: 2020-02-14
external_link: 
url_pdf: uploads/DelMissier_PIBN
url_code: https://github.com/gioodm/Hemoglobin-complex-analysis
tags:
  - Structural biology
  - Hemoglobin complex
  - Network analysis

image:
  caption: 'Figure created with UCSF Chimera.'
  focal_point: ""
  preview_only: false
---

Computational analysis of structural properties of the hemoglobin complex.  

### Summary

#### **Background**
   The report provides a comprehensive computational analysis of the hemoglobin complex, focusing on its structural properties and interactions within the human proteome. The primary objectives are to identify key components that stabilise the hemoglobin tetramer, understand the interactions between protein monomers and heme groups, and explore the connectivity of hemoglobin subunits in various biological pathways.

#### **Materials and Methods**
   1. **Data Collection**:
      - Structural data for hemoglobin were obtained from the Protein Data Bank (PDB), specifically using the hemoglobin PDB structure (ID: 1GZX).
      - DSSP (Define Secondary Structure of Proteins) files were generated for the full hemoglobin, all possible trimers, and each monomer.

   2. **PDB Parsing**:
      - Python scripts were used to parse the PDB file, identifying interactions between residues and their contact with heme and oxygen atoms.

   3. **DSSP Analysis**:
      - Accessible surface areas (ASA) were computed to determine the interaction surfaces between monomers.

   4. **Protein-Protein Interaction Network**:
      - Network metrics such as betweenness centrality, node degree, and clustering coefficient were computed to analyse the connectivity of hemoglobin subunits within the human proteome.

#### **Results**
   1. **Structural Analysis of Hemoglobin**:
      - Hemoglobin is composed of two α and two β polypeptide chains, each associated with a heme group.
      - The heme group is situated inside a hydrophobic pocket between the E and F helices of each chain.

   2. **Heme-Monomer Interactions**:
      - Residues within each chain interacting with heme and oxygen atoms were identified, showing symmetry between different subunits.
      - Histidines (His58, His87) play a crucial role in stabilising the heme group.

   3. **Monomer-Monomer Interactions**:
      - Significant non-covalent interactions were found between monomers, especially between α and β subunits (chains A-B and C-D).
      - Extensive interaction surface areas were quantified between these subunits, indicating strong inter-subunit contacts.

   4. **Surface of Interaction**:
      - ASA computations confirmed large interaction surfaces between α and β subunits, suggesting strong inter-subunit contacts.
      - Minimal interaction was observed between β subunits, indicating lesser direct contact.

   5. **Protein-Protein Interaction Network**:
      - The network analysis highlighted the connectivity of hemoglobin subunits within the human proteome.
      - Metrics such as betweenness centrality, node degree, and clustering coefficient provided insights into the role of hemoglobin subunits in various biological pathways and their interactions with other proteins.

   These findings enhance the understanding of the structural properties and interactions that stabilise the hemoglobin complex and elucidate its role within the human proteome. The detailed analysis of monomer interactions and the protein-protein interaction network offers valuable insights into the functionality and biological significance of hemoglobin.
