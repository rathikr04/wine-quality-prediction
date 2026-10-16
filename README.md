# Wine Quality Prediction - CODTECH Internship Task 3

## Objective
Predict wine quality (score 3-8) based on chemical properties.

## Dataset
- Name: Wine Quality Red (UCI Machine Learning Repository)
- File: winequality-red.csv (1599 rows, 12 columns)
- Link: https://archive.ics.uci.edu/dataset/186/wine+quality
- Features: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, etc.
- Target: quality

## Model Used
RandomForestClassifier (100 trees)

## Steps
1. Loaded dataset using pandas
2. Split data 80% train, 20% test
3. Trained Random Forest
4. Evaluated accuracy

## Result
Accuracy: ~70%

## How to Run
pip install -r requirements.txt
python wine_quality_prediction.py

## Author
Rathik - CODTECH Internship
