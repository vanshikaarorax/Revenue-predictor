

## Candidate: Vanshika Arora

This folder contains all required files and components for the Oxford DataPlan technical task.

---

## 🔽 What to Download

 The entire folder  contains the following:

* `main.ipynb` – Interactive notebook with all code, outputs, and visualizations.
* `Revenue Index Prediction Write-up.pdf` – Detailed explanation of methodology, feature engineering, and evaluation.
* `data_task.xlsx` – The original data file provided in the task.

You can open the `.ipynb` file using Jupyter Notebook, JupyterLab, or VS Code.

---
## ✅ Notes

* All plots are embedded inside the notebook.
* Model was trained up to 2022 Q3 and evaluated on 2022 Q4 only.
* Total of 19 data points used for training.
* Revenue index was predicted in line with task expectations.
* No `pip install` commands are included to avoid installation errors. If the models fail to run, please ensure the following libraries are available in your environment:

  * `pandas`
  * `numpy`
  * `matplotlib`
  * `seaborn`
  * `scikit-learn`
  * `openpyxl` (for reading `.xlsx` files)
  * `datetime` (Python built-in)
  * `warnings` (Python built-in)


## ✅ Folder Structure

```

├── main_notebook.ipynb        # Jupyter Notebook with full code, explanations, and visualizations
├── writeup.pdf                # Summary write-up of methodology and approach
├── data_task.xlsx             # Original data provided for the task
```

---

## ✅ Notebook Content (main\_notebook.ipynb)

* [x] Data Cleaning of order numbers and transaction data
* [x] Feature Engineering (including period length, normalization, ratios)
* [x] Aggregation of daily data to quarterly format
* [x] Model Training (Linear Regression and Ridge)
* [x] Evaluation Metrics:

  * In-sample R²
  * Percentage Error on 2022 Q4
* [x] Visualizations:

  * Actual vs. Predicted Revenue Index
  * Train/Test period timeline plot
  * Feature correlation heatmap
* [x] Clean code with markdown headers and print statements for clarity
* [x] All `!pip install` commands removed
* [x] Notebook saved with all output cells executed

---

## ✅ Write-Up 

* [x] Overview of the task and datasets used
* [x] Steps for cleaning, feature engineering, and modeling
* [x] Evaluation results with metrics
* [x] Explanation of modeling choices and how overfitting was avoided
* [x] Professional tone, clear structure, no emojis


---

## Submission Notes

* Please review the notebook directly in Jupyter or VS Code to see the outputs.
* No additional installation is required — all used libraries are standard or built-in.

---

Thank you for reviewing my submission!

**– Vanshika Arora**
