# 🦠 COVID-19 Data Analysis & Dashboard

## 📌 Project Overview

This project presents an analysis of global COVID-19 data using **Microsoft Excel / Google Sheets**.

The project focuses on analyzing country-wise and date-wise COVID-19 statistics, creating Pivot Table summaries, developing visualizations, and presenting key metrics through an analytical dashboard.

The goal of this project is to transform raw COVID-19 data into meaningful insights using spreadsheet-based data analysis and visualization techniques.

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Google Sheets
- Pivot Tables
- Data Cleaning
- Data Analysis
- Data Visualization
- Charts
- Dashboard Creation
- Basic Statistical Analysis

---

## 📂 Dataset

The dataset contains global COVID-19 information collected across different countries and dates.

### Main columns include:

- Province/State
- Country/Region
- Latitude
- Longitude
- Date
- Confirmed Cases
- Deaths
- Recovered Cases
- Active Cases
- WHO Region

The project also contains date-wise calculated metrics such as:

- New Cases
- New Deaths
- New Recoveries
- Deaths per 100 Cases
- Recovered per 100 Cases
- Deaths per 100 Recovered
- Number of Countries

---

## 🔎 Data Analysis Performed

The following analysis was performed as part of the project:

### 1. Country-wise Analysis

Analyzed COVID-19 cases across different countries and compared:

- Confirmed Cases
- Deaths
- Recovered Cases

### 2. Top 10 Countries Analysis

Identified the top 10 countries based on confirmed COVID-19 cases and compared their:

- Confirmed Cases
- Deaths
- Recovered Cases

### 3. Date-wise Analysis

Analyzed the growth of confirmed COVID-19 cases over time using date-wise data.

### 4. Pivot Table Analysis

Created a Pivot Table to summarize country-level COVID-19 statistics and make comparisons easier.

### 5. Dashboard

Created a dashboard containing key COVID-19 indicators and visualizations for quick analysis.

---

## 📊 Dashboard

The dashboard provides an overview of the major COVID-19 metrics, including:

- Total Confirmed Cases
- Total Deaths
- Total Recovered Cases
- Global Death Rate
- Top 10 Countries
- Confirmed Cases over Time

### Dashboard Preview

![COVID-19 Dashboard](Dashboard/COVID-19_Dashboard.png)

---

## 📈 Visualizations

### Top 10 Countries: Confirmed, Deaths & Recovered

The chart compares confirmed, death, and recovered cases across the top 10 countries in the analysis.

![Top 10 Countries](Charts/Top_10_Countries.png)

---

### Confirmed Cases Over Time

This line chart shows the growth of cumulative confirmed COVID-19 cases over the analyzed period.

![Confirmed Cases Over Time](Charts/Confirmed_vs_Date.png)

---

## 📋 Pivot Table Analysis

A Pivot Table was used to summarize country-level COVID-19 data and compare confirmed cases, deaths, and recovered cases.

![Pivot Table](Screenshots/Pivot_Table.png)

---

## 💡 Key Insights

- The United States recorded the highest confirmed cases among the countries shown in the analysis.
- Brazil and India were also among the countries with the highest confirmed cases.
- Confirmed cases increased significantly over the analyzed period.
- The comparison between confirmed, recovered, and death cases shows significant differences in COVID-19 outcomes across countries.
- The dashboard provides a consolidated view of important COVID-19 indicators.

---

## 📊 Dashboard Metrics

The dashboard summarizes the following figures from the analyzed dataset:

| Metric | Value |
|---|---:|
| Total Confirmed Cases | 16,480,485 |
| Total Deaths | 654,036 |
| Total Recovered Cases | 9,468,087 |
| Global Death Rate | 3.97% |

---

## 📁 Project Structure

```text
COVID-19-Data-Analysis/
│
├── README.md
│
├── Dataset/
│   ├── covid_19_clean_complete.csv
│   └── day_wise_data.csv
│
├── Dashboard/
│   └── COVID-19_Dashboard.png
│
├── Charts/
│   ├── Top_10_Countries.png
│   └── Confirmed_vs_Date.png
│
└── Screenshots/
    └── Pivot_Table.png
