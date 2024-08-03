---
title: ML for sound classification
date: 2022-06-03
external_link: 
url_code: https://github.com/gioodm/ML-for-sounds-classification
tags:
  - Machine Learning
  - Sound classification
  - fMRI data
  - MATLAB modeling
---

Evaluating various ML methods in classifying sound categories based on fMRI data from brainstem regions.

### Summary

**Introduction:**
- The auditory system processes sound through several neuronal structures, with increasing complexity as the signal moves from the cochlea to the auditory cortex.
- Machine learning techniques have been applied to fMRI data analysis to detect brain activation patterns linked to cognitive states, but less is known about sound processing in subcortical regions like the cochlear nucleus (CN), superior olivary complex (SOC), inferior colliculus (IC), and medial geniculate body (MGB).

**Materials and Methods:**
- **Dataset:** fMRI responses to seven sound categories (human speech, voice, animal sounds, music, tools, nature sounds, monkey calls) across four brain regions in ten subjects.
- **Methods Evaluated:** Principal Component Analysis (PCA), Lasso regression, Linear Discriminant Analysis (LDA), Naive Bayes, Random Forest, and Support Vector Machine (SVM).
- **Approach:** Classifications were simplified into three groups (human, animal, inanimate) for comparison.

**Results:**
- **PCA:** No clear separation of sound categories in the PCA plots, indicating challenges in distinguishing sounds based on subcortical fMRI data.
- **Lasso Regression:** Limited feature retention with generally low accuracy, except for MGB where accuracy reached 62%. The classification was notably better for human versus inanimate sounds compared to human versus animal sounds.
- **Other Methods:** 
  - **LDA:** Best performance in CN.
  - **Naive Bayes:** Best performance with kernel density estimation in MGB.
  - **Random Forest and SVM:** Various performances across regions, with no single method consistently outperforming the others.

**Conclusions:**
- Classifying sounds in brainstem regions using machine learning is challenging, with no single method clearly superior.
- The dataset's complexity and the subcortical fMRI signal quality contribute to the difficulties.
- Better classification accuracy was observed for ecologically relevant sounds compared to inanimate objects, supporting the hypothesis that higher brain regions are optimized for processing behaviorally significant sounds. Further research with more subjects and refined methods is suggested.