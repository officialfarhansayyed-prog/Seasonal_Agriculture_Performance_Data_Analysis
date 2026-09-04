## 🌾 Seasonal Agriculture Performance Analysis

### Overview
This repository contains a comprehensive agricultural data analytics project built in Google Colab. The study evaluates a 4,000-record agricultural dataset across **Kharif**, **Rabi**, and **Zaid** seasons to uncover key environmental drivers behind crop yield and farm profitability.

### Key Features & Workflow
* **Data Cleaning & Preparation**: Missing value imputation via domain group medians (`Season` & `Crop`) and outlier detection using Interquartile Range (IQR) bounds.
* **Exploratory Data Analysis**: Univariate, bivariate, and multivariate distribution visualisations (Scatter plots, Violin plots, Bivariate KDE density maps).
* **Statistical Rigor**: One-Way ANOVA and Tukey’s HSD post-hoc testing ($p < 0.05$) to mathematically prove performance variations across seasons.
* **Machine Learning**: Random Forest Regressor models to rank yield and profitability feature importances.
* **Data-Driven Strategy**: Evidence-based recommendations for seasonal crop planning, soil moisture tracking, and micro-irrigation management.

### Tech Stack
* **Language**: Python 3.x
* **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`, `scikit-learn`
