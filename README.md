# Practical Lab 2: Multivariate Linear Regression, Non-Parametric Models and Cross-Validation

**Student Name:** Ali Cihan Ozdemir  
**Student ID:** 9091405

---

## Overview

This Jupyter Notebook contains a comprehensive machine learning analysis using the Scikit-Learn Diabetes dataset. The assignment covers:

- **Part 1**: Data Preparation & Exploratory Data Analysis (EDA)
- **Part 2**: Univariate Polynomial Regression Models
- **Part 3**: Multivariate Models (Polynomial, Decision Trees, kNN, Logistic Regression)

---

## Prerequisites

Before running this project, ensure you have the following installed:

### 1. Python (Version 3.8 or higher)

```bash
# Check Python version
python3 --version
```

### 2. Required Python Packages

Install all required packages using one of the following methods:

#### Method A: Using requirements.txt (Recommended)

```bash
# Clone the repository
git clone https://github.com/alicih4n/CSCN8010-Practical-Lab2.git
cd CSCN8010-Practical-Lab2

# Create virtual environment (optional but recommended)
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

#### Method B: Manual Installation

```bash
pip install numpy pandas matplotlib seaborn scikit-learn nbformat jupyter
```

---

## How to Run the Project

### Step 1: Open Jupyter Notebook

```bash
# From the project directory
jupyter notebook Practical_Lab_2.ipynb
```

### Step 2: Run Cells Sequentially

The notebook is organized into 48 cells. You can run them in two ways:

**Option A: Run all cells at once**
- Go to `Kernel` → `Restart & Run All`

**Option B: Run cells individually**
- Click on each cell and press `Shift + Enter` to execute

### Step 3: Expected Output

The notebook will generate:
- Data loading and dataset overview
- Exploratory Data Analysis visualizations:
  - Feature vs Target scatter plots
  - Target variable histogram
  - Correlation matrix heatmap
- Univariate polynomial regression results (degrees 0-5)
- Best model selection and evaluation
- Polynomial fit visualization
- Multivariate model comparison (8 models)
- Conclusions

### Step 4: Generated Files

The following image files will be created in your directory:
- `feature_vs_target_scatter.png`
- `target_histogram.png`
- `correlation_heatmap.png`
- `univariate_polynomial_fit.png`

---

## Project Structure

```
CSCN8010-Practical-Lab2/
├── Practical_Lab_2.ipynb    # Main Jupyter Notebook
├── README.md                # This file
├── requirements.txt         # Python dependencies
├── .gitignore              # Git ignore file
├── correlation_heatmap.png # Generated visualization
├── feature_vs_target_scatter.png
├── target_histogram.png
└── univariate_polynomial_fit.png
```

---

## Dataset Information

- **Source**: `sklearn.datasets.load_diabetes(as_frame=True)`
- **Instances**: 442 samples
- **Features**: 10 numeric predictive values (age, sex, bmi, bp, s1-s6)
- **Target**: Disease progression one year after baseline (integer 25-346)
- **Note**: Features are already mean-centered and scaled

---

## Key Results Summary

### Part 2 - Univariate Models
- Best model: Polynomial Degree X
- Test R²: ~X%
- Uses only BMI feature to predict disease progression

### Part 3 - Multivariate Models
- 8 models evaluated
- Best regression model: [Model Name]
- Logistic Regression (binary classification): ~X% accuracy

---

## Troubleshooting

### Issue: ModuleNotFoundError
**Solution:** Run `pip install -r requirements.txt`

### Issue: Jupyter not found
**Solution:** Run `pip install jupyter`

### Issue: Graphs not displaying
**Solution:** Add `%matplotlib inline` at the top of code cells

---

## Author

- **Name:** Ali Cihan Ozdemir
- **Student ID:** 9091405
- **Course:** CSCN8010 - Machine Learning Fundamentals
- **Institution:** Conestoga College

---

## License

This project is for educational purposes.
