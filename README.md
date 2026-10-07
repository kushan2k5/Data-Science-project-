# Data-Science-project-1. Logistic Regression: Titanic Survival & SUV Purchase
Two binary classification problems with logistic regression.
- **Titanic:** predicted survival from age and sex, **~80% accuracy** (143 test passengers).
- **SUV purchase:** predicted purchase from age, salary and gender, **82.5% accuracy** (400 customers).
- Evaluated with confusion matrices and precision/recall/F1.
- 📓 [Notebook](01-logistic-regression/)

### 2. Feature Scaling
Compared Min-Max normalization and StandardScaler on a small dataset (age, salary), showing how each rescales features for distance-based models.
- 📓 [Notebook](02-feature-scaling/)

### 3. Linear Regression: Salary vs Experience
Predicted salary from years of experience.
- **R² = 0.90** on the test set; correlation between the two variables is **0.98**.
- Visualized the fitted line and a correlation heatmap.
- 📓 [Notebook](03-linear-regression-salary/)

### 4. Decision Trees & Cost-Complexity Pruning
Used pruning to reduce overfitting in decision tree regressors.
- **House prices (1,460 homes, 81 features):** R² of 0.80 with a depth-5 tree, 0.83 after pruning.
- **Medical insurance charges (1,338 rows):** R² improved from **0.73 to 0.86** after pruning. The tree's first split is smoker status, which is a clear and explainable finding.
- **Diabetes dataset:** see note below.
- 📓 [Notebook](04-decision-trees-pruning/)
