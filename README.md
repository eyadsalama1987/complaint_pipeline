# Multi-Label Customer Complaint Classification

**Improving Multi-Label Financial Customer Complaint Classification
Using Fine-Tuned BERT, Focal Loss, and Per-Label Threshold Optimization**

> Islamic University of Gaza — Department of Computer Engineering, 2026
> Submitted to IEEE Access

---

## Overview

This repository contains the full experiment code for multi-label
classification of financial customer complaints from the CFPB Consumer
Complaint Database using:

- Fine-Tuned BERT (bert-base-uncased)
- Focal Loss with per-label class weighting
- Per-label threshold optimization via validation grid search

**Best result:** F1 Macro = 0.380 | F1 Micro = 0.546 | F1 Weighted = 0.593
(+37.3% F1 Macro improvement over TF-IDF baseline)

---

## Files

| File | Description |
|------|-------------|
| `complaint_pipeline.ipynb` | Full pipeline: preprocessing, training, evaluation |

---

## Requirements


torch>=2.0
transformers>=4.35
scikit-learn>=1.3
numpy
pandas
---

---

## Authors

- Eyad Kamal Salama — esalama4@students.iugaza.edu.ps
- Dr. Aiman Ahmed Abusamra — aasamra@iugaza.edu.ps
- Dr. Ayman Fayez Maliha — amaliha@iugaza.edu.ps
