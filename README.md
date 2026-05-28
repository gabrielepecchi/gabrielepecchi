# Gabriele Pecchi

**Biomedical Engineer · Applied AI · Retrieval Systems · ML Evaluation**

---

Biomedical Engineering graduate working at the intersection of machine learning, clinical data retrieval, and wearable sensing. My focus is on building honest, reproducible benchmarks — particularly for Parkinson's Disease research — with rigorous evaluation methodology and transparent reporting, including negative results. I also have hands-on experience in AI data annotation, model output evaluation, dataset validation, and quality control workflows.

---

## Main Focus Areas

- Biomedical information retrieval (BM25, semantic embeddings, hybrid ranking)
- Leakage-free ML evaluation for wearable IMU time-series
- Clinical trial eligibility reasoning and LLM-assisted benchmarking
- Subject-independent and LOSO evaluation design for clinical ML
- AI output evaluation, annotation quality, and dataset validation

---

## Featured Projects

### [`biomedical-evidence-retrieval`](https://github.com/gabrielepecchi/biomedical-evidence-retrieval)

FastAPI + Streamlit biomedical search system over Parkinson's ClinicalTrials.gov records.

- Hybrid retrieval pipeline combining BM25, semantic embeddings, and hybrid ranking with optional filters
- Grounded template summaries and graded retrieval evaluation
- Best hybrid result: Precision@5 0.9913 · Recall@10 0.9976 · MRR 1.0000 · nDCG@10 0.9453
- SQLite backend; not clinical decision support

---

### [`pads-imu-parkinson-benchmark`](https://github.com/gabrielepecchi/pads-imu-parkinson-benchmark)

Leakage-aware ML benchmark for Parkinson's Disease vs. Healthy Control classification from wrist-worn PADS smartwatch IMU data.

- Strict leakage-free evaluation: normalization fitted on training folds only, never on the full dataset
- Subject-independent 5-fold cross-validation; models include Logistic Regression, Random Forest, and 1D-CNN v2
- Best balanced model: Logistic Regression — Balanced Accuracy 0.6441 ± 0.0156, AUROC 0.7029 ± 0.0261
- Focus is realistic evaluation, not inflated scores

---

### [`clinical-trial-eligibility-benchmark`](https://github.com/gabrielepecchi/clinical-trial-eligibility-benchmark)

Local benchmark for patient-to-trial eligibility reasoning using synthetic Parkinson's patients and public ClinicalTrials.gov trial criteria.

- LLM-reviewed draft labels over 150 evaluated patient–trial pairs (not clinical gold truth)
- Current results: Accuracy 0.440 · Macro F1 0.439
- Includes local pipeline, error analysis, and no real patient data
- Transparent about label quality and scope limitations

---

## Technical Skills

**Languages & Libraries**  
Python · NumPy · Pandas · Scikit-learn · PyTorch · SciPy · FastAPI · Streamlit

**ML & Retrieval**  
BM25 · Semantic embeddings · Hybrid ranking · Classical ML · 1D-CNN · LOSO cross-validation · Subject-independent evaluation · Class weighting · Threshold analysis · Model explainability

**Data & Pipelines**  
IMU signal processing · Feature engineering · Leakage-aware preprocessing · Dataset validation · Annotation QC · SQLite

**Tooling**  
Git · Jupyter · SQL basics · REST API basics

---

## Current Direction

Building end-to-end biomedical AI tooling — retrieval systems for clinical and research data, structured evaluation frameworks, REST API development, and LLM-assisted benchmarking pipelines. The goal is tools that are methodologically sound, deployable, and maintainable in practice.

---

## Contact

- GitHub: [github.com/gabrielepecchi](https://github.com/gabrielepecchi)
