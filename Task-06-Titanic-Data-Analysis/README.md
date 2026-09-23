# AIS Solution – AI Internship

## Task 6 – Titanic Data Analysis / AI-ML

### Objective

The objective of this task is to perform basic data analysis and preprocessing on the Titanic dataset and prepare categorical data for machine learning.

### Dataset

The Titanic dataset was loaded using the Seaborn library.

```python
import seaborn as sns

df = sns.load_dataset("titanic")
```

### Analysis Performed

The following dataset exploration operations were performed:

* `describe()` – Statistical summary
* `info()` – Dataset information and data types
* `shape` – Number of rows and columns
* `columns` – Display dataset column names

### Preprocessing

The following preprocessing techniques were applied:

* Checked missing values using `isnull().sum()`
* Handled missing values in the `age` column using the median
* Handled missing values in the `embarked` column using the mode
* Handled missing values in the `deck` column using `"Unknown"`
* Applied Label Encoding to the `sex` column

### Technologies Used

* Python
* Pandas
* Seaborn
* Scikit-learn
* Jupyter Notebook
* GitHub

### File

`Task-06-Titanic-Data-Analysis.ipynb`

### Conclusion

This task provided practical experience in exploring a real-world dataset, handling missing values, performing categorical data encoding, and preparing data for machine learning.
