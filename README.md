# Paediatric Perioperative Risk Stratification Using Large Language Models

## Overview

This dissertation explores the use of Large Language Models (LLMs) to predict perioperative risk in paediatric patients from unstructured clinical notes.

## Key Findings

- **MedGemma-27B-text-it** (domain-specific medical model) consistently outperformed **Llama-3.1-8B-Instruct** (general-purpose model) on ASA-PS classification tasks
- Few-shot Chain-of-Thought (CoT) prompting achieved the best performance (42.6% accuracy)
- Domain-specific pretraining and structured reasoning significantly improved clinical prediction accuracy
- Both models struggled with heavily imbalanced datasets (rare adverse events)

## Tasks Evaluated

1. **ASA-PS Classification** - Predicting preoperative health status (categorical)
2. **AnyEmerg** - Detecting respiratory adverse events during emergence from anaesthesia (binary)
3. **AnyRF** - Identifying perioperative respiratory risk factors (binary)

## Technical Approach

- Prompt engineering strategies: zero-shot, few-shot, and Chain-of-Thought
- Dataset: Unstructured paediatric clinical notes from Perth Children's Hospital
- Computing: MERLIN HPC cluster (H100 GPUs)

## Full Document

See `dissertation.pdf` for the complete research findings and methodology.
