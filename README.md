\## 5-Day Curriculum \& Pipeline Workflow



\* \*\*Day 1: Preprocessing \& Baseline Model\*\* — Cleaned raw data, encoded categorical variables, applied `StandardScaler`, and established a `LogisticRegression` baseline.

\* \*\*Day 2: Decision Trees \& Overfitting Controls\*\* — Evaluated split criteria (Gini vs. Entropy) and constrained tree depth (`max\_depth=5`) to stop overfitting.

\* \*\*Day 3: Parallel Ensembles\*\* — Built 100-tree `BaggingClassifier` and `RandomForestClassifier` models to decorrelate trees and stabilize variance.

\* \*\*Day 4: Sequential Boosting\*\* — Trained `AdaBoostClassifier` and `GradientBoostingClassifier` to iteratively correct errors from earlier trees.

\* \*\*Day 5: Test Set Evaluation \& Deployment\*\* — Benchmark testing on unseen data, threshold optimization, SHAP interpretability, and `.pkl` file export.

