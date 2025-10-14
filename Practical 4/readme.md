# 🎓 Student Rating Dataset Analysis

## 🧭 Objective
The aim of this project is to analyze a *Student Rating Dataset* using Python libraries such as **NumPy**, **pandas**, and **Matplotlib**.  
The analysis includes performing statistical computations, visualizations, and interpretations of factors influencing teaching evaluations — such as **tenure status, age, gender, and minority representation**.

---

## 📊 Dataset Description
The dataset contains information about *university professors* and their *student evaluation ratings*.  
Each record represents one professor along with demographic and professional details.

| Column      | Description |
|-------------|-------------|
| `prof`      | Unique identifier for each professor |
| `age`       | Age of the professor in years |
| `gender`    | Gender of the professor (Male/Female) |
| `minority`  | Indicates whether the professor belongs to a visible minority group (Yes/No) |
| `tenure`    | Tenure status of the professor (Tenured/Not Tenured) |
| `eval`      | Evaluation score given by students (1–5 scale) |
| `students`  | Number of students who rated the professor |
| `beauty`    | Perceived beauty score of the professor (numerical rating) |
| `division`  | Course level taught by the professor (Lower or Upper division) |

---

## 🧰 Tools & Libraries Used
| Tool/Library | Purpose |
|--------------|----------|
| **Python (v3.x)** | Core programming language for analysis |
| **pandas** | Data loading, cleaning, and manipulation |
| **NumPy** | Numerical computations and statistics |
| **Matplotlib (Pyplot)** | Visualization of distributions and categorical variables |
| **Seaborn** | Enhanced data visualization with styling |
| **Google Colab / Jupyter Notebook** | Interactive coding environment |

---

## 🧾 Results Summary

### 1️⃣ Tenure Status and Visible Minority
- For professors identified as a **visible minority**, **65.6%** were tenured.  
- For professors **not** identified as a visible minority, **61.8%** were tenured.  

✅ Finding: The percentages are close, suggesting tenure status does not strongly differ by minority status in this dataset.

---

### 2️⃣ Age and Tenure
- **Tenured Professors** → Mean age: **52.3 years**, Std Dev: **11.0**  
- **Untenured Professors** → Mean age: **51.4 years**, Std Dev: **11.4**  

✅ Finding: Tenured professors are slightly older on average, which is expected since tenure is awarded after more years of service.

---

### 3️⃣ Visualizing the Age Distribution
- **Histogram** → Shows overall distribution of ages.  
- **Boxplot** → Compares age between tenured vs. untenured.  

📌 Finding: **Boxplot** is more effective for comparing across tenure groups.

---

### 4️⃣ Bar Charts for Categorical Data
- `pyplot.bar` → Creates **vertical bar charts**  
- `pyplot.barh` → Creates **horizontal bar charts**  

📊 A bar chart of professor **gender distribution** was plotted, showing counts for Male and Female professors.

---

### 5️⃣ Median Evaluation Score for Tenured Professors
- The **median evaluation score** for tenured professors is **3.25**.  

✅ This shows the central tendency of student evaluations among tenured faculty.

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/student-rating-analysis.git
   cd student-rating-analysis
