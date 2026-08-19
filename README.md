# A Cross-Continental Guideline Comparison and Multicenter Study Using a Machine Learning Approach Based on Real-World Data

This is the repo for hosting the codes for the article "Toward Global Standardization of Neurosyphilis Diagnosis: A Cross-Continental Guideline Comparison and Multicenter Study Using a Machine Learning Approach Based on Real-World Data"

We built an online streamlit app at: [link](https://nspredicton.streamlit.app/)
<img width="1386" alt="streamlit app" src="https://github.com/user-attachments/assets/a0a472b8-ad98-4f85-98fe-b1a849bea593" />

## 1. System Requirements

### Software Dependencies
The software has been developed and tested with the following specific versions:

* **Operating System:** Windows, macOS, or Linux (Tested on Windows 11)
* **Python:** 3.12.2
* **Core Libraries:** pandas, numpy, matplotlib, seaborn
* **Machine Learning & Evaluation:** scikit-learn (1.4.0), xgboost (2.1.1), imbalanced-learn, statkit
* **Explainability:** shap (0.45.0)
* **R Integration (Optional):** rpy2 & R package pROC

### Hardware Requirements
* **Standard Desktop Computer:** CPU with at least 8GB of RAM. No GPUs required.

## 2. Installation Guide

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn shap statkit openpyxl rpy2
```

Optional R installation:
```R
install.packages("pROC")
```
The installation process may take a few minutes.

## 3. Demo Instructions

1. Prepare sample data file.
2. Run data loading:
```python
import pandas as pd
mydata = pd.read_excel('demo_data.xlsx')
```
3. Run model pipeline[MD Xgboost.ipynb].
Takes a few minutes depending on the size of the data.

## 4. Instructions for Use

Ensure mandatory variables exist: `Age`, `Sex`, `Serum_TT`, `Serum_NTT`, `CSF_NTT` (target), `CSF_TT`, `CSF_WBC`, `CSF_Protein`, `NS_Symptom`.


# Notes
We will provide the link to the article once published. 

