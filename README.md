# Evaluating Models
Evaluating multiple model results in sklearn using accuracy, recal, precision, f-score and receiver operating characteristic curves (roc). Dataset used in this notebook is the credit fraud dataset from Kaggle.

# Before you get started
- Usage of python and sklearn.
- Train test split concept.
- Training basic models.
- Producing reports and evaluation of models.

# Setup
**How to obtain this repository:**
```sh
git clone https//link.to.this.projects.git-repo
```
**Modules/dependencies:**
- `pandas`
- `sklearn`
- `jupyter`
- `matplotlib`

Install the following dependences:
```sh
pip install pandas sklearn jupyter
```

# Tests
- Built K-Nearest Neighbors, Logistic Regression, Random Forest and Gaussian Naive Bayes models.
- Produced ROC Curves for each in matplotlib
- Produced classfication reports for each model using `classification_report()` function from sklearn.

# Contributors
- Daniel Corcoran

# Sources
- [sklearn documentation](https://scikit-learn.org/)
- [article on recall, precision, f1-scores #1](https://blog.exsilio.com/all/accuracy-precision-recall-f1-score-interpretation-of-performance-measures/)
- [article on recall, precision, f1-scores #2](https://towardsdatascience.com/accuracy-precision-recall-or-f1-331fb37c5cb9)
- [Credit Card Fraud dataset downloaded from Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)
