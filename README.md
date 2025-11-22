# LDD Prompt Injection Figures (Supplementary Material)

This repository provides the result figures accompanying the paper:

**“Semantics as a Shield: Label Disguise Defense (LDD) against Prompt Injection in LLM Sentiment Classification.”**

These visualizations serve as supplementary material for the paper and illustrate the empirical performance of the evaluated models under various prompting and attack conditions.


## Overview

The repository contains **80 PNG figures**, each corresponding to a specific model–alias pair combination. The figures summarize the models’ behavior in controlled experimental settings designed to assess robustness against prompt injection.


## Figure Contents

Each figure presents **shot-wise accuracy curves** (evaluated at 2, 4, 6, and 8 shots) under the following conditions:

### 1. Clean Few-Shot Prompting
- Baseline performance of each model when no adversarial modification is present.

### 2. Under-Attack Performance
- Accuracy under class-directive injection attacks, where adversarial content attempts to manipulate model behavior.

### 3. LDD-Protected Performance
- Performance when applying **Label Disguise Defense (LDD)** using selected alias label pairs, demonstrating the defense’s ability to preserve intended task semantics.


## Models and Alias Label Pairs

Figures are organized by:

- **Model family** (e.g., GPT-4o, Gemma-3, LLaMA-3.2, Mistral)
- **Alias label pairs** used for LDD, including both aligned and unaligned semantic mappings

Each combination yields a separate figure for comprehensive comparison.


## Reproducibility Notes

The figures in this repository directly correspond to the experiments described in the paper.  
All model prompts, attack instructions, alias mappings, and evaluation protocol details are documented in the methodology section of the manuscript.


## Citation

If you use these figures or the results they summarize, please cite the associated paper:

> **Li, Y.** *Semantics as a Shield: Label Disguise Defense (LDD) against Prompt Injection in LLM Sentiment Classification.*, 2025.
