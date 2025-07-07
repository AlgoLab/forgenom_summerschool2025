---
layout: page
title: Lectures
description: List of Lectures
navorder: 5
---
### Andrea Guarracino

- Hackathon:<br>
<sub>The exponential growth of genomic data demands new compression solutions. This hackathon project will explore adapting the Assembled Genomes Compressor (AGC, https://github.com/refresh-bio/agc) to compress raw sequencing reads—a different application beyond its original design for assembled genomes—for potential integration with the Rust-based GBAM framework (https://github.com/NickRoz1/gbam). Students will benchmark AGC's compression ratios and speed on raw read datasets, prototype a proof-of-concept integration between the C++ AGC library and Rust GBAM, and gain hands-on experience with bioinformatics tool development and cross-language integration. The project accommodates diverse skill levels: beginners can focus on benchmarking and data analysis using command-line tools, while advanced students can tackle the C++/Rust interoperability challenge. Deliverables include performance benchmarks, a report on feasibility, and potentially a minimal working integration that students can continue developing post-hackathon on their own systems.</sub>

### Benedict Paten

- Lecture: Human Pangenome Alignments - working toward the second release of the human pangenome reference<br>
<sub>I will review recent progress from within the Human Pangenome Reference Consortium, specifically the development of a complete, integrated human pangenome alignment of hundreds of individual human haplotypes. I will show tools and applications for using this resource. I will describe some novel data structures that we view as missing pieces of the pangenomics informatics ecosystem.</sub>

### Erik Garrison

- Building Pangenome Graphs: From Variation Theory to Human Genome Complexity & Pangenome Applications: Evolutionary Insights and Scaling to Population Genomics<br>
<sub>Pangenomics has evolved from counting genes in bacterial populations to building comprehensive variation graphs that represent all types of variation across many genomes. I'll present methods for constructing these graphs through genome alignment, focusing on the PanGenome Graph Builder (PGGB) approach that creates unbiased representations where any genome can serve as reference. Using the Human Pangenome Reference Consortium data, we've uncovered hidden structural complexity including the evolution of amylase copy number variation linked to agricultural transitions and recombination between acrocentric chromosomes that explains Robertsonian translocations. However, building pangenomes for hundreds of genomes faces quadratic scaling challenges. I'll introduce implicit pangenome graphs (IMPG) that maintain alignment relationships without materializing the full graph structure, enabling efficient coordinate translation and subgraph extraction. These developments allow us to move from chromosome-level to truly genome-wide pangenome analysis while maintaining computational tractability for population-scale studies.</sub>

### Marcel Kucharík

- Lecture & Practical: Short tandem repeats genotyping (and their part in Pangenomes)<br>
<sub> In this lecture, we will familiarize ourselves with short tandem repeats (STRs) and their significance in diagnostics and personal identification. We will introduce several STR detection tools and describe the working principles of two of them, while diving deep into one in particular. In the practical portion of the lecture, participants will work in groups to download the required data and STR detection tools, install them, and utilize them to detect STRs for a few select loci. In the end, we will discuss the findings, any inconsistencies, and the performance of different tools.</sub>

### Mauricio Soto Gomez

- Lecture & Practical: An Introduction to Machine Learning Tools: Methods and Applications<br>
<sub>The course introduces essential machine learning (ML) techniques and tools for data analysis. In this series of lectures, we explore both theoretical foundations and practical applications of ML approaches for processing, analyzing, and interpreting complex data. During practical sessions, graphic programming tools will be used to implement ML models on several examples. During practical sessions, graphic programming tools will be used to implement ML models on several examples.</sub>

### Tobias Rausch

- Lecture: Introduction to cancer genomics and its caveats<br>
<sub>Cancer genomes contain a wide range of somatic variants – DNA differences between tumor cells and normal host cells. In addition, inherited germline variants may predispose to cancer. Researchers use DNA sequencing to discover somatic and germline variants, identify cancer driver mutations and infer clonal tumor architecture. In this lecture the trainer discusses the challenges of cancer genomics and the computational methods used to analyze cancer genomes.</sub>

- Lecture: Mutational processes and structural & copy-number variation analysis<br>
<sub>Cancer genomes contain a wide range of somatic structural and copy number variants (SVs and CNVs), and these are a common source of cancer driver mutations. Recent pan-cancer studies performed using short-read sequencing classified simple SVs into different higher-order classes, such as chromothripsis or chains and cycles of templated insertions, but due to the difficulty of assembling short-reads into coherent contigs, identifying such SV patterns is complicated and often requires visual interpretation of the results. In this lecture we will explain the principles of short-read SV calling and discuss complex rearrangements. We also present a comprehensive overview of the most recent advancements in the field of mutational signatures, focusing on the pan cancer analysis of thousands of cancer samples.</sub>

- Lecture: The benefits of interrogating (cancer) genomes using long reads<br>
<sub>Long-read sequencing of 1000 Genomes project samples yielded a 2- to 3-fold increase in detected germline structural variants (SVs) compared to short-read sequencing with improved sensitivity for smaller SVs (<1 kbp) and SVs in repetitive regions. In this lecture, the trainer discusses the benefits and challenges associated with long-read applications in population and cancer genomics and how long reads can help to interpret complex genomic rearrangements in a haplotype-specific manner that are inaccessible to short reads. We will also discuss benefits of long-read technologies for linking genetic with epigenetic information and the integration of SVs in pan-genome graphs.</sub>

### Tomáš Szemes

- TBA<br>

### Vincenza Colonna

- Integrating Genetic Ancestry, Environmental Exposure and Health Equity<br>
<sub>The BIG Initiative examines the relationship between genetics, environment, and health across a diverse Tennessee population. Analysis of over 13,000 genomes revealed remarkable diversity, with half having non-European or admixed ancestry. Using identity-by-descent analysis, we identified four main communities corresponding to continental ancestries and mapped these to neighborhood-level geographical data. Some subcommunities were overrepresented in areas with elevated environmental stressors, suggesting genetic relatedness serves as an indicator of shared environmental factors. The African-ancestry community exhibited higher rates of respiratory and dermatological conditions, while significant health differences were detected between subcommunities of the same ancestry group. This approach provides a framework for understanding health disparities that captures both ancestral population structure and environmental influences without relying on potentially biased reference populations.</sub>
