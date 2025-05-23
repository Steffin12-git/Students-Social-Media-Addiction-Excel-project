
# Social Media Addiction vs Relationships – Excel Dashboard Documentation

## 📌 Overview

This interactive **Excel** dashboard provides a comprehensive analysis of how **social media usage** impacts **addiction**, **mental health**, **sleep patterns**, and **relationship conflicts** among students from various countries. Using slicers, charts, and KPI summaries, this visualization enables users to explore multi-dimensional data insights intuitively.

---

## 📊 Dataset Summary

* **Source:** [Kaggle - Social Media Addiction vs Relationships](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships)
* **Total Students Surveyed:** 705
* **Attributes Analyzed:**
  * Demographics: Country, Gender, Age, Academic Level
  * Behavioral: Sleep Duration, Platform Usage, Daily Usage
  * Mental Health Score & Status
  * Social Media Addiction Score & Level
  * Relationship Status & Conflict Frequency

---

## 🧹 Data Cleaning & Preparation (Power Query)

Before analysis, the dataset was thoroughly cleaned using **Power Query** in Excel. Major transformations included:

- **Renaming columns** for clarity
- **Removing duplicates**
- **Handling missing values** (filtering or imputing)
- **Standardizing text entries** (e.g., consistent case for categories)
- **Converting data types** appropriately
- **Creating derived columns** like addiction flags, sleep categories, etc.

Power Query ensures that the dashboard remains **dynamic and refreshable** if the source data changes.

---

## 📈 Dashboard Visuals & Explanations

### 🖼️ Dashboard Screenshot

![Dashboard Screenshot](social%20media%20vs%20studens.png)

---

### 1. 🧮 Key Metrics Cards (Left Panel)

| Metric                | Value  | Insight                                                          |
| --------------------- | ------ | ---------------------------------------------------------------- |
| Total Students        | 705    | Size of surveyed population                                      |
| Average Mental Health | 6.23   | Indicates moderately low mental well-being                       |
| Highly Addicted       | 77.16% | Majority of students are in the **high addiction** category      |
| Poor Sleep            | 30.78% | Nearly 1/3rd of students have **poor sleep quality**             |
| Conflict Behavior     | 63.83% | 2 out of 3 students experience conflicts related to social media |

---

### 2. 🧑‍🤝‍🧑 Gender vs Addiction (Stacked Column Chart)

* **Objective:** Compare addiction levels across genders.
* **Insight:** Both **males and females** show similar distributions, with **low and moderate addiction dominating**, but notable presence of **high addiction** as well.

---

### 3. 🧠 Usage vs Mental Health (Bar Chart)

* **Objective:** Correlate usage frequency with mental health.
* **Insight:**
  - **High usage → Lower mental health (5.85)**
  - **Low usage → Higher mental health (8.50)**
  - Shows negative correlation between screen time and mental well-being.

---

### 4. 💔 Relationship vs Conflict (Column Chart)

* **Objective:** Analyze how relationship status affects social conflicts.
* **Insight:**
  - **Single students (384)** face the most conflict.
  - **In relationships (289)** also show high conflict.
  - **Complicated status (32)** face the least conflicts — possibly due to social withdrawal.

---

### 5. 🌍 Addiction Level vs Conflict (Combo Chart - Bar & Line)

* **X-Axis:** Top 10 countries
* **Bar:** % of highly addicted students
* **Line:** Average conflict frequency
* **Insight (Top 5):**
  - **India (16.77%)** has highest addiction percentage with moderate conflict (3.53).
  - **USA** shows **high conflict score (3.80)** with lower addiction.
  - **France & Switzerland** show **low addiction and low conflict**.

---

### 6. 📱 Social Media vs Students (Line Chart)

* **Objective:** Show platform preference among students.
* **Insight:**
  - **Instagram (249)** is the most used platform.
  - Followed by **TikTok (154)**, **Facebook (123)**, **WhatsApp (54)**, and **Twitter (30)**.

---

### 7. 🎛️ Slicers: Filters for Deep Analysis

* **Sleep Categories:** Excellent, Good, Poor, Very Poor
* **Gender:** Male / Female
* Enable customized insights into subgroups (e.g., “Female students with poor sleep”).

---

## 📘 Storytelling: Insights in Sequence

> 🧍‍♂️ The dataset shows that the **majority of students are highly addicted** to social media. Despite representing a global sample, commonalities appear across countries and genders.

> 🧠 With increasing screen time, **mental health scores drop significantly**, highlighting the emotional toll of digital engagement.

> 💬 Most students, especially those who are single or heavily online, report high **conflict frequency**, suggesting that digital behavior spills into social stress.

> 📉 Platforms like Instagram and TikTok dominate, raising concerns over the **dopamine feedback loops** and **platform design** influencing student behavior.

> 🛌 Finally, **sleep disruption (30.78%)** emerges as a critical health indicator, reinforcing that digital overuse affects not just the mind but also physical recovery.

---

## 🛠 How It Was Built (Excel Techniques)

| Tool/Feature         | Purpose |
|----------------------|---------|
| Power Query          | Cleaning, transformation, derived columns |
| PivotTables          | Data aggregation |
| Charts               | Combo, stacked bar, column, line |
| Slicers              | Interactive filtering |
| Conditional Formatting | Visual emphasis |
| COUNTIF, AVERAGEIF   | KPI calculations |

---

## ✅ Recommendations (based on findings)

1. **Digital Wellness Programs** should be prioritized in educational institutions.
2. Students should be educated about **screen time management**.
3. Social support and mental health counseling can be targeted toward **high-risk groups**.
4. Encourage **platform usage awareness** through workshops.
5. Future studies should explore **longitudinal effects** of these digital behaviors.

---

## 📁 File Contents

- `social media vs studens.png`: Dashboard Screenshot  
- `README.md`: This documentation  
- `Students-Social-Media-Addiction-Excel-project.xlsx`: Excel file with Power Query & Dashboard (not included here)  
- Dataset: [Kaggle CSV file](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships)
