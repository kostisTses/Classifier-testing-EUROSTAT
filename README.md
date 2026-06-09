# Satellite image classification on the EUROSAT dataset

Testing different classification models using different techniques (Normal CNN, Transfer learning , Self-supervised, LoRA) on the **EuroSAT** satellite image dataset, implemented in a single Jupyter notebook.

Project was done for the deep-learning class (ΕΠ22στ) in the University of Athens , DIT

## Repository contents

- `src.ipynb` — main notebook containing the full workflow. The repository currently consists of this notebook only. :contentReference[oaicite:1]{index=1}

## What the notebook includes

- Library setup with `PyTorch`, `torchvision`, `NumPy`, `PIL`, and `matplotlib`
- Reproducibility setup with fixed random seeds
- GPU/CPU device selection
- EuroSAT dataset loading

## Requirements

Typical Python dependencies used in the notebook:

```bash
pip install torch torchvision numpy matplotlib pillow scikit-learn pandas

