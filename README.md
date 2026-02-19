# FT-AFM-CTR
Feature Tokenization Attentional Factorization Machine (FT-AFM) for click-through rate prediction. Code for IEEE Access manuscript.
# FT-AFM: Feature Tokenization Attentional Factorization Machine for CTR Prediction

This repository contains the official implementation of **FT-AFM**, a click-through rate (CTR) prediction model that combines Feature Tokenization with an Attentional Factorization Machine. This code accompanies the manuscript submitted to **IEEE Access**.

---

## Overview

FT-AFM integrates a Feature Tokenizer (inspired by FT-Transformer) with an Attentional Factorization Machine (AFM) to capture both deep contextual representations and explicit pairwise feature interactions for CTR prediction.

---

## Datasets

Experiments were conducted on three public datasets:

- [Avazu](https://www.kaggle.com/c/avazu-ctr-prediction)
- [Criteo](https://www.kaggle.com/c/criteo-display-ad-challenge)
- [Outbrain](https://www.kaggle.com/c/outbrain-click-prediction)

---

## Requirements
```bash
pip install -r requirements.txt
```

---

## Running the Code

Train FT-AFM on each dataset using the corresponding notebook:

- `criteo_pipeline.ipynb` — Criteo dataset
- `outbrain_pipeline.ipynb` — Outbrain dataset

Analyze attention weights:
- `extract_afm_weights.ipynb`

Compare baseline models:
- `comparison_models.ipynb`

---

## Results

Results and attention analysis outputs are available in the `results/` and `attention_analysis_*/` folders.

---

## Citation

Coming soon after publication.

---

## License

MIT License
