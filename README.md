## Hi, I'm Raouf 👋

**Petroleum engineer building evaluated AI systems — agents, RAG, and offline OCR.**

I build applied AI systems and reproducible NLP evaluations. My background is in computer and petroleum engineering, and I work at PRC LIBYA.

Open to work and collaboration. Reach me on [Facebook](https://www.facebook.com/abdalraofelkabir2) or [Instagram](https://www.instagram.com/raouf.el6).

### Currently building

- **[section-team](https://github.com/afel6/section-team)** — a Claude Code plugin that delegates work to specialist agents and requires code review before handoff. On three unseen tasks, blind AI judges scored it **8.80 vs. 8.16** for plain Claude Code at about **2.2× the cost**. Both passed all hidden tests. [Held-out benchmark](https://github.com/afel6/section-team/blob/main/docs/benchmark-heldout-2026-11.md)
- **[Folio OCR](https://github.com/afel6/folio-ocr)** — an offline OCR CLI and local review app for English and Arabic documents. It flags uncertain lines and unread regions before exporting TXT, DOCX, or JSON. [Evaluation](https://github.com/afel6/folio-ocr#results)
- **[SovereignFin-3M](https://github.com/afel6/SovereignFin-3M)** — a local-first financial intelligence engine: agentic RAG over 10-K snippets, relational deep learning on a synthetic ERP database, and knowledge-graph retrieval, orchestrated with LangGraph.

### Measured NLP work

- **[TURAS](https://github.com/Rxd3/TURAS)** — I owned integration and evaluation for Turkish parliamentary speech recognition, building the WER/CER evaluator, timing harness, validators, and submission verifier. The team's full Whisper fine-tune reduced normalized word error rate from **24.51% to 10.37%** on 636 clips scored against edited minutes. [Benchmark report](https://github.com/Rxd3/TURAS/blob/main/results/final/M4_M5_FINAL_REPORT.md)
- **[NALTRA](https://github.com/Rxd3/NALTRA)** — I built classification and retrieval models and the evaluator for a bilingual research taxonomy benchmark. A calibrated linear SVM led the tested models at **0.558 English and 0.489 translated-Turkish micro-F1**. [Results](https://rxd3.github.io/NALTRA/results/)
- **[RECAP](https://github.com/Rxd3/RECAP)** — I built the evaluator and audited utterance-end shortcuts for punctuation and capitalization restoration. The improved CRF scored **49.92 vs. 35.12 macro-F1** for the HMM on the primary test.

### Engineering software

- **[pvt-correlations](https://github.com/afel6/pvt-correlations)** — textbook black-oil PVT correlations in pure Python: Standing, Vasquez-Beggs, Glaso, and Beggs-Robinson, with a PVT table builder.

### Tools

Python · PyTorch · TypeScript · FastAPI · React · PostgreSQL · Docker

### University work

- **[swe015-handwritten-digitizer](https://github.com/afel6/swe015-handwritten-digitizer)** — handwritten boxed-word digitizer: EMNIST CNN + n-gram + BERT MLM, INT8 quantized, with a FastAPI canvas app.
- **[coe305-ml-project](https://github.com/afel6/coe305-ml-project)** — machine learning practical project: cross-validation, feature selection, PCA, K-Means, and tree ensembles.
- **[submission-correctness](https://github.com/afel6/submission-correctness)** — a Claude skill to make sure the grader (human or AI agent) can install and run your project before the deadline.
