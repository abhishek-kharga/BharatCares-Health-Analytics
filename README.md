# BharatCares: Healthcare Data Analytics with AI

**Prepared by:** Abhishek Kharga  
**Project type:** AI/data analytics internship demonstration

## Overview
This project demonstrates data cleaning, exploratory data analysis, visualization, and baseline machine-learning classification using a locally generated synthetic healthcare dataset. It predicts a synthetic follow-up flag to demonstrate the ML workflow.

> **Safety and data note:** All records are artificial. This project is educational, not clinically validated, and must not be used for diagnosis, treatment, or real patient decisions.

## Technologies
- Python
- Jupyter Notebook
- pandas and NumPy
- Matplotlib
- scikit-learn (Random Forest, preprocessing, evaluation metrics)

## Dataset
The notebook generates 1,200 artificial records in code using a fixed random seed. No external dataset or private patient data is required.

## Setup and run
1. Install Python 3.10 or newer.
2. Open a terminal in this project folder.
3. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```
4. Start Jupyter:

   ```bash
   jupyter notebook
   ```
5. Open `Abhishek_BharatCaresHealthAnalytics.ipynb` and choose **Run All**.

## Workflow
1. Generate synthetic data.
2. Inspect data types, missing values, duplicates, and summary statistics.
3. Visualize department volume, waiting times, age distribution, and target balance.
4. Compare group-level summary statistics.
5. Split the data into training and testing sets.
6. Train a Random Forest pipeline.
7. Evaluate accuracy, precision, recall, F1-score, and a confusion matrix.
8. Run an example prediction and discuss limitations.

## Expected outputs
Charts, summary tables, classification metrics, confusion matrix, and an example model prediction appear when notebook cells are run.

## Limitations and future work
The model learns from artificial data and a simulated target. Its metrics do not demonstrate real-world clinical performance. Future work could use an approved de-identified dataset, validate target definitions with domain experts, assess fairness, use cross-validation, and document data governance.

## Repository
Create a GitHub repository and upload the four required submission files. Add the final repository URL to the internship form after confirming the repository is accessible.
