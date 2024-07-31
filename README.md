# Healthcare Inpatient Data Anomaly Analysis

## Overview

The purpose of this project is to conduct anomaly analysis on healthcare/inpatient data. This analysis aims to identify and understand unusual patterns or outliers that could indicate potential issues or opportunities for improvement in healthcare delivery, cost management, and patient outcomes. The objective is to perform exhaustive Exploratory Data Analysis (EDA) on inpatient data and provide business insights for each feature.

## Methods

The following methods are used for anomaly detection in this project:
- Histogram-based Outlier Score (HBOS)
- Empirical Cumulative Distribution Function Outlier Detection (ECOD)
- Autoencoder
- Isolation Forest (Iforest)
- K-Nearest Neighbors (KNN)
- Principal Component Analysis (PCA)

## Table of Contents

- **Section 1: Data Preparation**
- **Section 2: EDA**
  - 2.1 Distribution of Variables
    - 2.1.1 Distributions of Avg. Payments
    - 2.1.2 Distributions of Charges and Payments
    - 2.1.3 DRG Frequency
    - 2.1.4 Distributions of Charges and Payments by State
- **Section 3: Feature Engineering**
  - 3.1 Average Medicare Payments
    - 3.1.1 By DRG
    - 3.1.2 Per DRG by State
    - 3.1.3 Per DRG by State & City
    - 3.1.4 Per DRG by Zip Code
  - 3.2 Average Total Payments
    - 3.2.1 Per DRG by State
    - 3.2.2 Per DRG by State & City
    - 3.2.3 Per DRG by Zip Code
  - 3.3 Average Out-Of-Pocket Payments
    - 3.3.1 Per DRG by State
    - 3.3.2 Per DRG by State & City
    - 3.3.3 Per DRG by Zip Code
- **Section 4: Model Creation**
- **Section 5: Model Comparison**

### Prerequisites

- Python 3.7+
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, pyod
