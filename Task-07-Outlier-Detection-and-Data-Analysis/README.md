# AIS Solution – AI Internship

## Task 7 – Data Analysis / AI-ML

### Topic

**Outlier Detection and Data Preprocessing**

### Objective

The objective of this task is to understand and implement different techniques for detecting outliers, standardizing data, and visualizing relationships between numerical features.

### Dataset

The **Iris dataset** was used for this task. The dataset was loaded using the Seaborn library.

### Techniques Implemented

#### 1. Box and Whisker Plot

A box and whisker plot was used to visualize the distribution of numerical features and identify possible outliers.

#### 2. Quartile Calculation

The following statistical values were calculated:

* Q1 – First Quartile (25th percentile)
* Q2 – Median (50th percentile)
* Q3 – Third Quartile (75th percentile)
* IQR – Interquartile Range

Formula:

`IQR = Q3 - Q1`

#### 3. Tukey's Method

Tukey's method was used to detect potential outliers using the IQR.

Formulas:

`Lower Bound = Q1 - 1.5 × IQR`

`Upper Bound = Q3 + 1.5 × IQR`

Values outside these boundaries were considered potential outliers.

#### 4. Z-Score

Z-score was calculated to determine how far a value is from the mean.

Formula:

`Z = (X - μ) / σ`

#### 5. Standardization

Standardization was performed using `StandardScaler`.

After standardization, the numerical features have approximately:

* Mean = 0
* Standard Deviation = 1

#### 6. Scatter Plot

A scatter plot was created to visualize the relationship between **Sepal Length** and **Petal Length**, with different colors representing Iris species.

### Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* GitHub

### File

`Task-07-Outlier-Detection-and-Data-Analysis.ipynb`

### Conclusion

This task provided practical experience with outlier detection, quartile calculation, Tukey's method, Z-score, standardization, and scatter plot visualization. These techniques are important steps in data preprocessing and are commonly used in Data Analysis and Machine Learning.
