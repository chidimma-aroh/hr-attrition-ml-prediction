# HR Attrition ML Prediction

Real IBM HR Dataset: 1470 employees, 16% attrition | Python + Scikit-learn

## Performance - Real Data (Hugging Face)
- Accuracy: 82.99%
- Precision: 42.86%
- Recall: 19.15%
- Model: RandomForest 200 trees, max_depth 12, class_weight='balanced'
- Features: ALL 35 features (Age, MonthlyIncome, OverTime, JobSatisfaction, YearsSinceLastPromotion, etc.)
- Threshold 0.6: Precision 52%+

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Hugging Face Datasets, Git

## Run in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chidimma-aroh/hr-attrition-ml-prediction/blob/main/hr_attrition_50_PRECISION.ipynb)

## Excel vs Python
- Excel: PivotTable, =H5/(G5+H5)=18.03% attrition rate, 4 slicers, 2 charts
- Python: ML pipeline, classification, feature importance, threshold tuning

## Author
Aroh Chidimma - Junior AI/ML Engineer
GitHub: github.com/chidimma-aroh
