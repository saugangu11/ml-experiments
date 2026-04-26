# 🤖 ML Experiments

> Applied machine learning experiments — RAG pipelines, time-series forecasting, classification, and agentic workflows. Built to learn fast and share what works.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## About

A lab notebook for applied ML work. Each experiment is self-contained, reproducible, and documented with what I tried, what worked, and what didn't. The goal is applied insight, not benchmark chasing.

Areas of focus: **Retrieval-Augmented Generation (RAG)**, **LLM fine-tuning**, **time-series forecasting**, **classification pipelines**, and **agentic patterns**.

---

## Experiments

| # | Experiment | Category | Key finding | Notebook |
|---|-----------|----------|-------------|----------|
| 01 | *Coming soon* | RAG | — | — |
| 02 | *Coming soon* | Forecasting | — | — |
| 03 | *Coming soon* | Agents | — | — |

---

## Tech stack

- **Frameworks** — PyTorch, scikit-learn, HuggingFace Transformers
- **LLMs / agents** — Claude API, LangChain, LlamaIndex
- **Vector stores** — ChromaDB, FAISS
- **Experiment tracking** — MLflow / Weights & Biases
- **Data** — pandas, numpy, DuckDB

---

## Repository structure

```
ml-experiments/
├── 01-experiment-name/
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   ├── results/        # metrics, charts, model outputs
│   └── README.md       # hypothesis, method, findings
├── 02-experiment-name/
│   └── ...
├── shared/             # reusable utilities across experiments
└── README.md           # this file
```

---

## Running an experiment

```bash
git clone https://github.com/saugangu11/ml-experiments.git
cd ml-experiments/01-experiment-name

pip install -r requirements.txt
jupyter notebook notebooks/experiment.ipynb
```

Each experiment directory has its own `requirements.txt` and a brief `README.md` describing the hypothesis, method, and results.

---

## Contributing

Found something interesting? Open an issue or PR — happy to discuss approaches and results.

---

## License

MIT
