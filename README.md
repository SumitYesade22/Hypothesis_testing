# Hypothesis Testing in Python

A practical collection of Python Jupyter notebooks covering statistical hypothesis testing, non-parametric methods, correlation analysis, and statistical inference.

This repository demonstrates how to select appropriate statistical tests, evaluate their assumptions, interpret p-values, and draw conclusions from data.

## 📌 Overview

The project contains hands-on implementations of commonly used statistical tests, with explanations of their hypotheses, assumptions, calculations, and interpretation of results.

## 📂 Repository Structure

```text
Hypothesis_testing/
│
├── data/
│   ├── boat_vs_noise_audio_products.csv
│   ├── data.csv
│   ├── MSRCT_data.csv
│   └── smartphones.csv
│
├── notebooks/
│   ├── chi_sq_goodnessoffit_test.ipynb
│   ├── chi_sq_independence_test.ipynb
│   ├── friedman_test.ipynb
│   ├── independent_t_test.ipynb
│   ├── oneway_anova.ipynb
│   ├── Paired_T_test.ipynb
│   ├── repeated_measure_anova.ipynb
│   ├── spearman_rank_corr.ipynb
│   ├── T_test.ipynb
│   ├── two_way_anova.ipynb
│   ├── wilcoxon_signed_rank_test.ipynb
│   └── Z_test.ipynb
│
├── .gitignore
├── requirements.txt
└── README.md
```

## 📊 Statistical Tests Covered

### 1. Z-Test
- One-sample Z-test
- Two-sample Z-test for means
- Two-proportion Z-test
- Test statistics, p-values, critical values, and hypothesis decisions

### 2. T-Tests
- One-sample t-test
- Independent two-sample t-test
- Paired-sample t-test

### 3. ANOVA
- One-way ANOVA
- Two-way ANOVA
- Repeated-measures ANOVA

### 4. Non-Parametric Tests
- Wilcoxon signed-rank test
- Friedman test

### 5. Chi-Square Tests
- Chi-square goodness-of-fit test
- Chi-square test of independence

### 6. Correlation Analysis
- Spearman rank correlation
- Interpretation of correlation coefficients and statistical significance

## 🧠 Key Concepts

- Null and alternative hypotheses
- One-tailed and two-tailed hypothesis tests
- Significance level (\(\alpha\)) and p-values
- Test statistics and critical values
- Type I and Type II errors
- Statistical assumptions and their verification
- Parametric vs. non-parametric tests
- Normality, independence, and variance assumptions
- Effect size and interpretation of statistical results

## 🛠️ Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** NumPy, pandas, SciPy, Matplotlib, Seaborn, statsmodels

## ⚙️ Getting Started

### Prerequisites

- Python 3.10 or later
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SumitYesade22/Hypothesis_testing.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Hypothesis_testing
   ```

3. Create and activate a virtual environment:

   **Windows (PowerShell):**

   ```powershell
   python -m venv .venv
   .venv\Scripts\Activate.ps1
   ```

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Open the `notebooks/` directory and run the notebooks individually.

## 📖 Blog

Detailed explanations and additional insights related to hypothesis testing:

**Blog:** [https://medium.com/@sumityesade14/hypothesis-testing-from-scratch-a-complete-guide-for-data-science-5eb3ab401f2a?sharedUserId=sumityesade14](blog)

## 🎯 Objective

The objective of this repository is to build a practical understanding of statistical inference and hypothesis testing, with a focus on selecting the right statistical method, checking assumptions, and interpreting results correctly.

## 👨‍💻 Author

**Sumit Yesade**

- GitHub: [SumitYesade22](https://github.com/SumitYesade22)

---

If you find this repository useful, consider giving it a ⭐.
