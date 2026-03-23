# 🌸 Iris Dataset - Exploratory Data Analysis (EDA) Project

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.2-green.svg)](https://www.djangoproject.com/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0-orange.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-yellow.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12-lightblue.svg)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A comprehensive Exploratory Data Analysis (EDA) web application for the famous Iris dataset. Built with Django, this project demonstrates data loading, inspection, statistical analysis, and advanced visualizations.

---

## 📸 Project Screenshots

### 🗂️ Program Structure
The complete project structure and organization.

![Program Structure](Program_Structure_Image.JPG)

### 🖥️ Main Dashboard
The main interface showing dataset overview and key statistics.

![Dashboard](1_Output_GUI.JPG)

### 📊 Data Types & Statistical Summary
Comprehensive data type information and statistical summary of the dataset.

![Data Types & Statistics](2_Output_Data_Types_Info%20&%20Statistical_Summary.JPG)

### 🌸 Species Distribution & Correlation Analysis
Species distribution visualization and correlation analysis between features.

![Species Distribution & Correlation](3_Output_Species_Distribution%20and%20Correlation_Analysis.JPG)

### 📈 Pairplot - Feature Relationships
Advanced pairplot visualization showing relationships between all features.

![Pairplot](4_Output_%20Pairplot%20-%20Feature%20Relationships.JPG)

### 🔥 Correlation Heatmap
Visual representation of feature correlations with color mapping.

![Heatmap](5_Output_Correlation_Heatmap.JPG)

### 📦 Box Plots - Outlier Detection
Box plots for each feature showing outliers across different species.

![Box Plots](6_Output_Box%20Plots%20-%20Outlier%20Detection.JPG)

### 📊 Feature Distributions
Histogram distributions for all features with kernel density estimation.

![Feature Distributions](7_Output_%20Feature%20Distributions.JPG)

### 🎯 Scatter Plots - Feature Relationships
2D scatter plots showing pairwise feature relationships.

![Scatter Plots](8_Output_%20Scatter%20Plots%20-%20Feature%20Relationships.JPG)

### 🎻 Violin Plots - Density Distribution
Violin plots showing density distribution of features across species.

![Violin Plots](9_Output_%20Violin%20Plots%20-%20Density%20Distribution.JPG)

---

## 📊 Project Overview

This project performs a complete Exploratory Data Analysis on the classic Iris dataset, which contains measurements of 150 iris flowers from three species:

- **Setosa**
- **Versicolor**
- **Virginica**

The dataset includes four features:
- **Sepal Length** (cm)
- **Sepal Width** (cm)
- **Petal Length** (cm)
- **Petal Width** (cm)

The application provides an interactive web interface to explore and visualize the data.

---

## 🎯 Features

### ✅ Data Loading & Inspection
- Load Iris dataset using seaborn
- Display dataset shape and column information
- Show first 10 rows of data
- Display data types and memory usage
- Statistical summary with `.describe()`

### ✅ Statistical Analysis
- Mean, standard deviation by species
- Correlation matrix
- Group-wise statistics
- Outlier detection using IQR method

### ✅ Visualizations
- **Pairplot**: Feature relationships by species
- **Correlation Heatmap**: Feature correlation visualization
- **Histograms**: Distribution of each feature
- **Box Plots**: Outlier detection per species
- **Scatter Plots**: 2D feature relationships
- **Violin Plots**: Density distribution visualization

### ✅ Interactive GUI
- Modern glassmorphism design
- Responsive layout
- All visualizations embedded
- Clean data tables

---


## 🚀 Installation & Setup

### Prerequisites
- Python 3.9 or higher
- pip package manager

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/iris-analysis-project.git
cd iris-analysis-project
