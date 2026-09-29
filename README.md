# Climate Disclosure Quality Assessment

A framework-guided transformer-based NLP approach for assessing corporate climate disclosure quality and sustainability reporting.

## Publication Status

**Accepted for presentation at TEMSMET 2026.**

Presentation scheduled for **28 October 2026**.

## Overview

This project develops a transformer-based NLP pipeline for identifying climate-relevant disclosures and measuring their semantic alignment with international climate reporting frameworks.

## Methodology

- Sustainability report acquisition and text extraction
- Text preprocessing and chunking
- Climate relevance identification using ClimateBERT
- Framework-guided disclosure matrix construction
- Sentence Transformer embeddings
- Cosine similarity-based semantic alignment
- Climate Disclosure Quality Index (CDQI)
- Statistical evaluation

## Dataset

- **1,422** corporate sustainability reports
- **146,470** climate-related disclosure chunks
- **500** companies
- **2020–2025**

## Models

- ClimateBERT
- all-mpnet-base-v2 Sentence Transformer

## Evaluation

- Pearson correlation
- Cronbach's alpha
- Linear regression
- One-way ANOVA

## Key Results

- Cronbach's α = **0.847**
- R² = **0.789**
- p = **0.018**

## Technologies

- Python
- PyTorch
- ClimateBERT
- Sentence Transformers
- Scikit-learn
- Pandas
- NumPy
