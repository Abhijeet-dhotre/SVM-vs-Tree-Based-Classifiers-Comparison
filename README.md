# SVM vs Tree-Based Classifiers Comparison

A comprehensive machine learning project comparing Support Vector Machine (SVM) classifiers with Tree-Based classifiers across multiple datasets.

## Overview

This project evaluates and compares the performance of SVM and tree-based classifiers on different datasets to understand their strengths and weaknesses in various scenarios.

## Datasets

| Dataset | Classes | Features | Description |
|---------|---------|----------|-------------|
| Wine | 3 | 13 | Chemical analysis of wine samples |
| Digits | 10 | 64 | Handwritten digit images (8x8) |
| Synthetic | 4 | 2 | Non-linear boundary patterns |

## Models Compared

### SVM Classifiers
- Linear SVM
- RBF (Radial Basis Function) SVM
- Polynomial SVM

### Tree-Based Classifiers
- Decision Tree
- Random Forest
- Gradient Boosting

## Results Summary

| Dataset | Best Model | Accuracy | F1-Score | Train Time (s) |
|---------|------------|----------|----------|----------------|
| Wine | Decision Tree | 100.00% | 1.0000 | 0.0011 |
| Digits | SVM (Linear) | 97.50% | 0.9749 | 0.0184 |
| Synthetic | SVM (RBF) | 74.00% | 0.7146 | 0.0064 |

## Files

- `SVM_Tree_Classifiers_Comparison.ipynb` - Main Jupyter notebook with analysis
- `best_models_summary.csv` - Summary of best performing models
- `summary_digits.csv` - Detailed results for digits dataset
- `radar_comparison.png` - Radar chart visualization comparing models
- `SVM_vs_Tree_Classifiers_Wine_Digits_Report.pdf` - PDF report with findings

## Requirements

- Python 3.x
- scikit-learn
- matplotlib
- seaborn
- pandas
- numpy

## Installation

```bash
pip install scikit-learn matplotlib seaborn pandas numpy
```

## Usage

Open and run the Jupyter notebook:

```bash
jupyter notebook SVM_Tree_Classifiers_Comparison.ipynb
```

## Key Findings

1. **Wine Dataset**: Decision Tree achieves perfect 100% accuracy, indicating clear separability in the chemical features.

2. **Digits Dataset**: Linear SVM performs best (97.50%), showing that digit classification benefits from linear decision boundaries in the feature space.

3. **Synthetic Dataset**: SVM with RBF kernel handles non-linear boundaries best (74%), demonstrating its strength in capturing complex patterns.

## License

This is an educational machine learning project.