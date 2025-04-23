⚙️ Machine Learning Operations Experiments
This repository contains a collection of experiments related to Machine Learning Operations (MLOps). Each experiment demonstrates best practices in model training, versioning, reproducibility, performance evaluation, and more.

📚 Experiments Overview
✅ Experiment 2: Model Training and Versioning
🔍 Objective: Work with a simple dataset (e.g., Iris dataset) to train models and manage their versions.

Tasks Performed:

📂 Data Preparation

🧠 Model Training

🎛️ Hyperparameter Tuning

📝 Result Recording & Comparison

📁 Model Versioning

Models saved as model_v1.pkl, model_v2.pkl, etc., to track iterations.

✅ Experiment 3: Saving and Reusing ML Models
🔍 Objective: Train a model once and reuse it without retraining.

Tasks Performed:

🧠 Train a Model

💾 Save the Model

♻️ Reload and Reuse the Model

✅ Experiment 4: Reproducible ML Pipeline
🔍 Objective: Create a fully reproducible ML workflow using Jupyter and virtual environments.

Tasks Performed:

⚙️ Set up virtual environment (venv / conda)

📦 Install necessary libraries (scikit-learn, pandas, matplotlib)

📓 Jupyter Notebook includes:

Dataset loading (e.g., Titanic, Wine)

Data preprocessing

Model training

💾 Save requirements.txt

☁️ Upload notebook + environment files to GitHub for reproducibility

✅ Experiment 5: Exploratory Data Analysis (EDA) & Reporting
🔍 Objective: Perform EDA on public datasets and generate insightful reports.

Tasks Performed:

🌐 Choose dataset (e.g., from Kaggle or UCI Repository)

🧹 Clean data, handle missing values

📊 Visualizations with seaborn/matplotlib

🔍 Insights on correlation, distribution, and outliers

📄 Export EDA report as PDF (using nbconvert / pandas_profiling)

📥 Commit both notebook and report to the repository

✅ Experiment 6: Visualizing Model Performance
🔍 Objective: Evaluate and compare classification model performance through visual tools.

Tasks Performed:

🧠 Train a binary classifier (e.g., Logistic Regression)

📊 Generate visualizations:

Confusion Matrix

Precision-Recall Curve

🔎 Compare multiple models and determine the best

📂 Store all visuals in a results/ directory

🧰 Tools & Libraries Used
Python 🐍

Scikit-learn ⚙️

Pandas 🐼

Matplotlib 📈

Seaborn 🌊

Jupyter Notebooks 📒

venv / conda for environments
