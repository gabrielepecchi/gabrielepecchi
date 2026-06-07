# Gabriele Pecchi

**AI Evaluation · Benchmark Design · Structured Reasoning · Retrieval Systems**

---

## About Me

I focus on AI evaluation and benchmark design — building structured frameworks that produce honest, reproducible results. My work emphasizes evaluation methodology: leakage-free design, criterion-level reasoning, error analysis, and transparent reporting of limitations and negative results. I have hands-on experience in LLM output evaluation, annotation QC, and dataset validation workflows.

My background is in Biomedical Engineering, which is where my projects are grounded — but the skills are methodological, not domain-specific.

---

## What I Work On

- Designing leakage-free ML evaluation pipelines with reproducible methodology
- Structured LLM output evaluation: criterion-level reasoning, error analysis, failure mode documentation
- Annotation QC and dataset validation workflows
- Hybrid information retrieval with graded evaluation (BM25, semantic embeddings, hybrid ranking)
- Subject-independent cross-validation for time-series classification

---

## Featured Projects

### [`clinical-trial-eligibility-benchmark`](https://github.com/gabrielepecchi/clinical-trial-eligibility-benchmark)

Structured benchmark for LLM-assisted eligibility reasoning across 150 synthetic patient–trial pairs.

- Criterion-level reasoning with robustness checks, error analysis, and an HTML benchmark report
- LLM-reviewed draft labels; results reported with known limitations (Accuracy 0.687 · Macro F1 0.686)
- Fully synthetic patients; not clinical decision support

---

### [`pads-imu-parkinson-benchmark`](https://github.com/gabrielepecchi/pads-imu-parkinson-benchmark)

Leakage-aware ML benchmark for wearable IMU classification, built with strict evaluation hygiene.

- Normalization fitted on training folds only; subject-independent 5-fold cross-validation
- Results with confidence intervals: balanced accuracy 0.6441 ± 0.0156, AUROC 0.7029 ± 0.0261
- Designed for realistic evaluation, not inflated scores

---

### [`biomedical-evidence-retrieval`](https://github.com/gabrielepecchi/biomedical-evidence-retrieval)

FastAPI + Streamlit search system with a hybrid retrieval pipeline and full graded evaluation.

- BM25, semantic embeddings, and hybrid ranking with optional filters
- Evaluated with Precision@5, Recall@10, MRR, and nDCG@10; best hybrid result: MRR 1.0000 · nDCG@10 0.9453

---

## Skills

**Evaluation & Benchmarking**
Leakage-aware evaluation design · Structured output evaluation · Error analysis · Annotation QC · Dataset validation · Limitation documentation · Subject-independent cross-validation

**Retrieval & ML**
BM25 · Semantic embeddings · Hybrid ranking · Classical ML · 1D-CNN · Feature engineering · Threshold analysis

**Languages & Libraries**
Python · NumPy · Pandas · Scikit-learn · PyTorch · SciPy · FastAPI · Streamlit

**Tooling**
Git · Jupyter · SQL · REST APIs

---

## Contact

- GitHub: [github.com/gabrielepecchi](https://github.com/gabrielepecchi)
