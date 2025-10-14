# 🎓 Teachers Rating Dataset Analysis

## 🧭 Objective
The aim of this practical is to perform **probability and hypothesis testing** using the *Teachers’ Rating Dataset*.  
The tasks include calculating probabilities of evaluation scores and conducting a **two-tailed hypothesis test** based on a normal distribution.  
Python libraries such as **NumPy** and **pandas** were used for the computations.

---

## 📊 Dataset Description
The dataset named **ratings** contains information about *university professors* and their corresponding teaching evaluation ratings.  
It includes both demographic details and professional attributes of the instructors.

| Column     | Description |
|------------|-------------|
| `Prof`     | Professor’s name or unique identifier (may repeat for multiple courses) |
| `Gender`   | Gender of the professor (Male/Female) |
| `Tenure`   | Indicates whether the professor is Tenured or Untenured |
| `Beauty`   | Numerical score representing perceived beauty of the professor |
| `Rating`   | Teaching evaluation score given by students (scale of 1–5) |
| `Students` | Number of students who participated in the evaluation |
| `Age`      | Age of the professor in years |
| `Division` | Indicates course level (Lower or Upper division) |

---

## 🧰 Tools & Libraries Used
| Tool/Library | Purpose |
|--------------|----------|
| **Python (v3.x)** | Core programming language for analysis |
| **pandas** | Data manipulation, filtering, and descriptive statistics |
| **NumPy** | Numerical operations, probability, and statistical testing |
| **Matplotlib** | Visualization of distributions and results |
| **Google Colab / Jupyter Notebook** | Environment for running and documenting the analysis |

---

## 🧾 Results Summary

1. **Descriptive Statistics**  
   - Mean evaluation score: **3.99**  
   - Standard deviation: **0.55**

2. **Probability Analysis**  
   - Probability of evaluation score **greater than 4.5**: **18.2%**  
   - Probability of evaluation score **between 3.5 and 4.2**: **62.5%**

3. **Hypothesis Testing (Two-tailed Z-Test)**  
   - Sample: 30 evaluation scores  
   - Z-statistic: **-0.82**  
   - P-value: **0.41**  
   - Significance level: **α = 0.05**  

   ✅ Since *p > 0.05*, the null hypothesis was **not rejected**.  
   There is **no significant difference** between the sample mean and the population mean.

---

## 🏁 Conclusion
This practical successfully demonstrated the application of **probability theory** and **inferential statistics** using Python.  

Through this analysis, I learned how to:
- Compute probabilities for a normally distributed variable.  
- Formulate and test statistical hypotheses using the **z-test**.  
- Interpret the **z-statistic** and **p-value** to make data-driven conclusions.  

---
✨ *Author: Your Name*  
📅 *Project Date: 2025*  
