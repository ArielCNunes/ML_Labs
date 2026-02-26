# ML Labs

A collection of machine learning laboratory notebooks covering foundational supervised learning techniques, from data handling through to classification with decision trees and image recognition.

## Labs Overview

| Lab | Topic | Key Datasets |
|-----|-------|-------------|
| [Lab 1](#lab-1--data-handling-and-visualisation-fundamentals) | Data Handling & Visualisation Fundamentals | `people.csv`, `students.csv`, `devices.json`, `weather.json` |
| [Lab 2](#lab-2--linear-regression) | Linear Regression | `mtcars.csv` |
| [Lab 3](#lab-3--logistic-regression) | Logistic Regression | `heart_disease.csv`, `wine_quality.csv` |
| [Lab 4](#lab-4--k-nearest-neighbours) | k-Nearest Neighbours | `penguins.csv`, Breast Cancer (sklearn) |
| [Lab 5](#lab-5--decision-trees) | Decision Trees | Various sklearn datasets |
| [Lab 6](#lab-6--handwritten-digit-recognition) | Handwritten Digit Recognition | Custom digits image dataset |

---

## Lab 1 – Data Handling and Visualisation Fundamentals

**Notebook:** `lab-1/ML_Lab1_Data_Fundamentals.ipynb`

**Objectives:**
- Load and manipulate data with **pandas**
- Visualise data with **matplotlib**
- Work with images as **numpy** arrays
- Get familiar with basic **scikit-learn** workflows

**Prerequisites:** Basic Python and numpy knowledge

---

## Lab 2 – Linear Regression

**Notebook:** `lab-2/LinearRegressionLab.ipynb`

Walks through a simple linear regression example using the Motor Trend Car Road Tests (`mtcars`) dataset, then extends to multiple linear regression models.

**Topics covered:**
- Simple and multiple linear regression
- Model evaluation and interpretation

**Reference:** `lab-2/regression-lab.pdf`

---

## Lab 3 – Logistic Regression

**Notebook:** `lab-3/logistic_regression_lab.ipynb`

**Learning objectives:**
- Understand the difference between linear and logistic regression
- Implement binary logistic regression for classification tasks
- Visualise decision boundaries and model performance
- Evaluate classification models using appropriate metrics (accuracy, precision, recall, F1)
- Use validation sets for feature selection and regularisation tuning
- Extend logistic regression to multi-class problems

**Datasets:**
- `heart_disease.csv` – binary classification
- `wine_quality.csv` – multi-class classification

---

## Lab 4 – k-Nearest Neighbours

**Notebooks:**
- `lab-4/knn_lab.ipynb` – Palmer Penguins classification
- `lab-4/BreastCancerExample.ipynb` – Cross-validation with KFold

**Learning objectives:**
- Load and explore the Palmer Penguins dataset
- Understand the importance of feature scaling for kNN
- Use cross-validation to tune hyperparameters
- Compare kNN and Logistic Regression
- Evaluate a final model on a held-out test set

---

## Lab 5 – Decision Trees

**Notebook:** `lab-5/Decision Trees Lab.ipynb`

**Learning objectives:**
- Understand how decision trees partition the feature space
- Visualise decision boundaries without requiring Graphviz
- Explore the effect of key hyperparameters (`max_depth`, `min_samples_split`, `min_samples_leaf`)
- Compare decision trees with kNN and logistic regression
- Use cross-validation with multiple metrics (accuracy, F1, precision, recall)

---

## Lab 6 – Handwritten Digit Recognition

**Notebook:** `lab-6/digits.ipynb`

Builds an image classifier for handwritten digits (0–9) using a custom image dataset processed with **Pillow**.

**Topics covered:**
- Reading and preprocessing images with Pillow
- Representing images as feature vectors
- Training and evaluating a digit classifier

---

## Getting Started

### Prerequisites

- Python 3.8+
- [Conda](https://docs.conda.io/en/latest/) (recommended) or pip

### Installation

**Using pip:**

```bash
pip install -r requirements.txt
```

**Using Conda (Lab 1 environment file):**

```bash
conda env create -f lab-1/ml.yml
conda activate ml
```

### Running the Notebooks

```bash
jupyter lab
```

Then open the notebook for the lab you want to work on.

---

## Dependencies

| Package | Purpose |
|---------|---------|
| `numpy` | Numerical computing and array manipulation |
| `pandas` | Data loading and manipulation |
| `matplotlib` | Plotting and visualisation |
| `seaborn` | Statistical data visualisation |
| `scikit-learn` | Machine learning algorithms and utilities |
| `Pillow` | Image loading and processing |
| `jupyterlab` / `notebook` | Notebook runtime |
| `ipykernel` / `ipython` | Interactive Python kernel |
