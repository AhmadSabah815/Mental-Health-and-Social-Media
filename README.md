# 🧠 Mental Health and Social Media Balance — Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange?logo=googlecolab)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 About the Dataset

This dataset explores the relationship between **social media usage** and **mental health indicators** across 500 users. It includes data on daily screen time, stress levels, sleep quality, happiness index, exercise habits, and platform preferences broken down by age and gender.

| Feature | Description |
|---|---|
| `User_ID` | Unique user identifier |
| `Age` | Age of the user |
| `Gender` | Male / Female / Other |
| `Daily_Screen_Time(hrs)` | Daily social media screen time in hours |
| `Sleep_Quality(1-10)` | Self-reported sleep quality score |
| `Stress_Level(1-10)` | Self-reported stress level score |
| `Days_Without_Social_Media` | Days per week user avoids social media |
| `Exercise_Frequency(week)` | Number of exercise days per week |
| `Social_Media_Platform` | Primary platform used (Facebook, Instagram, TikTok, LinkedIn, X, YouTube) |
| `Happiness_Index(1-10)` | Self-reported happiness score |

---

## 📊 Analysis Performed

The notebook covers the following:

1. **Library Imports** — pandas, numpy, matplotlib, seaborn
2. **Loading the Dataset** — CSV upload in Google Colab
3. **Basic Overview** — shape, dtypes, head/tail, describe, missing values
4. **Numeric Histograms** — distribution of all numeric features
5. **Gender Distribution** — counts and bar chart
6. **Age Analysis** — mean, std, histogram by gender
7. **Platform Analysis** — crosstab, pivot table, count plot by gender, stacked bar chart
8. **Screen Time Analysis** — stats, avg by platform, boxplot by gender
9. **Sleep Quality & Stress Level** — avg by platform bar charts
10. **Happiness Index** — avg by platform, scatter vs screen time
11. **Correlation Heatmap** — relationships between all numeric features
12. **Exercise & Social Media Detox** — frequency distributions
13. **Summary Table** — all metrics grouped by platform

---

## 🚀 How to Run on Google Colab

1. Go to [https://colab.research.google.com](https://colab.research.google.com)
2. Click **File → Upload notebook**
3. Upload `Mental_Health_Social_Media_Analysis.ipynb`
4. Run the first cell — it will prompt you to **upload the CSV file**
5. Upload `Mental_Health_and_Social_Media_Balance_Dataset.csv`
6. Click **Runtime → Run all** to execute the full analysis

---

## 📁 Repository Structure

```
📦 mental-health-social-media-analysis
 ┣ 📄 Mental_Health_and_Social_Media_Balance_Dataset.csv   ← Dataset
 ┣ 📓 Mental_Health_Social_Media_Analysis.ipynb            ← Colab Notebook
 ┗ 📄 README.md                                            ← This file
```

---

## 📈 Key Findings

- **500 users** across **6 platforms**: Facebook, Instagram, LinkedIn, TikTok, X (Twitter), YouTube
- **Average age**: ~33 years (std ≈ 9.96)
- **TikTok** has the highest male users (48); **Facebook** has the highest female users (46)
- Gender distribution: Female-dominant on Facebook; Male-dominant on Instagram and TikTok
- Correlation analysis reveals how screen time, stress, sleep quality, and happiness interact

---

## 🛠️ Requirements

No installation needed for Google Colab — all libraries are pre-installed.

For local use:
```bash
pip install pandas numpy matplotlib seaborn
```

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

*Analysis prepared for GitHub | 2026*
