# 🎓 Student Performance Analytics

## 📌 Project Overview

Student Performance Analytics is a data analysis project that uses Python to explore students' academic performance and identify patterns associated with their grades, study habits, absences, family background, and extracurricular activities.

The project uses Exploratory Data Analysis (EDA) to transform educational data into meaningful insights through statistical analysis and data visualization.

## 🎯 Project Objectives

- Understand the structure and characteristics of the student dataset.
- Check for missing values, duplicate records, and potential data quality issues.
- Analyze the distribution of students' final grades.
- Investigate the relationship between study time and academic performance.
- Explore the impact of absences on students' grades.
- Examine parental education and family-related factors.
- Analyze the relationship between previous failures and academic performance.
- Compare performance based on gender and extracurricular activities.
- Identify correlations between academic variables.
- Detect unusually high or low performance using outlier analysis.
- Provide data-driven recommendations to support student learning.

## 📊 Dataset Information

This project uses the **UCI Student Performance Dataset**, specifically the Mathematics dataset (`student-mat.csv`).

The dataset contains student demographic, social, family, and academic information collected from secondary school students.

### Important Variables

| Variable | Description |
|---|---|
| `school` | Student's school |
| `sex` | Student's gender |
| `age` | Student's age |
| `studytime` | Weekly study-time category |
| `absences` | Number of school absences |
| `Medu` | Mother's education level |
| `Fedu` | Father's education level |
| `failures` | Number of previous class failures |
| `activities` | Participation in extracurricular activities |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade |

The final grade (`G3`) is the primary variable used to examine academic performance.

**Original dataset:** https://archive.ics.uci.edu/dataset/320/student+performance

## 🛠️ Technologies Used

- **Python** – Data analysis and programming
- **Pandas** – Data loading, cleaning, and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical plots and correlation heatmaps
- **Jupyter Notebook** – Interactive analysis and documentation

## 🔍 Exploratory Data Analysis Workflow

### 1. Data Loading and Inspection
- Load the dataset into a Pandas DataFrame.
- Inspect the number of rows and columns.
- Examine column names, data types, and summary information.

### 2. Data Cleaning
- Check for missing values.
- Identify duplicate records.
- Review data types and potential inconsistencies.
- Validate the dataset before analysis.

### 3. Descriptive Statistics
- Calculate mean, median, standard deviation, minimum, and maximum.
- Understand the distribution and variability of numerical variables.
- Summarize categorical variables.

### 4. Grade Distribution Analysis
- Examine the distribution of final grades (`G3`).
- Use histograms and other suitable plots to identify common performance ranges.
- Explore variation in academic outcomes.

### 5. Study Time and Academic Performance
- Compare study-time categories with final grades.
- Investigate whether greater study time is associated with better performance.

### 6. Absences and Academic Performance
- Analyze the distribution of student absences.
- Explore the relationship between absences and final grades.
- Identify potential patterns between attendance-related behavior and academic outcomes.

### 7. Family Background and Previous Performance
- Examine parental education levels.
- Investigate previous class failures and their relationship with final grades.
- Explore the relationship between earlier grades (`G1`, `G2`) and final grades (`G3`).

### 8. Gender and Extracurricular Activities
- Compare grade distributions across gender groups.
- Examine performance differences between students participating and not participating in extracurricular activities.

### 9. Correlation Analysis
- Calculate correlations between relevant numerical variables.
- Use a correlation heatmap to visualize relationships.
- Examine the relationships among `G1`, `G2`, `G3`, study time, absences, and previous failures.

### 10. Outlier Detection
- Apply the Interquartile Range (IQR) method to identify potential outliers in numerical variables.
- Examine unusually high or low values.
- Interpret outliers in context rather than automatically treating them as errors.

## 📈 Visualizations

The notebook includes visualizations designed to communicate the results of the analysis, such as:

- Histograms of final grades.
- Bar charts comparing academic performance across categories.
- Box plots for examining grade variability and potential outliers.
- Scatter plots for exploring relationships between grades and other numerical variables.
- Correlation heatmaps for understanding relationships among numerical features.

The plots help make patterns in student performance easier to interpret.

## 💡 Key Areas of Investigation

The analysis focuses on the following questions:

1. What is the distribution of students' final grades?
2. How is study time related to academic performance?
3. Is there a relationship between absences and final grades?
4. How are parental education levels associated with student performance?
5. How do previous class failures relate to final grades?
6. What relationship exists between first-period, second-period, and final grades?
7. Are there differences in performance across gender groups?
8. Is participation in extracurricular activities associated with academic outcomes?
9. Which numerical variables show stronger correlations with final grades?
10. Are there students with unusually high or low performance?

The answers are explored through descriptive statistics, visualizations, and correlation analysis in the notebook.

## 🚀 How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, or use an environment such as Google Colab.

### Step 1: Clone the Repository

```bash
git clone https://github.com/sujithra2505/Student_Performance_Analytics.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Student_Performance_Analytics
```

### Step 3: Install the Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Open the Notebook

```bash
jupyter notebook Student_Performance_Analytics.ipynb
```

### Step 5: Run the Analysis

Run the notebook cells sequentially, from top to bottom, to reproduce the data inspection, analysis, and visualizations.

Ensure that `student-mat.csv` is available at the file path specified in the notebook.

## 📁 Project Structure

```text
Student_Performance_Analytics/
│
├── Student_Performance_Analytics.ipynb
├── student-mat.csv
├── README.md
└── [Other project files, if included]
```

The structure above shows the main project files. Additional reports, presentations, datasets, or supporting files may also be included in the repository.

## ⚠️ Limitations

- The analysis focuses on the Mathematics dataset and may not represent all subjects or student populations.
- Observed relationships do not establish causation.
- Correlation does not necessarily mean that one variable directly influences another.
- Outlier detection identifies unusual observations but does not automatically establish that they are errors.
- Results may be affected by the dataset's size, scope, and the variables available.

## 🏁 Conclusion

This project demonstrates how exploratory data analysis can be used to understand academic performance and investigate factors associated with student grades.

By combining data cleaning, descriptive statistics, correlation analysis, outlier detection, and visualizations, the project provides a structured approach to analyzing educational data and generating evidence-based insights.

## 👩‍💻 Author

**Sujithra C. S.**

GitHub: [@sujithra2505](https://github.com/sujithra2505)

---

⭐ If you find this project useful, consider giving the repository a star.
