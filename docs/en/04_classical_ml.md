# 4. Classical ML

> Russian version: [04_classical_ml.md](../ru/04_classical_ml.md)

> Classical ML is still the base of most production systems and interviews.

---

## Algorithms

### Supervised learning
- [ ] Linear regression: derivation, Ridge, Lasso, ElasticNet
- [ ] Logistic regression: probabilistic view, log-loss
- [ ] kNN: metrics, kd-tree
- [ ] Naive Bayes
- [ ] SVM: kernel trick, soft margin
- [ ] Decision trees: Gini, entropy, MSE
- [ ] Random Forest: bagging, OOB
- [ ] Gradient Boosting: training procedure and theory
  - XGBoost
  - LightGBM
  - CatBoost

### Unsupervised learning
- [ ] K-Means, K-Means++, MiniBatch K-Means
- [ ] Hierarchical clustering
- [ ] DBSCAN, HDBSCAN
- [ ] PCA, t-SNE, UMAP
- [ ] Anomaly detection: Isolation Forest, LOF

### Recommender systems
- [ ] Content-based and collaborative filtering
- [ ] Matrix factorization: ALS, SVD
- [ ] Implicit / LightFM
- [ ] Two-tower models basics

---

## Metrics

| Task | Metrics |
|---|---|
| Binary classification | Accuracy, Precision, Recall, F1, ROC-AUC, PR-AUC, log-loss |
| Multiclass | macro / micro / weighted F1 |
| Regression | MSE, RMSE, MAE, MAPE, R2 |
| Ranking | NDCG, MAP, MRR, Hit@K |
| Clustering | Silhouette, Davies-Bouldin, ARI |

---

## Tools

- [ ] scikit-learn: Pipeline, ColumnTransformer, GridSearch
- [ ] CatBoost: categorical features, GPU training
- [ ] XGBoost and LightGBM
- [ ] Optuna for hyperparameter search
- [ ] SHAP and LIME for interpretability
- [ ] MLflow for model tracking and registry
- [ ] Feature engineering: target encoding, datetime features

---

## Validation

- [ ] Train / validation / test split
- [ ] K-Fold, Stratified K-Fold, GroupKFold, TimeSeriesSplit
- [ ] Data leakage and how to find it
- [ ] Imbalanced classes, class weights, SMOTE

---

## Resources

| Resource | Level |
|---|:---:|
| [Hands-On Machine Learning](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/), Aurelien Geron | ** |
| [Kaggle Learn](https://www.kaggle.com/learn) | * |
| [StatQuest](https://www.youtube.com/@statquest) | ** |
| [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) | ** |
| [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) | ** |
| [CatBoost docs](https://catboost.ai/docs/) | ** |

---

## Checkpoint projects

1. Get a Bronze-level result in a tabular Kaggle competition.
2. Build a full pipeline for churn prediction, credit scoring, or demand forecasting: EDA, features, CatBoost, SHAP, REST API.
