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




### 💉 1. Total Cases vs Vaccination Rate Over Time
- **Chart Type:** Dual-axis Line Plot
- **Purpose:** Track relationship between vaccination coverage and new cases using 7-day averages.
- **Insight:** As vaccination rate rises, case surges begin to stabilize or decline, suggesting a delayed but evident impact.

    <img width="652" alt="image" src="https://github.com/user-attachments/assets/804f42b3-1c77-4400-9bac-e2f371d7a434" />

### 🇮🇳 2. Daily New COVID-19 Cases in India
- **Chart Type:** Line Plot
- **Purpose:** Show the trend of daily reported cases in India along with a 7-day moving average.
- **Insight:** Clearly identifies pandemic waves and helps assess policy impacts over time.
   
 <img width="608" alt="image" src="https://github.com/user-attachments/assets/097eb96f-5ea0-4c64-9be8-2cc586a32209" />

### 🌐 3. Total Cases vs Total Vaccinations (Top 10 Countries)
- **Chart Type:** Bar Chart
- **Purpose:** Compare the total number of confirmed COVID-19 cases and total vaccinations among the top 10 most affected countries.
- **Insight:**  Countries with the highest number of cases also show high vaccination counts, reflecting large-scale mitigation efforts. However, disparities suggest uneven global distribution of vaccines despite high caseloads.

    <img width="618" alt="image" src="https://github.com/user-attachments/assets/2907e63e-178b-4f8f-aadf-7a0f933ef204" />

### 🌍 4. Total Cases vs Total Deaths by Continent
- **Chart Type:** Bar Chart
- **Purpose:** Visualize the cumulative burden of COVID-19 across continents by comparing total confirmed cases and deaths.
- **Insight:** Asia and Europe report high case counts, while mortality rates vary, indicating differences in healthcare infrastructure, reporting, and population size.
    
  <img width="445" alt="image" src="https://github.com/user-attachments/assets/59818337-e369-4a58-bcd3-48af496dffff" />




### 🔍 5. Correlation Matrix of COVID-19 Metrics
- **Chart Type:** Heatmap
- **Purpose:** Display statistical relationships between core COVID-19 metrics such as cases, deaths, vaccinations, and population.
- **Insight:** Strong positive correlation observed between total cases and total deaths. Vaccination rate shows moderate correlation with total vaccinations and inversely with deaths, indicating a potential mitigation effect.

   <img width="331" alt="image" src="https://github.com/user-attachments/assets/4a7b1b62-d1f7-46ed-847d-0eef13e1a822" />



### 🌍 6. Total New COVID-19 Cases by Continent
- **Chart Type:** Bar Chart
- **Purpose:** Visualize the total new COVID-19 cases by continent to identify regions with the highest new case rates.
- **Insight:** The chart highlights continents with the highest daily case increases, offering valuable insights for public health strategies and resource allocation.

    <img width="305" alt="image" src="https://github.com/user-attachments/assets/2235322c-fbc5-4b0e-a67c-f3cb797c752a" />


### 🌍 7. Estimated COVID-19 Case Distribution in India
- **Chart Type:** Pie Chart
- **Purpose:** Estimate the distribution of active, recovered, and deceased COVID-19 cases in India based on available data.
- **Insight:** The pie chart provides a visual estimate of active, recovered, and deceased cases in India, offering insights into the current state of the pandemic and helping in the assessment of healthcare system strain and response strategies.

    <img width="312" alt="image" src="https://github.com/user-attachments/assets/94d8ccfb-78dc-483d-bdf2-fd191070f054" />


### 🌍 8. Pie Chart – India's Case Distribution
- **Chart Type:** Pie Chart
- **Purpose:** Show proportion of active, recovered, and deceased cases.
- **Insight:** Recovery remains dominant; fatalities are proportionally low.

    <img width="314" alt="image" src="https://github.com/user-attachments/assets/382d2f2f-0eb0-4bda-8ac1-cd586317b3d4" />


### 🧰 9. Cluster Analysis
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
