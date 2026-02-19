# Generative vs Discriminative Classification

## Description
This project compares three classifiers:
1. Gaussian Generative Model (Different Covariances)
2. Gaussian Generative Model (Same Covariance)
3. Linear SVM

The goal is to study how assumptions affect decision boundaries.

## Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

Install dependencies:
pip install numpy pandas matplotlib scikit-learn

## How to Run
1. Place 'binclass.txt' in the same directory.
2. Run the script:
   python main.py

3. The script generates:
   - QDA-like boundary
   - LDA-like boundary
   - Linear SVM boundary
