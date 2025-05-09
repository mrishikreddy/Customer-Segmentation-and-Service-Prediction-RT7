# Customer Segmentation and Service Prediction

This project uses the K-Nearest Neighbors (KNN) algorithm to segment telecom customers and predict their service category based on demographic and usage data. It helps in understanding customer behavior for potential targeted marketing strategies.

---

## Table of Contents

- [Installation Instructions](#installation-instructions)  
- [Usage](#usage)  
- [Features](#features) 

---

## Installation Instructions

### Prerequisites

- Python 3.x
- Jupyter Notebook or any Python IDE
- The following Python libraries:
  - `scikit-learn==0.23.1`
  - `pandas`
  - `numpy`
  - `matplotlib`

### Setup Steps

1. Clone or download this repository.
2. Install dependencies (if not already installed):
   ```bash
   pip install scikit-learn==0.23.1 pandas numpy matplotlib
   ```
3. Open the Jupyter Notebook or `.py` file.
4. Run the code cells or script step by step.

---

## Usage

The code:

- Loads telecom customer data from a CSV file.
- Visualizes distributions (e.g., income histogram).
- Preprocesses and normalizes data.
- Splits it into training and testing sets.
- Trains a KNN model and evaluates accuracy for different `k` values.
- Visualizes the effect of `k` on model performance.

### Sample Output

```bash
Train set Accuracy:  0.5475
Test set Accuracy:   0.32
The best accuracy was with 0.34 with k= 9
```

The plotted graph shows how accuracy changes with different `k` values and includes confidence intervals.

---

## Features

- Customer segmentation into 4 categories using the `custcat` label.
- Data standardization for better KNN performance.
- Performance tuning by testing multiple values of `k`.
- Visual plot of model accuracy with standard deviation bands.
- Works with real-world customer data.
