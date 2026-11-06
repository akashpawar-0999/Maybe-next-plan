## 1. Which libraries should you learn next?

Don't try to learn 10 libraries together. Follow this order:

| Priority | Library      | What you will use it for                          |
| -------- | ------------ | ------------------------------------------------- |
| 1        | Scikit-learn | Machine Learning algorithms                       |
| 2        | SciPy        | Scientific computing, statistics and optimization |
| 3        | Seaborn      | Statistical data visualization                    |
| 4        | Statsmodels  | Statistical analysis and regression summaries     |
| 5        | Joblib       | Saving and loading trained ML models              |
| 6        | PyTorch      | Deep Learning and Neural Networks                 |

---

1\. Scikit-learn — Learn this first

[File:Scikit learn logo small.svg - Wikimedia Commons](https://images.openai.com/static-rsc-4/cEDR7NGDHkT2KWKOKYd-9dGB0AWeJo0HGIHL6Ynpoa6Tn77SbVVtXk1UVZkmuPGP0JWLi8RSCvKPFEomRQiVR_9IO3zUEioCu4rxpGKIzTeyVMfWvLenUSy3CVhs41vDZr5MiVeol7aOIX7mjX2XBwuxC6QShypA9d-YM2LKYLI?purpose=inline)

This will be your primary ML library.

Learn these modules in order:

- `sklearn.linear_model` — Linear and Logistic Regression.
- `sklearn.model_selection` — Train/test split and cross-validation.
- `sklearn.metrics` — Evaluate model performance.
- `sklearn.preprocessing` — Scaling and encoding.
- `sklearn.neighbors` — KNN.
- `sklearn.tree` — Decision Trees.
- `sklearn.ensemble` — Random Forest.

### Understand these Scikit-learn functions

| Function                | Purpose                                    |
| ----------------------- | ------------------------------------------ |
| `LinearRegression()`    | Creates the model                          |
| `train_test_split()`    | Divides training and testing data          |
| `fit()`                 | Trains the model                           |
| `predict()`             | Predicts new values                        |
| `coef_`                 | Gives the learned slope                    |
| `intercept_`            | Gives the learned intercept                |
| `mean_absolute_error()` | Measures average absolute prediction error |
| `mean_squared_error()`  | Measures squared prediction error          |
| `r2_score()`            | Measures goodness of fit                   |


Official guide: [Scikit-learn Getting Started](https://scikit-learn.org/stable/getting_started?utm_source=chatgpt.com).

---

2\. SciPy

[Introduction to SciPy - DEV Community](https://images.openai.com/static-rsc-4/yPVq5EpGdTrpkkM-K0w1x6wZrfXv0dqTuvihz5xYyvCmzEBSoJrirwpwrnUhPF9TDu7Ic9ybYlh7HKf75fbwXAs0CVzlySsyW4lre3WIgb9NcSALSF3gjAj-ppKuRA8xvmPvgoyvecEw5S5Wm9FSamOfU6y6T15tfNG2yV1FpJI?purpose=inline)

Learn:

- Statistical functions.
- Probability distributions.
- Optimization.
- Scientific calculations.

You don't need to master SciPy before starting regression.

---

3\. Seaborn

[Beautiful Plots With Python and Seaborn | by Juan Cruz Martinez | Better Programming](https://images.openai.com/static-rsc-4/0BY0WVHWik-CdQYVJVJqc1Fv_k8foiboytEkDZFmZDaLpHSrdzxRg2jhwlT_BR9yiDscgzJNIAha_sGgRL-7Dum_yIJw8KtWnSpCQge8HI5cxtNgD9kDyWTobyBRSc1GxVRQiT7jwa3RWl4NEFjG_xMo-S-P5SINK8cdh_-buAU?purpose=inline)

Since you have already started Matplotlib, learn:

- Heatmaps.
- Pairplots.
- Boxplots.
- Correlation plots.
- Distribution plots.

---

4\. Statsmodels

Learn this after Scikit-learn basics.

Useful for:

- Regression summaries.
- P-values.
- Confidence intervals.
- Statistical significance.


---

5\. Joblib

Learn how to save and load trained models so you don't have to train them every time.


---

6\. PyTorch

Learn this later, after Classical ML.

It is useful for:

- Neural Networks.
- Deep Learning.
- Computer Vision.
- NLP.

The official PyTorch beginner course covers tensors, datasets, model building, automatic differentiation and optimization.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://docs.pytorch.org\&sz=32)

PyTorch Tutorials 2.15.0+cu132 documentation+1

---
## # What should you learn after Simple Linear Regression?

Follow this sequence:

---
Phase 1 — Regression

Start here

1. Simple Linear Regression
2. Multiple Linear Regression
3. Polynomial Regression
4. Ridge and Lasso Regression


---

Phase 2 — Classification

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest
5. Naive Bayes
6. Support Vector Machine (SVM)


---


Phase 3 — ML Data Processing

1. Missing value handling
2. Feature scaling
3. Label Encoding
4. One-Hot Encoding
5. Train/Test Split
6. Cross Validation
7. Hyperparameter Tuning

---

Phase 4 — Unsupervised Learning

1. K-Means Clustering
2. Hierarchical Clustering
3. Principal Component Analysis (PCA)


---

Phase 5 — Deep Learning

1. Neural Network basics
2. Activation Functions
3. Forward Propagation
4. Backpropagation
5. Gradient Descent
6. PyTorch

---

## 5. Mathematics you should learn alongside ML

You don't need advanced mathematics initially.

| Mathematics                        | Importance                      |
| ---------------------------------- | ------------------------------- |
| Mean, Median, Mode                 | High                            |
| Variance and Standard Deviation    | High                            |
| Probability                        | High                            |
| Correlation and Covariance         | High                            |
| Linear Algebra (vectors, matrices) | High                            |
| Derivatives                        | Medium                          |
| Partial Derivatives                | Medium                          |
| Gradient Descent                   | High for understanding training |

---
---
---
---
---
---

Since you have already completed Python basics, NumPy, Pandas, and Matplotlib, you are ready to start Machine Learning with Scikit-learn.

You don't need to learn 10+ libraries before starting ML.

## 1. Libraries to learn before Scikit-learn

| Order | Library      | What to learn                                           |-- |
| ----- | ------------ | ------------------------------------------------------- | --|
| 1     | NumPy        | Arrays, indexing, broadcasting, mathematical operations | done
| 2     | Pandas       | DataFrames, filtering, cleaning, missing values         |done
| 3     | Matplotlib   | Line plots, scatter plots, histograms, subplots         |done
| 4     | Seaborn      | Heatmaps, pairplots, distribution plots, boxplots       | pending 
| 5     | SciPy        | Basic statistics and scientific calculations            |pending
| 6     | Scikit-learn | ML algorithms, preprocessing, training, testing         |pending

You can start Scikit-learn now

## 2. Other concepts you should learn

Before diving deeply into ML, understand these mathematical concepts:

| Mathematics    | Topics                                           |
| -------------- | ------------------------------------------------ |
| Statistics     | Mean, median, mode, variance, standard deviation |
| Probability    | Basic probability, conditional probability       |
| Linear Algebra | Vectors, matrices, matrix multiplication         |
| Calculus       | Derivatives, gradients, basic differentiation    |

You don't need advanced mathematics initially.

## 3. Scikit-learn learning roadmap

Learn these topics in this order:

1. ML Fundamentals

   Supervised vs Unsupervised Learning, features, labels, datasets.
2. Data Preprocessing

   `train_test_split()`, `StandardScaler`, `LabelEncoder`, `OneHotEncoder`, handling missing values.
3. Regression Algorithms

   Linear Regression, Multiple Linear Regression, Polynomial Regression.
4. Classification Algorithms

   Logistic Regression, KNN, Decision Tree, Random Forest, SVM.
5. Unsupervised Learning

   K-Means Clustering, Hierarchical Clustering, PCA.
6. Model Evaluation

   Accuracy, Precision, Recall, F1-score, Confusion Matrix, MAE, MSE, RMSE, R².
7. Advanced Concepts

   Cross-validation, Hyperparameter Tuning, GridSearchCV, Pipelines.

## 4. My recommended learning sequence

1. Complete Seaborn basics (2–3 days).
2. Learn basic statistics and probability.
3. Start Scikit-learn.
4. Implement Simple Linear Regression.
5. Build small ML projects using real datasets.
