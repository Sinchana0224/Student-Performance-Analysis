# 📊 Student Performance Analysis using Statistics

This project analyzes student academic performance using **descriptive and inferential statistics** to uncover how different factors like gender, parental education, lunch type, and test preparation affect scores in Math, Reading, and Writing.

---

## 🧠 Objective

To apply core statistical techniques on real-world education data to:
- Explore trends and patterns in student scores
- Understand which demographic or behavioral factors influence performance
- Perform hypothesis testing to validate assumptions

---

## 📁 Dataset

We used the [Students Performance in Exams Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) from Kaggle, which includes:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math, Reading, and Writing Scores

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy, Statsmodels
- Jupyter Notebook / Google Colab

---

## 🔍 Exploratory Data Analysis (EDA)

### ✅ Descriptive Statistics
- Calculated Mean, Median, Mode, Range, Standard Deviation, and IQR for scores
- Cleaned and standardized column names for analysis

### ✅ Visualizations

Here are some key plots used to support the analysis:

| 📷 Visualization | Description |
|------------------|-------------|
| ![Correlation Matrix](images/correlation_matrix.png) | Strong **positive correlation** among Math, Reading, and Writing scores. |
| ![Math Score Distribution](images/Distribution_of_mathscores.png) | **Math score distribution** shows a slight right skew, peaking around 65–75. |
| ![Dataset Preview](images/dataset.png) | Cleaned dataset preview after column renaming and preprocessing. |
| ![Math Scores by Gender](images/maths_scoresbygender.png) | Slight difference in Math scores between **male and female students** shown using a boxplot. |


---

## 📈 Inferential Statistics

### 1️⃣ Hypothesis Testing

- **Test Preparation vs Math Scores**  
  ✅ Students who completed the prep course performed **significantly better** in Math.  
  ✔️ _t-test p-value < 0.05_

- **Gender vs Reading Scores**  
  🚫 No statistically significant difference found.  
  ✔️ _t-test p-value > 0.05_

---

## 🧾 Key Insights

- ✅ **Test preparation** improves performance in all subjects
- ✅ **Parental education** moderately impacts academic results
- ✅ **Gender** does not significantly affect final scores
- ✅ **High correlation** exists between all three subject scores
- ✅ **Lunch type** reflects socioeconomic status influencing performance

---

## 🗂️ Project Structure

Student-Performance-Analysis/
├── student_performance.csv
├── Student_Performance_Analysis.ipynb
├── README.md
└── images/
├── correlation_matrix.png
├── Distribution_ofmathscores.png
├── dataset.png
└── maths_scoresbygender.png



---

## 🔗 Author & Credits

Developed by Sinchana P as part of placement-focused learning in Data Science and Statistics.  
Dataset sourced from Kaggle.



