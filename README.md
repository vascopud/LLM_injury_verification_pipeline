# LLM_injury_verification_pipeline
Analysis pipeline for sports injury verification using Mistral Large LLM.

This repository contains the code used in the article:

**“Scalable Retrieval and LLM-powered Curation of Sports Injury Data:
 An AI and Web-Based Approach for Evidence Synthesis in Athletic Performance.”**

Contents:
- `01_mistral_injury_verifier.ipynb` — main pipeline (parsing + LLM inference)
- `02_evaluation_of_LLM_performance.ipynb` — evaluation of accuracy, recall, specificity, etc.
- `requirements.txt` — Python dependencies
- `.env.example` — template for API key configuration
- `LICENSE`

## Sample Input File

For demonstration purposes, this repository includes a small file,
`sample_extracted_text.txt`, containing two random entries from the full
dataset. This sample illustrates the exact formatting expected by the parsing
functions used in the pipeline notebooks.