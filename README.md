# 📊 Survey Data Visualization Project

This project is part of the **RISE Internship Program by Tamizhan Skills** under the **Data Science & Analytics** domain. The aim is to explore survey results and create engaging visual summaries that convey key insights clearly and effectively.

---

## 🔍 Project Objective

To use a structured survey dataset and develop visualizations that highlight user preferences, satisfaction levels, and behavioral patterns — ultimately aiding data-driven decision-making.

---

## 📝 Dataset Description

The dataset (`survey_data_project8.csv`) contains 30 responses with the following fields:

| Column Name         | Description                                        |
|---------------------|----------------------------------------------------|
| Respondent ID       | Unique ID for each respondent                      |
| Age                 | Age of the respondent                              |
| Gender              | Gender (Male, Female, Other)                       |
| Preferred Feature   | Most liked product feature (UI, Speed, etc.)       |
| Satisfaction        | Rating from 1 to 5                                 |
| Time Spent (hrs)    | Time spent on platform weekly                      |
| Feedback Rating     | Overall experience rating (1 to 10)                |
| Would Recommend     | Whether user would recommend the platform (Yes/No) |

---

## 📈 Tools & Libraries Used

- **Python**
- **Pandas** – Data loading & manipulation  
- **Matplotlib** – Basic plotting  
- **Seaborn** – Enhanced statistical visualizations  
- **Plotly** – Interactive dashboards (optional)

---

## 📊 Visualizations Created

- ✅ Bar Chart – Gender distribution, feature preference  
- ✅ Pie Chart – Preferred features  
- ✅ Heatmap – Correlation between numeric features  
- ✅ Histogram – Satisfaction vs Gender using Plotly  
- ✅ (Optional) Interactive Dashboard using Plotly or Streamlit

---

## 🧠 Key Insights

- Most users preferred the `UI` and `Speed` features.
- Female users showed slightly higher satisfaction and feedback ratings.
- A strong correlation exists between **Time Spent** and **Feedback Rating**.
- Majority of users would recommend the platform.

---

## 📁 Project Files

| File Name                       | Description                              |
|--------------------------------|------------------------------------------|
| `survey_data_project8.csv`     | The raw survey dataset                   |
| `Survey Data Visualization.ipynb` | Jupyter Notebook with all code & charts |
| `README.md`                    | This project overview                    |

---

## 📜 How to Run the Project

1. Clone the repo
2. Open the notebook in Jupyter or VS Code
3. Install required libraries if not already installed:
   ```bash
   pip install pandas matplotlib seaborn plotly
