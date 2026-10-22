# Datheon Machine Learning & Data Science Internship

This repository contains my project work for the **Datheon Machine Learning & Data Science Internship**.

## Completed Tasks

### Task 1: Multi-Class Benchmark Classification Pipeline — Iris Dataset

**Objective:** Build and evaluate supervised machine-learning classification models using the Iris dataset.

**Work completed:**
- Loaded and explored the Iris dataset using Pandas.
- Checked dataset dimensions, feature information, missing values, and class distribution.
- Visualized feature relationships with a pairplot.
- Split the data into training and testing sets using an 80/20 split.
- Applied `StandardScaler` for feature scaling in machine-learning pipelines.
- Trained and evaluated:
  - Logistic Regression
  - Decision Tree Classifier
- Compared model performance using accuracy, precision, recall, and F1-score.
- Generated classification reports and confusion-matrix heatmaps.
- Visualized the decision tree and decision boundaries.

**Dataset:** `iris.csv`

**Notebook:** `Task_1_Iris_Classification/Iris_Classification.ipynb`

## Repository Structure

```text
Datheon_Machine_Learning_&_Data_Science_Internship/
├── README.md
└── Task_1_Iris_Classification/
    ├── Iris_Classification.ipynb
    └── iris.csv
```

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run

1. Clone or download this repository.
2. Open the `Task_1_Iris_Classification` folder.
3. Open `Iris_Classification.ipynb` in Jupyter Notebook.
4. Make sure `iris.csv` is in the same folder as the notebook.
5. Run the notebook cells from top to bottom.

Install the required libraries if they are not already available:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Results

The notebook reports and visualizes the performance of Logistic Regression and Decision Tree models using accuracy, precision, recall, F1-score, classification reports, and confusion matrices. Run all cells in the notebook to view the generated results.

## Notes

- This repository currently documents **Task 1**.
- Model metrics should be taken from the notebook outputs after running the notebook.
- This project is submitted for review as part of the Datheon Machine Learning & Data Science Internship.

