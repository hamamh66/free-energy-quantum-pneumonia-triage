# Free-Energy–Driven Quantum-Enhanced Pneumonia Triage

This repository accompanies the paper:

**"Free-Energy–Driven Quantum-Enhanced Pneumonia Triage from Chest X-Ray Images"**

## Overview

This work introduces a decision-centric framework for pneumonia triage from chest X-ray images. The framework combines compact latent representation learning, a hybrid quantum-enhanced transformation, Monte Carlo dropout, and free-energy–based triage to support reliable prediction and clinically meaningful deferral of uncertain cases.

## Repository Structure

- `notebooks/` — reproducible prototype and final notebooks
- `src/` — modular source code for models, training, evaluation, and triage
- `outputs/` — figures, tables, and logs
- `data/` — dataset instructions only

## Installation

```bash
pip install -r requirements.txt
```

## Dataset

The experiments use **PneumoniaMNIST** from **MedMNIST**. Dataset download is handled automatically in the notebook.

## Reproducibility

The final notebook reproduces:
- model training
- uncertainty estimation
- entropy vs free-energy triage
- figures and tables used in the manuscript

## Citation

If you use this repository, please cite the associated paper.
