---
layout: post
title: Bioinformatics Practice Assignment1
date: 2024-09-16 15:04 +0800
tags: [Assignment]
toc:  true
---

**This is Assignment1.**

## Reviewing class content

### 4 steps of bioinformatics
- Question
- Information  
  1. Images
  2. Sequences: DNA-seq, RNA-seq, Epigenetics(DNAase, Methylation, Histone modifications), Interaction(Protein-DNA, Protein-RNA, DNA-RNA)
- Analysis  
  sequencing methods + bioinformatics tools  

   | Variation | Sequencing Methods | Bioinformatics Tools |
   |:---------:|:------------------:|:--------------------:|
   | Abundance | RNA-seq | DEGseq2, EdgeR, Cufflinks |
   | Splicing | RNA-seq | rMATs, TOPHAT/Cufflinks |
   | Editing | RNA-seq | GIREMI, REDItools, SPRINT |
   | APA (Alternative Poly-adenylation) | RNA-seq/PAT-seq | DaPars, APAtrap |
   | Translation | Ribo-seq | RiboWave, RiboTaper, ORFscore |
   | Degradation | Degradome-Seq (PARE-seq), cfRNA-seq | sPARTA, cfPeak |
   | Modification | m6A-seq, MeRIP-seq, miCLIP | m6AViewer, MeRIP-PF |
   | Structure | icSHAPE, SHAPE-map, DMS-seq | RNAstructure, RNAfold, RME |
   | RNA-protein interaction | HITS-CLIP, PAR-CLIP, iCLIP, eCLIP | Piranha, PARalyzer, CIMS, POSTAR/CLIPdb |

- Modeling  
  1. traditional machine learning(Random Forest, SVM, Hidden Markov model, etc.)
  2. deep learning
  3. hypothesis driven model -> data driven model

### Differences between algorithm and model
1. Definition:  
   - Algorithm: An algorithm is the process that runs on data to create a model.
   - Model: A model is the output of the algorithm that runs on data(A model can be seen as the outcome of applying an algorithm to a specific dataset).
2. Generality vs. Specificity:
   - Algorithm: It is usually general and not dependent on a particular dataset. 
   - Model: It is specific, containing parameters and knowledge learned from a particular dataset.
3. Variability:
   - Algorithm: Once defined, it is usually fixed and does not change with the data.
   - Model: It is variable and can change with each training or update as the model adjusts based on new data.
4. Updates and Maintenance:
   - Algorithm: Once developed, it usually does not require frequent updates unless it's for performance optimization or to adapt to new computational needs.
   - Model: May need regular updates and maintenance to adapt to new data or environmental changes.

## Study plan

### Basic courses & skills
- Further understanding of data structures and algorithms, especially the application of deep learning algorithms in bioinformatics.
- Learing biological knowledge based on the needs of the research topic.
- Reading more literature in the relevant fields and summarizing.

### Practice, communication and teaching
following the Feynman Technique, do more practices, communicate with others and teach others.


