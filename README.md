# Breast Cancer Survival Analysis using Exploratory Data Analysis (EDA)

## Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the **Haberman Breast Cancer Survival Dataset** to identify meaningful patterns affecting patient survival after surgery. The analysis focuses on understanding feature distributions, relationships between variables, class imbalance, and extracting actionable insights using statistical visualization techniques.

The project demonstrates practical data analysis skills commonly required in Data Science and Machine Learning roles, including:

* Data preprocessing
* Univariate and bivariate analysis
* Statistical visualization
* Insight extraction
* Interpretation of medical datasets
* Communicating findings effectively

---

## Problem Statement

The objective of this project is to analyze clinical patient data and determine how factors such as:

* Patient age
* Year of operation
* Number of auxiliary lymph nodes detected

influence survival outcomes after breast cancer surgery.

The dataset classifies patients into:

* **Survived 5 years or longer**
* **Did not survive beyond 5 years**



## Dataset Information

### Dataset: Haberman Survival Dataset

The dataset contains records of patients who underwent surgery for breast cancer.

### Features

| Feature         | Description                                       |
| --------------- | ------------------------------------------------- |
| Age             | Age of patient at the time of operation           |
| Operation Year  | Year of surgery                                   |
| Auxiliary Nodes | Number of positive auxiliary lymph nodes detected |
| Survival Status | Survival outcome class                            |

### Target Variable

| Class | Meaning                            |
| ----- | ---------------------------------- |
| 1     | Patient survived 5 years or longer |
| 2     | Patient died within 5 years        |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook



## Exploratory Data Analysis Performed

### 1. Data Understanding

* Dataset shape analysis
* Feature inspection
* Class distribution analysis
* Checking dataset balance

### 2. Univariate Analysis

Performed distribution analysis using:

* Histograms
* PDF (Probability Density Function)
* CDF (Cumulative Distribution Function)
* Distplots

### 3. Bivariate Analysis

Analyzed feature relationships using:

* 2D Scatter Plots
* Pair Plots
* Facet Grids

### 4. Statistical Analysis

Computed:

* Mean
* Median
* Standard Deviation
* Percentiles
* Median Absolute Deviation (MAD)

### 5. Box Plots and Violin Plots

Used for understanding:

* Spread of data
* Outliers
* Distribution overlap
* Survival trends



## Key Insights

### Major Observations

* Patients with fewer auxiliary lymph nodes had significantly higher survival rates.
* The dataset is imbalanced, with more patients surviving beyond 5 years.
* Age alone was not sufficient to clearly separate survival classes.
* Auxiliary lymph nodes provided the strongest separation between survival groups.
* Significant overlap exists between classes, indicating that survival prediction is a complex problem.

---

## Visualization Highlights

The project includes multiple visualizations such as:

* Pair plots for multidimensional relationship analysis
* Distribution plots for survival comparison
* Box plots and violin plots for statistical spread analysis
* Scatter plots for feature interaction understanding

These visualizations help convert raw medical data into interpretable insights.

---

## Skills Demonstrated

This project highlights the following industry-relevant skills:

### Data Analysis

* Data cleaning and preprocessing
* Exploratory data analysis
* Statistical reasoning
* Pattern recognition

### Visualization

* Advanced visualization using Seaborn and Matplotlib
* Comparative analysis
* Data storytelling

### Machine Learning Foundations

* Understanding class imbalance
* Feature importance interpretation
* Data understanding before model building

### Software & Tools

* Python programming
* Jupyter Notebook workflow
* Analytical thinking
* Documentation and reporting

---

## Project Structure

```bash
├── eda.ipynb
├── haberman.csv
├── README.md
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <repository-link>
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the Notebook

Run:

```bash
eda.ipynb
```

---

## Future Improvements

Possible enhancements for this project include:

* Building machine learning classification models
* Applying feature engineering
* Handling class imbalance using SMOTE
* Hyperparameter tuning
* Model deployment using Streamlit or Flask

---

## Why This Project Matters

This project demonstrates the ability to:

* Analyze real-world healthcare datasets
* Extract business and medical insights from raw data
* Communicate analytical findings effectively
* Apply core data science concepts used in industry

It reflects practical problem-solving and analytical thinking skills expected from aspiring Data Scientists and Machine Learning Engineers.

---

## Author

**Ankita Agrawal**

Aspiring Data Scientist | Machine Learning Enthusiast | Open Source Contributor

---

## License

This project is open-source and available for educational and learning purposes.


