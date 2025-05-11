# COVID-19 Data Analysis with Web Scraping, Pandas & Seaborn

This project presents a comprehensive **Exploratory Data Analysis (EDA)** on the spread and impact of **COVID-19 in India** using real-time web scraping from credible sources like **Wikipedia** and **BBC**. The primary aim is to extract meaningful patterns and trends related to **COVID-19 testing**, **positivity**, and **regional case distributions**. This analysis supports public health insights and policy decisions by visualizing complex data in an intuitive format.

## 📅 Project Overview

### ✨ Goal:
To perform EDA on COVID-19 data for India using real-time scraped data.

### ⚖️ Approach:
1. **Web scraping** news and tabular data from trusted sources.
2. **Data cleaning** and structuring using **Pandas**.
3. **Data visualization** with **Matplotlib** and **Seaborn**.
4. Highlighting **state-wise trends**, **cluster similarities**, and **key metrics**.

### 🌐 Sources:
- **Wikipedia:** [COVID-19 pandemic in India](https://en.wikipedia.org/wiki/COVID-19_pandemic_in_India) - Live case data, positivity rates, and government statistics.
- **BBC:** [Coronavirus News](https://www.bbc.com/news/coronavirus) - Latest news and alerts related to COVID-19 globally.

## 🔄 Workflow Summary

### Data Collection:
- Scraped COVID-19 case statistics from Wikipedia tables.
- Extracted headlines and reports from the BBC Coronavirus News page.

### Data Cleaning:
- Removed null rows and adjusted column headers.
- Normalized numerical values for comparison.

### Data Transformation:
- Calculated positivity rate and derived metrics.
- Converted date formats and ensured type consistency.

### Visualization & Analysis:
- Created detailed plots to understand trends and regional variations.

## 💪 Technologies Used
- **Python 3.12**
- **Pandas** - Data manipulation and cleaning
- **Matplotlib** - Base plotting
- **Seaborn** - Statistical visualizations
- **Requests & BeautifulSoup** - Web scraping
- **Jupyter Notebook** - Interactive data exploration

## 📊 Visualizations & Insights


### 🧪 1. Total Tests vs Positive Cases
- **Chart Type:** Bar Plot
- **Purpose:** Compare the number of tests conducted with the number of positive cases.
- **Insight:** A proportional increase in testing correlates with higher confirmed cases, suggesting better detection coverage.

### 💉 8. Total Cases vs Vaccination Rate Over Time
- **Chart Type:** Dual-axis Line Plot
- **Purpose:** Track relationship between vaccination coverage and new cases using 7-day averages.
- **Insight:** As vaccination rate rises, case surges begin to stabilize or decline, suggesting a delayed but evident impact.

    <img width="652" alt="image" src="https://github.com/user-attachments/assets/804f42b3-1c77-4400-9bac-e2f371d7a434" />

### 🇮🇳 10. Daily New COVID-19 Cases in India
- **Chart Type:** Line Plot
- **Purpose:** Show the trend of daily reported cases in India along with a 7-day moving average.
- **Insight:** Clearly identifies pandemic waves and helps assess policy impacts over time.
    

### 📈 2. New Positive Cases Over Time
- **Chart Type:** Line Chart
- **Purpose:** Monitor the spread of COVID-19 daily.
- **Insight:** Significant spikes correspond to the Delta and Omicron variant waves.

        <img width="609" alt="image" src="https://github.com/user-attachments/assets/803b07f8-fcc2-4cf2-a0d5-7d1eefd64a66" />


### 📊 3. Statewise Positivity Rate (India)
- **Chart Type:** Horizontal Bar Chart
- **Purpose:** Compare positivity rates across Indian states.
- **Insight:** Certain states consistently exceed the national average, indicating testing and containment disparities.

### 🔢 4. New Samples vs New Positives
- **Chart Type:** Scatter Plot
- **Purpose:** Measure testing efficiency by visualizing daily new tests vs new positives.
- **Insight:** Outliers show testing surges during major COVID waves.

### 🔋 5. Heatmap of COVID Metrics by State
- **Chart Type:** Seaborn Heatmap
- **Purpose:** Show intensity of cases, deaths, and recoveries across states.
- **Insight:** Urban and dense states exhibit higher volumes and more healthcare pressure.

### 🔍 6. Correlation Matrix
- **Chart Type:** Heatmap
- **Purpose:** Discover statistical correlations between variables like tests, deaths, vaccination.
- **Insight:** Strong correlation between positivity rate and confirmed cases.

    <img width="332" alt="image" src="https://github.com/user-attachments/assets/f73d1bb0-4f9b-440c-86fe-919d6e34e499" />


### 🌍 7. Pie Chart – India's Case Distribution
- **Chart Type:** Pie Chart
- **Purpose:** Show proportion of active, recovered, and deceased cases.
- **Insight:** Recovery remains dominant; fatalities are proportionally low.

    <img width="314" alt="image" src="https://github.com/user-attachments/assets/382d2f2f-0eb0-4bda-8ac1-cd586317b3d4" />



### 🧰 8. Cluster Analysis
- **Technique:** KMeans Clustering
- **Features Used:** Total cases, total deaths, total vaccinations
- **Insight:** Countries grouped by severity level — useful for health policy segmentation.

    <img width="425" alt="image" src="https://github.com/user-attachments/assets/a0a7b29d-50fe-48b7-a5b7-00c25a270ee3" />

---

## 🛠️ Tech Stack

| Area              | Tools & Libraries Used                          |
|-------------------|--------------------------------------------------|
| **Web Scraping**  | `requests`, `BeautifulSoup`                      |
| **Data Analysis** | `pandas`, `numpy`                                |
| **Visualization** | `matplotlib`, `seaborn`                          |
| **ML Clustering** | `scikit-learn` (StandardScaler, KMeans)         |

---

## 📌 Key Observations

- 🟢 **Women had much higher survival rates** across all classes (if gender data is included).
- 🔵 **States with higher testing** usually report lower positivity due to early detection.
- 🟠 **Small states/UTs** sometimes report higher positivity due to lower test counts.
- 🟡 **Positivity rate fluctuations** align with known COVID-19 wave periods.
- 🔴 **Certain regions like Maharashtra and Delhi** consistently reported high cases and deaths.
