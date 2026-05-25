# 8. ML System Design

> Russian version: [08_system_design.md](../ru/08_system_design.md)

> ML System Design is the interview section that usually separates Junior from Middle and Middle from Senior.

---

## Answer framework

1. Clarify the task: business goals, ML metrics, load, SLA, constraints.
2. Define metrics: business, product, offline ML, online ML.
3. Describe data: sources, volume, labeling, privacy, compliance.
4. Start with a baseline, then iterate.
5. Design features and feature store usage.
6. Choose model candidates and validation strategy.
7. Plan inference: latency, batching, caching, GPU or CPU.
8. Plan deployment: A/B, canary, shadow mode.
9. Add monitoring: service metrics, drift, alerts, retraining.
10. Explain trade-offs: cost, quality, latency, complexity.

---

## Common cases

| Case | Where it appears |
|---|---|
| Video or product recommendations | marketplaces, media products |
| Search and ranking | search, classifieds, ecommerce |
| Fraud detection and scoring | banks, fintech |
| Spam and moderation | social networks, mail, classifieds |
| Chatbot or RAG assistant | AI products, support |
| ETA prediction | taxi, delivery |
| Demand forecasting | retail, ecommerce |
| Image generation | generative AI products |
| Detection and face ID | security, fintech, consumer apps |

---

## Resources

| Resource | Level |
|---|:---:|
| Machine Learning System Design, Alex Xu and Sahn Lam | *** |
| Designing Machine Learning Systems, Chip Huyen | *** |
| [Eugene Yan: applied-ml](https://github.com/eugeneyan/applied-ml) | *** |
| [Made With ML: systems](https://madewithml.com/) | ** |
| [Full Stack Deep Learning](https://fullstackdeeplearning.com/) | ** |

---

## What you should be able to do

- Design a recommender system for a marketplace in 60 minutes.
- Explain why two-tower models are common first candidates for retrieval.
- Compare online learning and batch retraining for a given case.
- Estimate an end-to-end latency budget: DB, features, model, response.
