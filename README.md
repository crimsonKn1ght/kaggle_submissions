# kaggle_submissions

[![Kaggle](https://img.shields.io/badge/Kaggle-gourabr0y555-20beff.svg?style=flat)](https://www.kaggle.com/gourabr0y555/code)
[![Notebooks](https://img.shields.io/badge/notebooks-10-f37626.svg?style=flat)](#from-scratch-implementations)

A copy of my better-received Kaggle notebooks, kept here so they are readable without a
Kaggle account. They fall into two groups: algorithms implemented from scratch to show
the mechanics, and competition notebooks from the Playground series.

## From-scratch implementations

| Notebook | What it covers |
|---|---|
| [Adam Optimizer from Scratch](Adam%20Optimizer%20from%20Scratch.ipynb) | Adam in NumPy, benchmarked against a reference implementation |
| [Backpropagation from scratch for NN](Backpropagation%20from%20scratch%20for%20NN.ipynb) | A network's backward pass by hand, with Bayesian optimisation over the hyperparameters |
| [SVM from scratch](SVM%20from%20scratch.ipynb) | Support vector machines, starting from the margin formulation |
| [Graph Convolutional Networks](Graph%20Convolutional%20Networks.ipynb) | A GCN layer built up from the propagation rule |

## Analysis and validation

| Notebook | What it covers |
|---|---|
| [Adversarial Validation](ADVERSARIAL%20VALIDATION.ipynb) | Detecting train/test distribution shift by training a classifier to tell the two apart ([Kaggle](https://www.kaggle.com/code/gourabr0y555/adversarial-validation)) |
| [Robust Error Analysis Framework](Robust%20Error%20Analysis%20Framework.ipynb) | Structured error analysis for medical image classification, past a single accuracy number |

## Competition notebooks

| Notebook | Competition | Approach |
|---|---|---|
| [Stanford RNA 3D Folding](https://www.kaggle.com/code/gourabr0y555/rna-3d-folding-proteinex-tbm-inference-v-1) | Stanford RNA 3D Folding | Protenix combined with template-based modelling, inference only |
| [S6E1: Student Exam Scores](https://www.kaggle.com/code/gourabr0y555/s6e1-8-56-xgboost-with-ridge-regression) | Playground S6E1 | XGBoost with Ridge regression meta-feature stacking |
| [S5E12: Diabetes Diagnosis](https://www.kaggle.com/code/gourabr0y555/s5e12-eda-k-fold-xgb-boosting) | Playground S5E12 | EDA, K-fold cross-validation, XGBoost |
| [S4E3: CatBoost](https://www.kaggle.com/code/gourabr0y555/ps-s4e3-catboost-eda-importance-plots) | Playground S4E3 | CatBoost with EDA and feature-importance plots |

The four competition notebooks are linked to Kaggle rather than to the files in this
repository, because their filenames contain characters that Windows cannot represent in a
path. They are in the repository and render on github.com; they just cannot be checked
out on a Windows filesystem.

## Notes

These notebooks were written to run in Kaggle's environment, so their input paths point
at `/kaggle/input/...` and their dependencies are whatever the Kaggle image provides.
Running one elsewhere means supplying the dataset and the packages yourself.
