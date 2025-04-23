# Machine Learning Operations (MLOps) Experiments

This repository contains **experiments related to Machine Learning Operations (MLOps)**.  
Each experiment focuses on essential components such as model training, versioning, pipeline reproducibility, EDA, and performance visualization.

---

## 🧪 List of Experiments

---

### **Experiment 2: Model Training and Versioning**

**Objective:**  
Work with a simple dataset (e.g., *Iris dataset*) to build and manage versions of a basic machine learning model.

**Tasks Performed:**
- **Data Preparation**
- **Model Training**
- **Hyperparameter Tuning**
- **Record results for comparison**
- **Model Versioning**  
  Save each trained model as a separate version using meaningful filenames  
  _(e.g., `model_v1.pkl`, `model_v2.pkl`)_

---

### **Experiment 3: Saving and Reusing a Machine Learning Model**

**Objective:**  
Train a machine learning model and learn to save and reuse it without retraining.

**Tasks Performed:**
- **Train a Model**
- **Save the Model**
- **Reuse the Model**

---

### **Experiment 4: Creating a Reproducible ML Pipeline**

**Objective:**  
Set up a fully reproducible ML workflow using Jupyter Notebooks and a virtual environment.

**Tasks Performed:**
- **Set up a virtual environment** (`venv` or `conda`)
- **Install necessary libraries** like `scikit-learn`, `pandas`, `matplotlib`
- **Create a Jupyter notebook** that:
  - Loads a dataset (e.g., *Titanic*, *Wine*)
  - Performs data preprocessing
  - Trains a simple model
- **Save the notebook and `requirements.txt`**
- **Share notebook + environment setup** on GitHub for reproducibility

---

### **Experiment 5: Exploratory Data Analysis (EDA) and Report Generation**

**Objective:**  
Perform EDA on a public dataset and generate a comprehensive report.

**Tasks Performed:**
- **Choose a public dataset** (e.g., from *Kaggle* or *UCI Repository*)
- **Data cleaning**, handle null values
- **Visualize data** using `seaborn` or `matplotlib`
- **Generate insights**: correlations, distributions, outliers
- **Export EDA results as PDF** (using `nbconvert`, `matplotlib`, or `pandas_profiling`)
- **Commit EDA notebook and report** to the repository

---

### **Experiment 6: Visualizing Model Performance**

**Objective:**  
Train a classifier and visualize its performance to compare different models.

**Tasks Performed:**
- **Train a binary classification model** (e.g., Logistic Regression)
- **Plot and save the following visualizations:**
  - Confusion Matrix
  - Precision-Recall Curve
- **Compare performance** between two models and identify the better one
- **Store all visualizations** in the `results/` directory

---
