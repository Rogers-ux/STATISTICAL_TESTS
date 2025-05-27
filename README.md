# 📊 Statistical Tests on Sales & Customer Segments Dataset

This project showcases the use of key **statistical hypothesis tests** on a real-world sales dataset. It is ideal for data analysts, statisticians, or students who want to understand when and how to apply different statistical tests using Python.

## 📁 Dataset
The dataset used (`Sales_without_NaNs_v1.3.csv`) contains information on customer segments, sales before and after a campaign, and whether customers belonged to a control or treatment group.

## 🧪 Statistical Tests Performed
The notebook performs the following statistical tests based on the data and assumptions:
- ✅ **Independent Samples T-Test**
- ✅ **Welch's T-Test**
- ✅ **Mann-Whitney U Test**
- ✅ **Wilcoxon Signed-Rank Test**
- ✅ **Chisquare test**

## 🔍 Workflow Overview
1. **Load and sample the dataset**
2. **Group data by customer segment**
3. **Check test assumptions**:
   - Normality (Shapiro-Wilk test or skip using CLT if n > 30)
   - Homogeneity of variances (Levene’s test)
4. **Select and perform the appropriate test**
5. **Interpret and display the results**

## 📌 Key Libraries Used
- `pandas` for data manipulation
- `scipy.stats` for statistical tests

## 🧠 What You’ll Learn
- When to use parametric vs non-parametric tests
- How to check assumptions before applying a test
- How to interpret test statistics and p-values

## 📈 Example Use Case
> "Is there a significant difference in pre-campaign sales between the control and treatment groups across different customer segments?"

This notebook provides the code and interpretation to answer questions like this using real data.

---

## 🚀 Get Started
Clone the repo and run the notebook in Jupyter or Kaggle:
```bash
git clone https://github.com/yourusername/statistical-tests-sales.git
