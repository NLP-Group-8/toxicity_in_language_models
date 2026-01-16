# Characterizing Toxicity in Language Models

This repository contains our project on **measuring and characterizing toxicity in large language models (LLMs)**. We evaluate multiple base models under a consistent prompting and scoring pipeline, and store generations + aggregated results for analysis and reporting.

## Project goals
- Compare how different base LLMs behave on the same set of prompts
- Quantify toxicity-related tendencies (e.g., toxic completions, sensitive-topic brittleness)
- Support reproducible analysis via saved generations and exported CSVs

## Models evaluated
We focus on open-weight / openly accessible base models, including:
- **Mistral-7B (base)**
- **BLOOM-7B/7B1 (base)**
- **Gemma-7B (base)**

> Note: Model availability may depend on your Hugging Face access permissions.

## Repository structure
- `code/`  
  Notebooks and scripts for running inference, scoring, and analysis.
- `output/`  
  Generated artifacts (model outputs, intermediate files, plots, exported tables).

You may also see exported CSVs at the root (e.g., consolidated generations).
