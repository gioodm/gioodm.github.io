---
# Display name
title: ''

# Name pronunciation (optional)
name_pronunciation: ''

# Full name (for SEO)
first_name: ''
last_name: ''

# Status emoji
status:
  icon: ''

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: ''

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: 
    url: 

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:delmissiergiorgia@gmail.com'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/gioodm
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/giorgia-del-missier
  - icon: academicons/orcid
    url: https://orcid.org/0009-0005-6291-9877
  - icon: academicons/researchgate
    url: https://www.researchgate.net/profile/Giorgia-Del-Missier

interests:

education:
#  - area: PhD Artificial Intelligence
#    institution: Stanford University
#    date_start: 2016-01-01
#    date_end: 2020-12-31
#    summary: |
#      Thesis on _Why LLMs are awesome_. Supervised by [Prof Joe Smith](https://example.com). Presented papers at 5 IEEE conferences with the contributions being published in 2 Springer journals.
#    button:
#      text: 'Read Thesis'
#      url: 'https://example.com'
  - area: MSc Systems Biology
    institution: Maastricht University
    date_start: 2021-09-01
    date_end: 2023-07-14
    summary: |
      GPA: 8.5/10, cum laude

      Thesis: 
      WASP: A new Pipeline for Functional Annotation of Proteins using AlphaFold Structural Models

      Courses included:
      - Systems Biology and Modelling Biosystems
      - Machine Learning and Multivariate Statistics
      - Dynamical Systems, Non-Linear Dynamics and Dynamic Game Theory
  - area: BSc Genomics
    institution: Alma Mater Studiorum - University of Bologna
    date_start: 2017-10-01
    date_end: 2021-03-15
    summary: |
      GPA: 110/110, cum laude

      Thesis: 
      Phenotype-driven Variant Prioritisation Tools: Analysis of Whole Exome Sequencing in Patients with Hereditary Optic Neuropathy
      
      Courses included:
      - Bioinformatics and Omics Technologies
      - Programming, Statistics and Data Science
      - Molecular Biology and Genetics
work:
  - position: Computational Biologist
    company_name: Imperial College London - Ledesma-Amaro group
    company_url: https://www.rlalab.org/
    company_logo: ''
    date_start: 2022-11-01
    date_end: ''
    summary: |2-
      Activities include:
      - Design, development and implementation of WASP, a Python-based command-line pipeline for structure-based protein annotation
      - Network analysis, statistical testing, and enrichment for protein function inference
      - Use of REST APIs for web scraping
      - Design and development of web applications with Python DASH
      - Genome-scale Metabolic models curation and phylogenetic cross-organism comparison
      - Communication of findings through regular presentations and reports
      - Participation in the selection, evaluation and interview process of new candidates for collaboration
      - Supervising and mentoring of students
  - position: Lab Technician
    company_name: Maastricht Center for Systems Biology
    company_url: ''
    company_logo: ''
    date_start: 2021-06-01
    date_end: 2021-09-30
    summary: |
      Lab activities include:
      - PCR and quantitative PCR assays
      - Molecular cloning, Gibson assembly and esiRNAs construction
      - Lab resources management
      - Preparation of weekly reports on experimental procedures
  - position: Bioinformatician
    company_name: IRCSS Institute of Neurological Sciences
    company_url: ''
    company_logo: ''
    date_start: 2020-11-01
    date_end: 2021-04-30
    summary: |
      Activities include:
      - Whole-Exome Sequencing data analysis for variant analysis
      - Evaluation of phenotype-driven tools for variant prioritisation
      - Python, R and Unix coding to streamline Next Generation Sequencing data analysis
      - Preparation of regular reports and presentations to communicate findings

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Programming Languages
    items:
      - name: Python
        icon: devicon/python
      - name: R
        icon: devicon/rstudio
      - name: Unix
        icon: devicon/linux
      - name: MATLAB
        icon: devicon/matlab
  - name: Developer software
    items:
      - name: Hiking
        icon: person-simple-walk
      - name: Cats
        icon: cat
      - name: Photography
        icon: camera
  - name: Developer software
    items:
      - name: Hiking
        icon: person-simple-walk
      - name: Cats
        icon: cat
      - name: Photography
        icon: camera
  - name: Developer software
    items:
      - name: Hiking
        icon: person-simple-walk
      - name: Cats
        icon: cat
      - name: Photography
        icon: camera


# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: 'Fundamentals of Accelerated Computing with CUDA C/C++'
    url: https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+C-AC-01+V1
    certificate_url: https://learn.nvidia.com/certificates?id=MSkAhwERQMG6UU4Ajpb6iw
    date: '2024-07-05'
    awarder: NVIDIA
    icon: brands/nvidia
    summary: |
      In this workshop, I learned the fundamental tools and techniques for accelerating C/C++ applications on massively parallel GPUs using CUDA. I gained skills in writing and parallelizing code, optimizing memory migration between the CPU and GPU, and applying these techniques to accelerate a CPU-only particle simulator for significant performance gains. Additional resources were provided for further learning and development of GPU-accelerated applications.
      Learning Objectives:
       - Write code for execution on a GPU accelerator.
       - Express data and instruction-level parallelism in C/C++ using CUDA.
       - Optimize memory migration with CUDA-managed memory and asynchronous prefetching.
       - Use command-line and visual profilers to optimize performance.
       - Utilize concurrent streams for instruction-level parallelism.
       - Develop and refactor GPU-accelerated CUDA C/C++ applications using a profile-driven approach.
  - title: 'Deep Learning with PyTorch : Build an AutoEncoder'
    url: https://www.coursera.org/projects/deep-learning-with-pytorch-build-an-autoencoder
    certificate_url: https://www.coursera.org/account/accomplishments/records/CH4Q4XWW6Q9V
    date: '2024-05-01'
    awarder: Coursera
    icon: coursera
    summary: |
      Learned to implement an autoencoder using PyTorch. An autoencoder is a type of neural network that learns to reproduce its input at the output layer. It consists of two main parts: the encoder, that compresses the input into a compact representation, and the decoder, which reconstructs the input from this compressed representation. In this project, I implemented an autoencoder to denoise handwritten digits.
  - title: 'Neo4j Certified Professional'
    url: https://neo4j.com/
    certificate_url: https://graphacademy.neo4j.com/c/da9e5162-3a72-4c13-a9bc-ea0515986d11/
    date: '2023-11-21'
    awarder: Neo4j
    icon: neo4j
    summary: |
     Neo4j is a graph database management system that uses graph structures—comprising nodes, edges, and properties—to represent and store data. It is designed for handling large-scale connected data and is renowned for its high performance and scalability.
     Learning objectives:
      - Understanding graph theory, the fundamentals of graph databases, and their differences from traditional relational databases.
      - Neo4j's architecture and optimised query processing with the Cypher language.
      - Best practices for designing and implementing graph data models to represent complex relationships and ensure data integrity.
---

## About Me

bla bla bla
