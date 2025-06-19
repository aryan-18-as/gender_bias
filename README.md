# 📘 Gender Bias in Hiring and Promotions – Data Science & Dashboard Project

## 🧾 Overview

This end-to-end project investigates gender bias in promotion and salary decisions using a synthetic HR dataset. Despite similar experience and performance, female employees in the dataset were promoted significantly less than males. The project uses statistical and machine learning techniques to detect these disparities and presents insights through a professional Power BI dashboard and interactive storytelling notebook.

---

## 🎯 Project Objectives

- Quantify gender-based disparities in promotion and compensation
- Use machine learning to model promotion outcomes
- Explain model behavior and feature importance
- Provide actionable insights to promote fairness in HR practices
- Communicate findings through visual storytelling and dashboard

---

## 📁 Project Structure

| File / Folder                                     | Description                                          |
|----------------------------------                 |------------------------------------------------------|
| `gender_bias_hr_dataset.csv`                      | Cleaned HR dataset used for analysis and dashboard   |
| `Gender_Bias_Job_Promotion.ipynb`                 | Google Colab notebook with full EDA & ML pipeline |
| `Gender_Bias_Job_Promotion.html`                  | Google Colab notebook with full EDA & ML pipeline in html form  |
| `Gender_Bias_Job_Promotion_Storytelling.ipynb`    | Notebook with polished visual storytelling + insights|
| `Gender_Bias_Job_Promotion_Storytelling.html`     | Notebook with polished visual storytelling + insights in html form |
| `Gender_Bias_PowerBI.pbix`                        | Final Power BI dashboard file                        |
| `Gender_Bias_Final_Report.pdf`                    | Complete project report with visuals & conclusions   |
| `README.md`                                       | Project overview and documentation (this file)       |

---

## 🔬 Analysis Breakdown

### 1. Problem Framing & Hypothesis
- **Null Hypothesis:** Gender has no effect on promotions or salary  
- **Alternative Hypothesis:** Gender significantly impacts outcomes

### 2. Descriptive & Diagnostic Analysis
- Promotion rate for females ~50% lower than males
- Salary gaps persist despite similar experience levels
- Performance ratings are equally distributed

### 3. Predictive Modeling
- Model: Random Forest Classifier (~82% accuracy)
- Features: Gender, Experience, Salary, Performance
- Gender was a top predictor → confirms embedded bias

### 4. Storytelling with Visuals
- Salary & promotion charts, experience vs. promotion scatter
- Annotated insights in markdown and Power BI visuals

### 5. Dashboard (Power BI)
- KPI cards (promotion rates, avg salary by gender)
- Interactive charts & filters (gender, department, role, performance)
- Actionable takeaways for HR & decision-makers

---

## 💡 Key Insights

- Female employees are promoted significantly less than males at equivalent performance levels  
- Salary inequality exists across roles and departments  
- Predictive model confirms gender’s influence, even when it shouldn't

---

## ✅ Recommendations

- Remove gender from predictive models
- Implement blind review in promotion decisions
- Standardize performance evaluation criteria
- Conduct routine fairness audits in HR systems
- Train managers on unconscious bias and equity

---

## 🛠️ Tools & Libraries

- Python, Pandas, Matplotlib, Seaborn, Scikit-learn
- Google Colab
- Power BI (for dashboard)
- Markdown for documentation

---

## 📌 Author

**Aryan Saxena**  
🚀 Data Analyst | SQL • Python • Power BI • Machine Learning | Transforming Data into Strategic Insights | AI & Analytics Enthusiast
📫 [LinkedIn](www.linkedin.com/in/aryan-saxena-615318309) | 🌐 [Portfolio](https://your-portfolio.com)

---

> 📢 *This project is ideal for showcasing ethical AI, fairness in machine learning, HR analytics, and real-world storytelling using data.*
