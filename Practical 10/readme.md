🍷 Wine Dataset Analysis – Version 3 (Alternate Approach)

This project presents a different and unique analysis of the Wine Dataset using Python.
It includes descriptive statistics, visualizations, feature scaling, and PCA — all implemented using different features and plotting styles compared to earlier versions.

✅ Tasks Performed
1️⃣ Basic Statistics

Displayed data summary using:

df.describe()

2️⃣ Boxplot by Class Labels

Plotted total_phenols distribution across wine classes.

3️⃣ Scatterplot Using Two New Variables

Visualized the relationship between:

alcalinity_of_ash

magnesium

4️⃣ Covariance Matrix

Generated a heatmap using:

"cubehelix" colormap

different styling and layout

5️⃣ Data Scaling

Standardized all numerical features using:

StandardScaler()

6️⃣ Principal Component Analysis (PCA)

Reduced the dataset to two principal components and visualized class separation using:

“Dark2” palette

larger scatter points (s=85)

📂 Project Structure
Wine-Analysis-v3/
│
├── wine_analysis_v3.py
└── README.md

🔧 Installation

Use the following commands to set up the project:

git clone https://github.com/<your-username>/Wine-Analysis-v3.git
cd Wine-Analysis-v3
pip install numpy pandas matplotlib seaborn scikit-learn

▶️ How to Run
python wine_analysis_v3.py

📊 Outputs Generated

Summary statistics table

Boxplot of total phenols by class

Scatterplot of alcalinity_of_ash vs magnesium

Covariance matrix heatmap

Scaled dataframe preview

2-component PCA scatter plot

🧪 Libraries Used

pandas

numpy

seaborn

matplotlib

scikit-learn
