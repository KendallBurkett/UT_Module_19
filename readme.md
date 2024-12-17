## Unsupervised Learning
---

# Crypto Market Clustering Analysis

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)
- [Author](#author)

---

## Description

The **Crypto Market Clustering** project applies **unsupervised machine learning** techniques to cluster cryptocurrencies based on their market performance data. This project utilizes the **K-Means clustering** and **Principal Component Analysis (PCA)** algorithms to identify patterns and group similar cryptocurrencies.

The analysis is implemented in **Jupyter Notebook** and leverages Python libraries such as **pandas**, **scikit-learn**, and **hvPlot** for data preprocessing, clustering, and visualization.

---

## Data Files

| File Name                 | Description                                  |
|---------------------------|----------------------------------------------|
| `crypto_market_data.csv`  | Contains historical market data for various cryptocurrencies. |
| `Crypto_Clustering.ipynb` | Jupyter Notebook performing clustering analysis. |

---

## Features

1. **Data Preprocessing**:
   - Reads and cleans cryptocurrency market data.
   - Scales data using Standard Scaler for machine learning.

2. **K-Means Clustering**:
   - Groups cryptocurrencies into clusters based on numerical features.

3. **Dimensionality Reduction**:
   - Applies Principal Component Analysis (PCA) to reduce data dimensions and improve clustering visualizations.

4. **Interactive Visualizations**:
   - Uses **hvPlot** and **Matplotlib** to create scatter plots, cluster charts, and other visualizations.

---

## Installation

1. **Prerequisites**:
   - Python 3.x
   - Jupyter Notebook

2. **Setup**:
   - Clone this repository or download the project files.
     
   - Install dependencies (if needed):
     ```bash
     pip install -r requirements.txt
     ```

### Required Libraries
Install the required libraries using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```
---

## Results

### Key Observations

* Cryptocurrencies are grouped into distinct clusters based on their market performance.
* The dimensionality reduction via PCA effectively visualizes the clusters.
* Insights reveal patterns among cryptocurrencies with similar characteristics.

Visualizations:
* K-Means Clustering: Scatter plots showing clusters of cryptocurrencies.
* PCA Visualization: 2D representation of the clustered data post-PCA.
---

## Author

**Kendall Burkett**  
https://github.com/KendallBurkett?tab=repositories
 
kbz1987@icloud.com