# AI-ML-internship-task-1
The task explores the Iris dataset using pandas, matplotlib, and seaborn. It includes loading data, viewing structure, and performing visualizations like scatter plots, histograms, and box plots. Key insights show petal features clearly separate species, aiding future classification.
Here's a structured summary based on your Iris dataset analysis task:

---

## ✅ **○ Task Objective**

The objective of this task is to:

* Load and explore the **Iris dataset**.
* Perform **data analysis** using Pandas.
* Visualize data using **matplotlib** and **seaborn** to understand feature distributions, relationships, and outliers.

---

## 📂 **○ Dataset Used**

* **Name**: Iris Dataset
* **Source**: CSV file (`IRIS.csv`)
* **Features**:

  * `sepal_length`
  * `sepal_width`
  * `petal_length`
  * `petal_width`
  * `species` (target variable with 3 classes: *setosa*, *versicolor*, *virginica*)

---

## 🤖 **○ Models Applied**

No machine learning models were applied in this task — it focuses on **exploratory data analysis (EDA)** only.

If models were to be applied later, common options include:

* Logistic Regression
* Decision Trees
* K-Nearest Neighbors
* SVM
  (*But not part of this task*)

---

## 📊 **○ Key Results and Findings**

### 1. **Dataset Shape and Structure**

* Shape: `(150, 5)` – 150 rows and 5 columns.
* Columns: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`, `species`.

### 2. **Descriptive Statistics**

* Used `.describe()` and `.info()` to observe:

  * All numeric features are floats.
  * No missing values in the dataset.
  * The mean, min, and max values of features show good variation between features.

### 3. **Visual Insights**

* **Scatter Plot Matrix** (`sns.pairplot()`):

  * Clear clustering of species based on petal features.
  * `setosa` is linearly separable from the other two species.

* **Histograms**:

  * Features like `petal_length` and `petal_width` show multimodal distributions (one for each species).
  * `sepal_width` has a more normal-like distribution.

* **Box Plots**:

  * Help identify **outliers**, especially in `sepal_width`.
  * Distinct differences in medians and ranges across species, especially for `petal_length`.

---

Let me know if you want this as a **PDF or report file**, or if you want to extend it with machine learning models.
