Smoking Health Risk Analysis Dashboard | Power BI

An interactive Power BI dashboard that analyzes the impact of smoking on human health, visualizing organ-wise damage, demographic trends, and health risk factors through dynamic, data-driven storytelling.

📌 Project Overview

This dashboard explores the relationship between smoking habits and organ health across a patient dataset of 2,500+ records. It combines custom navigation, comparative visuals, and DAX-driven analytics to present a clear, interactive view of how smoking status, duration, and intensity correlate with health outcomes such as cholesterol levels and hypertension risk.


✨ Key Features

-🫁 Organ-wise Navigation** — Custom image-based slicer (Human Body, Heart, Lungs, Kidney, Liver) to filter the dashboard by organ
- ⚖️ Healthy vs Damaged Comparison — Bookmark-powered toggle button that dynamically switches organ visuals and metrics between healthy and damaged states
- 📊 Smoking Status Breakdown — Donut chart showing the proportion of Never / Current / Former smokers
- 📈 YOS & CPD Trend Analysis  — Line chart tracking Years of Smoking (YOS) and Cigarettes Per Day (CPD) across age groups
- 👥 Gender-wise Smoking Trends  — Streamgraph comparing smoking status distribution between male and female patients
- ❤️ Cholesterol & Hypertension Risk — Stacked column chart showing risk levels (High / Low / Normal) segmented by age group
- 📋 KPI Cards — Total Patients, Average Age comparison, and Average BMI comparison indicators

---

 🛠️ Tools & Techniques Used

| Category | Details |
|---|---|
| Tool| Microsoft Power BI Desktop |
| Data Modeling| Custom relationships, data categorization (Image URL) |
| DAX | Calculated Columns (e.g., Age Group via `SWITCH`), Calculated Measures (Avg Age, Avg BMI comparisons) |
| Interactivity | Custom image-based slicers, Bookmarks, Buttons, Page navigation |
| Visuals | Donut Chart, Line Chart, Streamgraph/Stacked Area Chart, Stacked Column Chart, Card Visuals |



📊 Dataset

The dataset includes patient-level records covering:
- Demographics (Age, Gender)
- Smoking behavior (Status, Years of Smoking, Cigarettes Per Day)
- Health metrics (BMI, Cholesterol Level, BP Risk)
- Organ condition (Healthy/Damaged status per organ)

---

🎯 Key Insights

- Smoking duration and daily intake show varying patterns across age groups, with peak intensity observed in mid-life cohorts
- Cholesterol and hypertension risk levels shift noticeably between healthy and damaged organ states
- Gender-based smoking trends reveal distinct behavioral differences between current, former, and never smokers

---
 🚀 What I Learned

- Building custom interactive slicers using image-based navigation
- Implementing bookmark-driven UI state changes for comparative analysis
- Writing efficient DAX for calculated columns and measures
- Designing a clean, healthcare-themed dashboard layout focused on storytelling

---
