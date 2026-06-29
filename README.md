# Code-Alpha_EDA

A comprehensive **Exploratory Data Analysis (EDA)** project performed on the famous **Titanic Dataset** using **Python**, **Pandas**, **NumPy**, **Seaborn**, **Matplotlib**, and **SciPy**.

The project explores passenger demographics, survival patterns, missing values, feature relationships, and performs a statistical hypothesis test to gain meaningful insights from the dataset.

---

## Project Objectives

* Load and inspect the Titanic dataset
* Perform data cleaning and missing value analysis
* Generate descriptive statistics
* Visualize important trends and relationships
* Analyze survival patterns
* Study feature correlations
* Perform hypothesis testing using an Independent T-Test
* Summarize key insights

---

## Dataset

This project uses the **Titanic dataset** available directly from the Seaborn library.

```python
import seaborn as sns
df = sns.load_dataset("titanic")
```

No external dataset download is required.

---

## Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

---

## Exploratory Analysis

The project performs the following analyses:

### 1. Dataset Overview

* Dataset shape
* Data types
* First five records

### 2. Descriptive Statistics

* Numerical summary
* Categorical summary

### 3. Missing Value Analysis

* Missing value count
* Missing percentage for each column

### 4. Data Visualizations

The following visualizations are generated:

* Survival Count
* Age Distribution
* Survival by Gender
* Survival by Passenger Class
* Fare Distribution (Log Scale)
* Correlation Heatmap

All visualizations are saved as:

```text
eda_titanic.png
```

---

## Statistical Analysis

An **Independent Two-Sample T-Test** is performed to determine whether there is a statistically significant difference in passenger age between survivors and non-survivors.

### Hypotheses

**Null Hypothesis (H₀):**

There is no significant difference in age between survivors and non-survivors.

**Alternative Hypothesis (H₁):**

There is a significant difference in age between survivors and non-survivors.

The project reports:

* T-statistic
* P-value
* Statistical conclusion

---

## Key Insights Generated

The script automatically calculates:

* Overall Survival Rate
* Female Survival Rate
* Male Survival Rate
* Median Age of Survivors
* Median Age of Non-Survivors

---

## Project Structure

```text
Code-Alpha_EDA/
│
├── Code Alpha EDA (TASK 2).py    # Main Python script
├── eda_titanic.png               # Generated visualization dashboard
├── README.md                     # Project documentation
└── requirements.txt              # Required Python libraries (optional)
```

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/AishaDataScientist/Code-Alpha_EDA.git
```

### 2. Navigate to the project folder

```bash
cd Code-Alpha_EDA
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scipy
```

### 4. Run the project

```bash
python "Code Alpha EDA (TASK 2).py"
```

---

## Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scipy
```

Or install them using:

```bash
pip install -r requirements.txt
```

---

## Output

The script generates:

* Console summary of the dataset
* Descriptive statistics
* Missing value analysis
* Statistical test results
* Key analytical insights
* Visualization dashboard saved as:

```text
eda_titanic.png
```

---

## Learning Outcomes

This project demonstrates:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Data Cleaning
* Missing Value Analysis
* Correlation Analysis
* Statistical Hypothesis Testing
* Data Interpretation
* Python Data Science Workflow

---

## Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork this repository and submit a pull request.

---

---

## Author

 **Aisha Arif**


GitHub: https://github.com/AishaDataScientist

---

###  If you found this project useful, consider giving it a star on GitHub!
