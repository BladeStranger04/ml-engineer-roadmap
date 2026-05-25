# 7. MLOps & Production

> Russian version: [07_mlops.md](../ru/07_mlops.md)

> The difference between an ML Engineer and a Data Scientist is often the ability to ship, monitor, and maintain models in production.

---

## Containers

- [ ] Docker: Dockerfile, multi-stage build, slim images
- [ ] docker-compose
- [ ] Kubernetes basics: pod, deployment, service, ingress, configmap
- [ ] Helm charts basics
- [ ] GPU containers with `nvidia-container-toolkit`

---

## Versioning

- [ ] Git for code
- [ ] DVC or LakeFS for data
- [ ] MLflow Model Registry or Weights & Biases Artifacts for models
- [ ] Model cards

---

## Experiments

- [ ] MLflow Tracking: runs, metrics, artifacts
- [ ] Weights & Biases
- [ ] ClearML
- [ ] Hydra / OmegaConf for experiment configs

---

## Serving

| Approach | Use when |
|---|---|
| FastAPI + Uvicorn | simple models, REST / JSON |
| gRPC | low latency, binary payloads |
| Triton Inference Server | production GPU, multiple models |
| TorchServe | PyTorch-only serving |
| Ray Serve | scaling and autoscaling |
| vLLM / TGI | LLM inference |
| ONNX Runtime / TensorRT | hardware optimization |

- [ ] Request batching
- [ ] Caching with Redis
- [ ] A/B testing for models
- [ ] Canary and shadow deployments

---

## CI/CD for ML

- [ ] GitHub Actions or GitLab CI
- [ ] Pre-commit hooks, linting, tests
- [ ] CI flow: lint, tests, train, eval, deploy
- [ ] Continuous training by schedule or trigger
- [ ] Feature stores: Feast

---

## Monitoring

- [ ] Prometheus + Grafana for service metrics
- [ ] Sentry for errors
- [ ] ML metrics: latency, throughput, RPS, data drift, concept drift, prediction distribution
- [ ] Evidently AI for ML monitoring
- [ ] Alerting

---

## Platforms

- Yandex DataSphere and Yandex Cloud ML
- Cloud.ru / SberCloud
- VK Cloud
- Selectel ML platform
- Internal ML platforms at larger companies

---

## Resources

| Resource | Level |
|---|:---:|
| [Made With ML](https://madewithml.com/) | *** |
| Designing Machine Learning Systems, Chip Huyen | *** |
| Machine Learning Engineering, Andriy Burkov | ** |
| [MLOps Community](https://www.youtube.com/@MLOps) | ** |
| [Awesome MLOps](https://github.com/visenger/awesome-mlops) | - |

---

## Checkpoint project

Build an end-to-end ML system:
1. Train a CatBoost or PyTorch model.
2. Log experiments in MLflow.
3. Version data with DVC.
4. Wrap inference in Docker + FastAPI.
5. Add CI/CD through GitHub Actions.
6. Deploy to Kubernetes, minikube is enough.
7. Add Prometheus + Grafana dashboards.
8. Add Evidently drift monitoring.
9. Document the architecture in README.
