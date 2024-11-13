# Multi-Trial Analysis for Quantitative Genetics
This repository contains the analysis and code developed in PS 756 - Quantitative Genetics course at South Dakota State University by Guilherme Olivera, Mandeep Singh & Subash Thapa. The project aims to conduct a Multi-Trial Analysis exploring Genotype x Environment Interaction (G x E), including various analysis methods and genomic selection approaches. The analysis uses two different open datasets, as outlined below.

# Project Overview
The main objective of this project is to conduct a Multi Trial Analysis, covering:
1. GxE Analysis (+ GGE Analysis)
2. AMMI Analysis
3. GGI Analysis
4. FW Analysis
5. Genomic Selection Approach with a focus on GxE interaction.
The project consists of two main parts, each utilizing a different dataset for analysis.
# Datasets Used
# Dataset 1: Dias et al. (2018) - Drought Tolerance Traits
Source: The open dataset made available by Dias et al. (2018) contains phenotypic data of five drought tolerance traits measured in 308 hybrids across eight environments contrasting for water availability.
Subset: For practical purposes, a subgroup of 202 hybrids is used.
Traits Analyzed:
-Grain Yield (GY)
-Ears per Plot (EPP)
-Female Flowering Time (FFT)
-Male Flowering Time (MFT)
-Anthesis-Silking Interval (ASI)
# Dataset 2: Crossa et al. (2013) & Montesinos-Lopez et al. (2016, 2017) - Maize Lines
Source: Crossa et al. (2013) and Montesinos-Lopez et al. (2016, 2017) contain data on 309 double-haploid maize lines tested in 3 environments with three replications for each line.
Traits Analyzed:
-Grain Yield (Yield)
-Anthesis-Silking Interval (ASI)
-Plant Height (PH)

#Methods Used
The following methods were used for the analysis:

-GxE Analysis: Exploring the interaction between Genotype and Environment to understand how different genotypes perform across multiple environments.

-GGE (Genotype + Genotype x Environment): A graphical approach to visualize the interaction between genotypes and environments.

-AMMI (Additive Main Effects and Multiplicative Interaction): A statistical model for analyzing GxE interactions.

-GGI (Genotypic-Environment Interaction) Analysis: Analyzing the environmental stability of genotypes.

-FW (Factorial Weighted) Analysis: Exploring weighted factors to analyze the GxE interaction.

-Genomic Selection: Approaches that explore the influence of genetic factors on trait performance across environments, considering GxE.
# Software and Packages Used
R Packages: The analysis was conducted using the metan (Olivoto and Lucio, 2020) and statgenGxE reference manuals for conducting GxE and other related analyses.
BMTME R Package: We also used the BMTME R package, developed by Montesinos-Lopez et al. (2019), with slight modifications for more comprehensive interpretations and additional analyses.
