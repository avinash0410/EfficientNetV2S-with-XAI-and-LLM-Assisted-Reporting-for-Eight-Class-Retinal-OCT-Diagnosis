# EfficientNetV2S with XAI and LLM-Assisted Reporting for Eight-Class Retinal OCT Diagnosis

> **Paper 48 — Accepted for oral presentation at AICS 2026.**

## About

This repository contains the code and supporting materials for our AICS 2026 paper on automated eight-class retinal OCT (Optical Coherence Tomography) diagnosis. We fine-tune **EfficientNetV2S** to classify retinal OCT scans into eight diagnostic categories, apply **explainable AI (XAI)** techniques to visualize what the model is looking at, and add an **LLM-assisted reporting** step that drafts human-readable diagnostic summaries from the model's predictions.

## Repository structure

- `src/` — training, evaluation, and inference code
- `docs/` — project proposal, literature review, and documentation
- `build/` — build outputs
- `requirements.txt` — Python dependencies

## Getting started

1. Clone the repository.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Work through the notebooks and scripts in `src/` to reproduce training and evaluation.

## Citation

If you use this work, please cite:

Avinash Vadlamudi, "EfficientNetV2S with XAI and LLM-Assisted Reporting for Eight-Class Retinal OCT Diagnosis" (Paper 48), AICS 2026.
