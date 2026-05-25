# Gabriele Pecchi

**Biomedical Engineer · Applied AI · Wearable Sensing · Reproducible Research**

---

Biomedical Engineering graduate working at the intersection of machine learning and clinical movement data. My focus is on building honest, reproducible benchmarks for wearable IMU time-series — particularly in neurological conditions — with rigorous evaluation methodology and transparent reporting of results, including negative ones. I also have hands-on experience in AI data annotation, model output evaluation, dataset validation, and quality control workflows.

---

## Main Focus Areas

- Wearable IMU time-series analysis (gait, tremor, movement disorders)
- Subject-independent and LOSO evaluation design for clinical ML
- Classical ML vs. deep learning comparison under realistic constraints
- Leakage-free preprocessing pipelines and reproducible experiment protocols
- AI output evaluation, annotation quality, and dataset validation

---

## Featured Projects

### [`pads-imu-parkinson-benchmark`](https://github.com/gabrielepecchi/pads-imu-parkinson-benchmark)

Subject-independent benchmark for Parkinson's Disease vs. Healthy Control classification from wrist-worn IMU data.

- Strict leakage-free evaluation: normalization fitted on training folds only, never on the full dataset
- Systematic comparison of classical ML models against a 1D-CNN baseline
- Honest reporting of modest classification results — no overclaiming
- Reproducibility-focused pipeline with documented methodology

---

### [`fog-prediction`](https://github.com/gabrielepecchi/fog-prediction)

Failure-analysis benchmark for pre-Freezing of Gait (FoG) prediction from wearable IMU data.

- Leave-One-Subject-Out (LOSO) cross-validation to evaluate held-out-subject generalization
- Systematic treatment of severe class imbalance across methods
- Negative results documented and analyzed, not discarded
- Threshold sensitivity analysis and feature explainability included
- Explicit discussion of clinical limitations — no unwarranted clinical claims

---

## Technical Skills

**Languages & Libraries**  
Python · NumPy · Pandas · Scikit-learn · PyTorch · SciPy

**ML & Evaluation**  
Classical ML · 1D-CNN · LOSO cross-validation · Subject-independent evaluation · Class weighting · Focal loss · Threshold analysis · Model explainability

**Data & Pipelines**  
IMU signal processing · Feature engineering · Leakage-aware preprocessing · Dataset validation · Annotation QC

**Tooling**  
Git · Jupyter · SQL basics · REST API basics

---

## Current Direction

Expanding beyond standalone benchmarks toward end-to-end biomedical AI tooling — including retrieval systems for clinical and research data, structured evaluation frameworks, REST API development, and database integration. The goal is to build tools that are not only methodologically sound but deployable and maintainable in practice.

---

## Contact

- GitHub: [github.com/gabrielepecchi](https://github.com/gabrielepecchi)
