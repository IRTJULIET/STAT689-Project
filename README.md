# STAT689-Project
Handling mislabeled training data for classification

## Team Members:
- Siddharth Subramaniyam
- Shubham Jain

## Report
Report is present in [Report.ipynb](Report.ipynb) file

## Code
1. General Approach to Identify Mislabeling:
    *  Code is in [script.py](script.py), [main.py](main.py), [util.py](util.py) and [dataset.py](dataset.py)
    *  Dataset for this is present in [mnist-data](mnist-data/) folder

2. Rankprunning Approach
    * Rankpruning implementation - [rankpruning.py](rankpruning.py)
    * Comparison and analysis - [rp_comparison.py](rp_comparison.py)
    * Generic classifier interface for use with RP - [classifier_for_rp.py](classifier_for_rp.py)
