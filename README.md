# 🌐 Global Internet Adoption Analysis | World Development Indicators (WDI)

![Global Internet Adoption Dashboard](World_Internet_Adoption_Dashboard.jpeg)

## 📖 Project Overview

This project presents an interactive Power BI dashboard analyzing global internet adoption trends using the **World Bank World Development Indicators (WDI)** dataset. The analysis explores internet usage across countries, regions, and genders, providing insights into historical trends, regional disparities, and global digital connectivity.

Developed as the **Week 8 Capstone Project** for the **AnalystLab Africa Data Analytics Internship**, this project demonstrates the complete data analytics workflow—from data preparation and modeling to visualization and insight generation.

---

## 🎯 Project Objectives

- Analyze historical internet adoption trends worldwide.
- Compare internet usage across countries and world regions.
- Examine internet adoption by gender.
- Identify countries with the highest average internet usage.
- Build an interactive dashboard to support data-driven decision-making.

---

## 📂 Dataset

**Source:** World Bank – World Development Indicators (WDI)

The World Development Indicators (WDI) is the World Bank's flagship database of international development statistics, covering over 200 countries and territories.

### Indicators Analyzed

- Individuals using the Internet (% of population)
- Individuals using the Internet, female (% of female population)
- Individuals using the Internet, male (% of male population)

Supporting country metadata from **WDICountry.csv** was used to distinguish individual countries from aggregate regions and income groups.

---

## 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel

---

## 🧹 Data Preparation

The following preprocessing steps were completed before analysis:

- Imported the WDI dataset into Power BI.
- Promoted headers and corrected data types.
- Filtered the dataset to retain internet adoption indicators.
- Removed unnecessary columns.
- Imported the WDICountry lookup table.
- Removed aggregate records by filtering blank regions.
- Created relationships using **Country Code**.
- Built DAX measures for KPIs and visualizations.

---

## 📊 Dashboard Features

The dashboard includes:

- 📈 KPI Cards
- 🌍 Interactive World Map
- 📉 Internet Adoption Trend Analysis
- 🏆 Top 10 Countries by Average Internet Adoption
- 🌎 Regional Internet Adoption Comparison
- 🎛 Interactive Slicers (Year, Country, Indicator)

---

## 🔍 Key Insights

- Internet adoption has grown substantially over time.
- North America records the highest average internet adoption among the analyzed regions.
- Sub-Saharan Africa records the lowest regional average, highlighting the digital divide.
- Male internet adoption is slightly higher than female internet adoption across the available observations.
- Several countries consistently demonstrate very high internet adoption rates.

> **Note:** The KPI values represent averages across the available country-year observations in the dataset. Because the dataset spans multiple decades, these values should be interpreted as historical averages rather than current global internet penetration rates.

---

## 💡 Recommendations

- Expand broadband infrastructure in underserved regions.
- Improve affordability of internet services.
- Invest in digital literacy and skills development.
- Promote inclusive digital access policies.
- Encourage international collaboration to reduce digital inequality.

---

## 📁 Repository Contents

```text
📦 world-internet-adoption-analysis
│
├── README.md
├── World_Internet_Adoption_Dashboard.jpeg
├── World_Internet_Adoption_Analysis_Goodness_Festus.pbix
├── World_Internet_Adoption_Analysis_Report_Goodness_Festus.pdf
```

---

## 🚀 How to Use

1. Download the `.pbix` file.
2. Open it in **Microsoft Power BI Desktop**.
3. Explore the dashboard using the interactive Year, Country, and Indicator slicers.

---

## 👩‍💻 Author

**Goodness Okoro**

Data Analyst with a passion for transforming data into actionable insights through analytics, visualization, and storytelling.

---

## 🙏 Acknowledgements

- **World Bank** for providing the World Development Indicators dataset.
- **AnalystLab Africa** for the Data Analytics Internship and Capstone Project opportunity.

---

⭐ If you found this project interesting, feel free to explore the dashboard and share your feedback!
