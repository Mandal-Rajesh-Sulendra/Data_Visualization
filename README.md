# 📊 Student Performance EDA & Data Visualization

## 📌 Project Overview

This project focuses on understanding student performance using Exploratory Data Analysis (EDA). The main idea is to take a simple dataset, clean it properly, and then use different visualization techniques to discover meaningful patterns.

Instead of just looking at numbers, this project helps in **seeing the data visually**, which makes it much easier to understand trends like how study hours or attendance affect final scores.

---

## 🎯 Objective

* To clean and prepare raw data
* To explore relationships between different variables
* To apply basic visualization techniques
* To understand how data visualization improves decision-making

---

## 📁 Dataset Details

The dataset used in this project is a **manually created (synthetic) student dataset**. It includes:

* Student ID
* Gender
* Study Hours
* Attendance (%)
* Previous Score
* Final Score

Additionally, a new column called **Result (Pass/Fail)** is created during analysis.

---

## 🧹 Data Cleaning

Before analysis, the dataset is cleaned to ensure accuracy:

* Missing values are handled using mean values
* Data types are checked and corrected if needed
* A new column (`Result`) is created based on final scores

This step is important because clean data leads to better and more reliable insights.

---

## 📊 Visualizations Used

Different types of visualizations are used to analyze the dataset:

* **Bar Chart** → To compare gender distribution
* **Histogram** → To understand study hours distribution
* **Box Plot** → To detect spread and outliers in scores
* **Scatter Plot** → To observe relationship between study hours and performance
* **Heatmap** → To find correlation between variables

These visuals help in quickly identifying patterns that are hard to see in raw data.

---

## 🔍 Key Insights

* Students who study more tend to score higher
* Attendance has a positive impact on performance
* Previous scores are a strong indicator of final results
* No major outliers were found in the dataset

---

## ⚙️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 How to Run the Project

1. Open Google Colab or Jupyter Notebook
2. Copy and paste the provided code
3. Run all cells step by step
4. View the generated graphs and outputs

(Optional)
You can also upload the dataset CSV file if you saved it separately.

---

## 📌 Conclusion

This project shows how even a simple dataset can provide useful insights when proper cleaning and visualization techniques are applied. It highlights the importance of EDA as a first step in any data analysis process.

---

## 🙌 Final Note

This project is beginner-friendly and designed to build a strong foundation in data analysis and visualization. It can be extended further by using larger datasets or interactive tools like Plotly.
