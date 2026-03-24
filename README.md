# ML-Project-GroupA
ML Project, Group A, HEC Lausanne

# Beijing Air Quality Machine Learning Project

Predicting PM2.5 pollution levels using machine learning models and identifying urban pollution patterns.

## 📊 Project Overview

**Research Question:**  
Can machine learning models predict high air pollution levels and identify patterns of pollution across different locations and time periods?

**Dataset:**  
Beijing Multi-Site Air-Quality Data (2013-2017)  
Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Beijing+Multi-Site+Air-Quality+Data)

## 🎯 Objectives

1. **Predict** PM2.5 pollution levels using supervised learning
2. **Identify** key factors influencing air quality
3. **Discover** pollution patterns across time and locations
4. **Interpret** model predictions using SHAP values

## 🛠️ Methods

- **Feature Engineering**: Temporal variables, lag features, rolling statistics
- **Models**: Linear Regression, Random Forest, Gradient Boosting
- **Validation**: Time-series cross-validation
- **Interpretability**: SHAP values
- **Unsupervised Learning**: PCA and K-Means clustering

## 📁 Project Structure

```
beijing-air-quality-ml/
│
├── data/                          # Raw data files (not tracked)
│   ├── README.md
│   └── *.csv
│
├── notebooks/                     # Jupyter notebooks
│   ├── 01_data_exploration.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_interpretation.ipynb
│
├── requirements.txt               # Python dependencies
├── README.md                      # This file
└── .gitignore                     # Ignored files
```

## 🚀 Getting Started

### Open in Google Colab

1. Click on any notebook in `notebooks/` folder
2. Click "Open in Colab" badge
3. Mount Google Drive and upload data
4. Run all cells

### Quick Start Badge
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/beijing-air-quality-ml/blob/main/notebooks/01_data_exploration.ipynb)

*Replace `YOUR_USERNAME` with your GitHub username*

## 📈 Key Results

*(To be updated after analysis)*

- **Best Model**: Gradient Boosting (R² = TBD)
- **Top Features**: TBD
- **Pollution Patterns**: TBD

## 👤 Author

Your Name - [Your GitHub](https://github.com/YOUR_USERNAME)

## 📄 License

MIT License
