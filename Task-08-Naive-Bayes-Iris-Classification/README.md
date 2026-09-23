# AIS Solution – AI Internship

## Task 8 – Iris Classification using Naive Bayes

### Objective

The objective of this task is to understand and implement different Naive Bayes classification algorithms using the Iris dataset.

### Dataset

The **Iris dataset** was used for classification.

The dataset contains four independent features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The dependent variable is the Iris species/class.

### Steps Performed

1. Loaded the Iris dataset using Scikit-learn.
2. Separated independent variables (`X`) and dependent variable (`y`).
3. Divided the dataset into training and testing data using an **80:20 train-test split**.
4. Studied Bayes' Theorem and the Naive Bayes classification formula.
5. Performed a simple hand calculation to understand probability-based classification.
6. Implemented **Gaussian Naive Bayes**.
7. Implemented **Bernoulli Naive Bayes**.
8. Implemented **Multinomial Naive Bayes**.
9. Trained all three models.
10. Predicted the test data.
11. Calculated the accuracy of each model.
12. Compared the model accuracies.
13. Created a bar chart for accuracy comparison.
14. Used Gaussian Naive Bayes to predict a new Iris sample.

### Naive Bayes Algorithms

#### 1. Gaussian Naive Bayes

Gaussian Naive Bayes is suitable for continuous numerical data.

It assumes that the features follow a Gaussian (normal) distribution within each class.

#### 2. Bernoulli Naive Bayes

Bernoulli Naive Bayes is designed for binary features such as:

* 0 / 1
* True / False
* Present / Absent

For this task, the Iris numerical features were converted into binary values before applying BernoulliNB.

#### 3. Multinomial Naive Bayes

Multinomial Naive Bayes is commonly used for discrete or count-based data.

It is widely used in:

* Text classification
* Spam detection
* Document classification

For this task, the Iris numerical features were converted into non-negative discrete values before applying MultinomialNB.

### Bayes' Theorem

The basic formula used by Naive Bayes is:

`P(C|X) = [P(X|C) × P(C)] / P(X)`

Where:

* `P(C|X)` = Posterior probability
* `P(X|C)` = Likelihood
* `P(C)` = Prior probability
* `P(X)` = Evidence

### Hand Calculation

A simple probability calculation was performed to understand how Naive Bayes selects the class with the highest probability.

Example:

`P(A) = 0.6`

`P(X|A) = 0.5`

Therefore:

`Score(A) = 0.6 × 0.5 = 0.30`

For another class:

`P(B) = 0.4`

`P(X|B) = 0.2`

Therefore:

`Score(B) = 0.4 × 0.2 = 0.08`

Since `0.30 > 0.08`, the observation is classified as Class A.

### Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook
* GitHub

### Files

* `Task-08-Naive-Bayes-Iris-Classification.ipynb`
* `README.md`

### Result

All three Naive Bayes algorithms were implemented successfully. Their predictions and accuracy scores were calculated and compared.

A new Iris sample was also given to the trained Gaussian Naive Bayes model, and the predicted species was:

**Setosa**

### Conclusion

This task provided practical experience with Naive Bayes classification and probability-based machine learning.

The task covered dataset preparation, train-test splitting, Bayes' theorem, hand calculation, implementation of GaussianNB, BernoulliNB and MultinomialNB, model training, prediction, accuracy evaluation, and visualization.

The task helped develop a basic understanding of how Naive Bayes algorithms can be applied to classification problems.
