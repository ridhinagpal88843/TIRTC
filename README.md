# Healthcare Analytics for Doctor Visits

## 📌 Project Overview

This project focuses on analyzing healthcare data to understand the factors influencing the frequency of doctor visits. The analysis explores patient demographics, socioeconomic factors, and health-related information to identify meaningful patterns in healthcare utilization.

The project was developed as part of the **VOIS Edunet Data Analyst Internship** using Python and various data analysis and visualization libraries.

---

## 🎯 Problem Statement

To analyze patient healthcare data and identify demographic, socioeconomic, and health-related factors influencing the frequency of doctor visits.

The project aims to answer questions such as:

- How does illness severity affect doctor visits?
- Do doctor visits vary by gender?
- Is there any relationship between age and income?
- What patterns can be observed in patient healthcare utilization?

---

## 📊 Dataset

The dataset contains **5,190 patient records and 13 features** related to healthcare and demographic information.

The analysis focuses on variables such as:

- Age
- Gender
- Income
- Illness Score
- Doctor Visits
- Other patient-related attributes

The dataset was checked for missing values, data types, and basic statistical characteristics before performing the analysis.

---

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization

---

## 🔍 Methodology

### 1. Data Loading & Preparation
- Loaded the healthcare dataset using Pandas.
- Examined the dataset structure, dimensions, and data types.
- Checked for missing or null values.
- Generated descriptive statistics.

### 2. Exploratory Data Analysis

Performed different levels of analysis:

#### Univariate Analysis
Analyzed individual variables such as:
- Doctor Visits
- Age
- Gender

The doctor-visit distribution was found to be highly right-skewed, with most patients having zero or one doctor visit.

#### Bivariate Analysis
Studied relationships between:
- Gender and Doctor Visits
- Illness Score and Doctor Visits

A noticeable positive relationship was observed between illness score and doctor visits.

#### Multivariate Analysis
Analyzed:
- Age
- Income
- Gender
- Doctor Visits

using a combined visualization to identify demographic and healthcare patterns.

---

## 📈 Key Findings

- **Illness score has a strong positive relationship with doctor visits.**
  As the illness score increases, the average number of doctor visits also increases.

- Patients with higher illness scores tend to utilize healthcare services more frequently.

- **Female patients showed a higher average number of doctor visits** compared to male patients in the dataset.

- Doctor visits are highly concentrated around **zero and one visit**, resulting in a right-skewed distribution.

- Multivariate analysis helped identify relationships between age, income, gender, and healthcare utilization.

---

## 🎯 Project Objectives

- Understand patterns in patient doctor visits.
- Identify factors associated with healthcare utilization.
- Perform exploratory data analysis on healthcare data.
- Create meaningful visualizations to communicate insights.
- Demonstrate practical Python-based data analytics skills.

---

## 👥 End Users

The insights from this analysis can be useful for:

- Healthcare providers and doctors
- Hospital administrators
- Healthcare analysts
- Healthcare researchers
- Public health organizations

---

## 🚀 Future Scope

The project can be further extended by:

- Building a machine learning model to predict doctor visits.
- Performing feature correlation and statistical testing.
- Developing an interactive dashboard using Power BI or Tableau.
- Applying advanced predictive analytics.
- Using larger and more diverse healthcare datasets.

---

