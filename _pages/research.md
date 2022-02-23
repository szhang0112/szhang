---
title: "Sai Zhang - Research"
layout: textlay
excerpt: "Research"
sitemap: false
permalink: /research/
---

### Research

We are devoted to leveraging machine learning and big biomedical data to decode complex human diseases. In particular, we develop machine learning algorithms which integrate large-scale genetic data (genotype and whole exome/genome sequencing) with heterogeneous multiomic (transcriptomics, epigenomics, single-cell multiomics, etc.) and clinical (electronic health records, imaging, etc.) data to elucidate disease mechanisms and to advance disease-associated phenotype prediction. We are making efforts towards a modern paradigm of biomedical research, where a structured model is learned from the data to inform experiment-verifiable hypothesis as well as to facilitate personalized prediction. We have been working closely with experimental biologists and clinicians to bring our model predictions down to earth.

The topics we are currently working on include but not limited to:

#### 1. Single-cell multiomics

The emerging single-cell sequencing technologies provide a great opportunity to study gene regulation at a much higher resolution. Based on our previous work on deep learning modeling of high-throughput sequencing data, we are developing novel deep learning frameworks to exploit massive single-cell multiome data (e.g., single-cell ATAC and gene expression) for: (1) uncovering underlying determinants which drive cellular heterogeneity and variability in gene regulatory elements, and (2) interrogating cell-type-specific effects of genetic variation on noncoding genome function. This lays the foundation for our downstream genome analysis in the context of diseases or other phenotypes.

<ul>
  <li> Zhang et al. Analysis of ribosome stalling and translation elongation dynamics by deep learning. <a href="https://doi.org/10.1016/j.cels.2017.08.004"><em>Cell Systems</em></a>, 5(3):212-220, 2017 </li>
  <li> Zhang et al. Common and rare variant analyses combined with single-cell multiomics reveal cell-type-specific molecular mechanisms of COVID-19 severity. <a href="https://pubmed.ncbi.nlm.nih.gov/34189540/"><em>medRxiv</em></a>, 2021 </li>
</ul>

#### 2. Disease gene discovery

Summary statistics derived from genetic studies, including genome-wide association study (GWAS) and rare-variant association test, are more accessible than individual-level data. However, the power of discovering novel biological insights from those summary data remains limited. We are designing machine learning algorithms based on Bayesian networks to model the genetic architecture of complex diseases from summary data. By integrating various functional genomic annotations (e.g., bulk/single-cell epigenomic profiling), our models can increase the power of pinpointing disease risk genes and achieve better interpretations of genome function and cell-type specificity in disease pathogenesis. 

<ul>
  <li> Zhang et al. Genome-wide identification of the genetic basis of amyotrophic lateral sclerosis. <a href="https://doi.org/10.1016/j.neuron.2021.12.019"><em>Neuron</em></a>, 110:1-17, 2022 </li>
  <li> Zhang et al. Multiomic analysis reveals cell-type-specific molecular determinants of COVID-19 severity. <em>Under submission</em> </li>
</ul>

#### 3. Disease-associated phenotype prediction

Multiple large-scale biobanks (e.g., UK Biobank, Genomics England, and Million Veteran Program) have sequenced exomes or genomes and performed deep phenotyping for millions of individuals. These resources enable a systematic investigation of genotype-phenotype mapping for thousands of complex diseases. However, traditional approaches such as polygenic risk scores assume a linear structure and fail to capture the complexity/nonlinearity of the biological system. We are developing semi-structured machine learning models shaped by biological domain knowledge based on probabilistic graphical models and deep learning to predict disease phenotypes from millions of genetic variants in a personal genome. As a counterpart of statistical analysis, new biological discovery can be derived from the trained model via model interpretation.

<ul>
  <li> Li*, Pan*, Zhang* et al. Decoding the genomics of abdominal aortic aneurysm. <a href="https://doi.org/10.1016/j.cell.2018.07.021"><em>Cell</em></a>, 174(6):1361-1372, 2018 </li>
  <li> Zhang et al. Common and rare variant analyses combined with single-cell multiomics reveal cell-type-specific molecular mechanisms of COVID-19 severity. <a href="https://pubmed.ncbi.nlm.nih.gov/34189540/"><em>medRxiv</em></a>, 2021 </li>
</ul>

#### 4. Multimodal integration of genomic and clinical data

Deep phenotyping of individuals such as electronic health records and imaging enables better disease subtyping, increased power of biological discovery, and augmented clinical prediction. We are working on deep learning methods to learn representations for various clinical data using cutting-edge techniques developed in computer vision and natural language processing. Clinical representations are fused with genomic modeling to reveal the molecular basis of complex phenotypes and further to boost clinical prediction, paving the way towards personalized medicine.

<ul>
  <li> Li*, Pan*, Zhang* et al. Decoding the genomics of abdominal aortic aneurysm. <a href="https://doi.org/10.1016/j.cell.2018.07.021"><em>Cell</em></a>, 174(6):1361-1372, 2018 </li>
  <li> Li, Li, Zhang et al. Gene-environment interaction in the era of precision medicine. <a href="https://doi.org/10.1016/j.cell.2019.03.004"><em>Cell</em></a>, 177(1):38-44, 2019 </li>
</ul>
