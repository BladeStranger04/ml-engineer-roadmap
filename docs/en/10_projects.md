# 10. Projects and portfolio

> Russian version: [10_projects.md](../ru/10_projects.md)

> Two or three strong GitHub projects are better than ten tutorial clones.

---

## What makes a project strong

- Real problem, not MNIST classification.
- Full cycle: data, model, deployment, monitoring.
- Clean code: type hints, tests, lint, CI.
- Documentation with an architecture diagram.
- Metrics and baseline comparison.
- Demo: video, Telegram bot, hosted service.
- Reproducible run, for example `docker-compose up`.

---

## Project ideas

### Starting level
1. Apartment price prediction for your city: parsing, CatBoost, SHAP, FastAPI.
2. Resume or vacancy classifier: infer level or role from text.
3. Churn prediction on an open dataset with MLflow and scheduled retraining.

### Middle level
4. CV classification or detection on your own dataset.
5. Russian review classification with RuBERT fine-tuning.
6. nanoGPT trained on a small Russian text corpus, with a detailed README.

### Strong portfolio level
7. RAG bot over a domain knowledge base: Qdrant, LLM API, Telegram.
8. Recommender for movies, books, or products: two-tower, FAISS, A/B simulation.
9. End-to-end MLOps platform: DVC, MLflow, Kubernetes, Prometheus, Evidently.
10. LoRA fine-tune of Saiga or T-lite with vLLM serving and quality benchmark.

### Robotics + ML
11. RL agent for a manipulator in simulation, Isaac Sim or MuJoCo.
12. Robot vision: detection, tracking, grasp prediction.
13. Small VLA-style prototype in simulation.

---

## Project README template

```markdown
# Project Name

> One-line project summary.

## Problem
What the project solves and why it matters.

## Architecture
Mermaid diagram or image.

## Results
| Metric | Baseline | My model |
|---|:---:|:---:|
| F1 | 0.72 | **0.83** |
| Latency p99 | 220 ms | **45 ms** |

## Run
```bash
docker-compose up
```

## Stack
Python, PyTorch, FastAPI, Docker, ...

## References
- dataset: ...
- model: ...
- papers: ...
```

---

## Kaggle and competitions

- Bronze in a tabular competition is a realistic 2-3 month target.
- Silver is already a strong signal.
- Russian alternatives: AI Journey Contest, Yandex Cup ML track, DataFest competitions.

---

## GitHub profile

- [ ] Pin 3-6 best repositories.
- [ ] Fill bio with CV or Telegram link.
- [ ] Add a profile README repository.
- [ ] Contribute to open source through issues, docs, or small PRs.
- [ ] Good targets: PyTorch, Hugging Face, Qdrant, CatBoost, ClearML, Albumentations.
