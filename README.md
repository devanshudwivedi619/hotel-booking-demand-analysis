# hotel-booking-demand-analysis
Exploratory Data Analysis of Hotel Booking Data using Python, Pandas, NumPy, Matplotlib and Seaborn to discover booking trends, cancellation patterns and business insights.



# 🏨 Hotel Booking Demand Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

<p align="center">
  **EXPLORATORY DATA ANALYSIS | DATA CLEANING | DATA VISUALIZATION**
</p>

---

## 📌 Project Overview

Hotel Booking Demand Analysis is a Python-based Exploratory Data Analysis (EDA) project focused on understanding hotel booking patterns, customer behaviour, cancellation trends and pricing.

The project uses the Hotel Booking Demand dataset and analyzes two hotel categories: City Hotel and Resort Hotel.

The analysis is performed using Python, Pandas, NumPy, Matplotlib and Seaborn in Jupyter Notebook.

**Business Case:** Elite Hotels International — a project scenario used to interpret booking data and explore possible business improvements.

## 🎯 Project Objectives

- Analyze hotel booking distribution.
- Compare City Hotel and Resort Hotel bookings.
- Understand cancellation patterns.
- Explore monthly arrival trends.
- Analyze Average Daily Rate (ADR).
- Study market segments and distribution channels.
- Explore country-wise booking patterns.
- Compare guest types and stay duration.
- Estimate lodging revenue using documented assumptions.
- Present findings through charts and business recommendations.

## 📊 Dataset Information

| Detail | Information |
|---|---|
| Dataset | Hotel Booking Demand |
| File | `hotel_bookings.csv` |
| Original rows | 119,390 |
| Columns | 32 |
| Exact duplicates removed | 31,994 |
| Rows after duplicate removal | 87,396 |

**Dataset Source:** [Hotel Booking Demand – Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming |
| 🐼 Pandas | Data cleaning and manipulation |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical visualization |
| 📓 Jupyter Notebook | Interactive analysis |

## 🧹 Data Cleaning

- Identified and removed 31,994 exact duplicate records.
- Filled four missing `children` values with 0.
- Replaced missing country values with `Unknown`.
- Retained missing agent and company values.
- Excluded negative ADR values from relevant ADR and revenue calculations.
- Avoided blindly deleting high ADR outliers.
- Created `total_guests`, `total_nights` and `arrival_date` fields.

## 📈 Exploratory Data Analysis

The notebook contains 14 chart and visualization sections:

1. Booking Distribution by Hotel Type
2. Booking Lead Time Distribution
3. Cancellation Rate by Hotel Type
4. Monthly Arrival Pattern
5. Market Segment Analysis
6. Distribution Channel Analysis
7. ADR Comparison by Hotel Type
8. ADR Trend by Year
9. Top Countries by Bookings
10. Guest Preferences and Special Requests
11. Stay Duration by Hotel Type
12. Repeated Guest Analysis
13. Estimated Lodging Revenue by Month
14. Cancellation Rate by Month

## 💡 Key Findings

| Analysis | Finding |
|---|---|
| City Hotel bookings | 53,428 (61.13%) |
| Resort Hotel bookings | 38.87% |
| Overall cancellation rate | 27.49% |
| City Hotel cancellation rate | 30.04% |
| Resort Hotel cancellation rate | 23.48% |
| Busiest arrival month | August |
| Largest market segment | Online TA |
| Largest distribution channel | TA/TO |
| Leading known country | PRT |
| Higher average ADR | City Hotel |

## 🚀 Business Recommendations

- Review cancellation patterns by hotel type and booking channel.
- Plan resources around seasonal booking demand.
- Monitor ADR patterns when reviewing pricing.
- Evaluate distribution channels beyond booking volume alone.
- Consider stay duration when planning housekeeping and staffing.

## 💰 Revenue Estimation

The notebook estimates lodging revenue using:

`ADR × Total Nights`

The estimate uses eligible completed, non-canceled bookings with non-negative ADR and at least one night.

This is an estimate, not audited revenue, profit or actual cash collected.

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/devanshudwivedi619/hotel-booking-demand-analysis.git
```

### 2. Open the Project Folder

```bash
cd hotel-booking-demand-analysis
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the Notebook

`Hotel_Booking_Demand_Analysis_Best_Version.ipynb`

Keep `hotel_bookings.csv` in the same directory as the notebook.

## 📁 Repository Structure

```text
hotel-booking-demand-analysis/
│
├── README.md
├── Hotel_Booking_Demand_Analysis_Best_Version.ipynb
├── hotel_bookings.csv
├── Hotel_Booking_Demand_Analysis_Documentation.pdf
└── .gitignore
```

## 📖 Project Documentation

Detailed project documentation is provided separately:

**Hotel_Booking_Demand_Analysis_Project_Documentation.docx**

It covers:

- Project overview and objectives
- Dataset description
- Data cleaning methodology
- Tools and technologies
- Exploratory Data Analysis
- 14 visualization sections
- Key findings
- Business recommendations
- Limitations and assumptions

## ⚠️ Limitations

- Occupancy rate is not calculated because room inventory is unavailable.
- ADR is not the same as total revenue or profit.
- Revenue is an estimate and excludes taxes, fees and other services.
- Special requests are not a direct customer satisfaction measure.
- Country booking counts do not necessarily represent unique guests.
- Monthly totals combine the years present in the dataset.

## 👨‍💻 Author

**Devanshu Dwivedi**

Aspiring Data Analyst

**Skills:** Python | Pandas | NumPy | Data Cleaning | Exploratory Data Analysis | Data Visualization

## 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/devanshu-dwivedi-403783371/">
    <img src="https://img.shields.io/badge/LinkedIn-Devanshu%20Dwivedi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile" />
  </a>
</p>

<p align="center">
  **Let's connect and grow professionally! 🚀**
</p>

---

<p align="center">
  **Turning Raw Data into Meaningful Business Insights 🚀**
</p>

<p align="center">
  ⭐ Thank you for visiting my project!
</p>
