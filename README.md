# ML-Project-GroupA
ML Project, Group A, HEC Lausanne

# Beijing Air Quality Machine Learning Project

Predicting PM2.5 pollution levels using machine learning models and identifying urban pollution patterns.

## 📊 Project Overview

**Research Question:**  
Can machine learning models predict high air pollution levels and identify patterns of pollution across different locations and time periods?

**Dataset:**  
Beijing Multi-Site Air-Quality Data (2013-2017)  
Source: [UCI ML Repository](https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data)

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
ML-Project-GroupA/
│
├── data/
│   ├── README.md
│   ├── raw/                        # Raw dataset files
│   └── processed/                  # Liink to the cleaned dataset
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

## 📂 Data

Due to GitHub file size limitations, the processed dataset is not included in this repository.

You can download the cleaned dataset here:
👉 [Cleaned Dataset + Featured](https://drive.google.com/file/d/1bzj6PRYjdXp9GD9zT2ye54qsrJlczadT/view?usp=drive_link)

After downloading, place the file in:

data/processed/data_clean_featured.csv

Alternatively, the dataset can be downloaded automatically using the provided notebook.(02_feature_engineering.ipynb)

## 📈 Key Results

*(To be updated after analysis)*

- **Best Model**: Gradient Boosting (R² = TBD)
- **Top Features**: TBD
- **Pollution Patterns**: TBD

## 👤 Author

Your Name - [Your GitHub](https://github.com/YOUR_USERNAME)

## 📄 License

MIT License
