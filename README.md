# **WHO Data Analysis on COVID-19 (2019)**

### **Introduction**
The COVID-19 pandemic has impacted countries and regions globally, with varying levels of intensity. This report analyzes the WHO dataset on COVID-19 for 2019, focusing on global cases and deaths, both cumulative and recent. The objective is to identify trends, correlations, and provide recommendations based on key insights from the data.


#### **Aim**:  
The aim of this research is to analyze the global spread and impact of COVID-19 using WHO data, focusing on the prevalence, incidence, and mortality rates across different countries and regions.


### **Tools Used**
- **Excel**: Data cleaning, transformation, and initial analysis.
- **SQL**: Writing queries to analyze data from a relational database.
- **Power BI**: Creating interactive visual reports and dashboards.


### **Project Structure**
- `data/WHO-COVID-19-global-table-data.csv`: Contains the WHO COVID-19 dataset.
- `Sql_queries/SQL Queries.txt`: SQL queries used for data analysis.
- `Power_bi_report/POWER BI PROJECT PDF.pdf`: Power BI report file (`.pdf`) containing the dashboards.
- `Power_bi_report/WHO_Covid19_Dashboard.pbix`: Power BI report file (`.pbix`) containing the Dashboards.
- `Excel_anlysis/WHO_Covid19_Analysis.csv`: Excel workbook with data cleaning and preliminary analysis.


### **Usage**

   **Prerequisites**:
1. **SQL Database**: To run the SQL scripts, ensure you have a working SQL environment (e.g., MySQL, PostgreSQL).
2. **Power BI Desktop**: Install Power BI Desktop to open the `.pbix` file and view the dashboards.


### **Data Overview**
- **Source of Data**: WHO COVID-19 Dashboard  
- **Timeframe**: 2019  
- **Variables**:

  - Names of Countries  
  - WHO Regions  
  - Total cumulative cases  
  - Total cumulative deaths  
  - Cases per 100,000 population  
  - Deaths per 100,000 population  
  - Cases within the last 7 days and 24 hours  
  - Deaths within the last 7 days and 24 hours  

- **Summary Statistics (Global)**:

  - **Total cases**: 1 billion  
  - **Cases within the last 7 days**: 13M  
  - **Cases within the last 24 hours**: 2M  
  - **Total deaths**: 13M  
  - **Deaths within the last 7 days**: 23K  
  - **Deaths within the last 24 hours**: 3,490  


### **Data Cleaning & Preprocessing**
- **Handling Missing Data**: Missing data were replaced with either NA or zero as seen in numerical columns.  
- **Standardization**: Ensured that the data is consistent in format (e.g., date formats, uniform measurement units).


### **Data Visualization**
- **Charts and Graphs**:  
  - Bar charts comparing the top 10 affected countries.  
  - Pie charts for recovery and death rate percentages.  
- **Dashboards**: Power BI or Tableau can be used to create interactive dashboards summarizing key insights.

### **Key Findings**

**Countries (Cases)**:
- The country with the highest total cases (prevalence) is **Global**, with 0.56bn cases.
- **221 countries** recorded between 0-10,000 cases.
- **4 countries** had no recorded COVID-19 cases.
- **Pitcairn Island** has the highest incidence rate of COVID-19 per 100,000 population over the last 7 days.
- **France Island** had the highest prevalence of COVID-19 per 100,000 population.

**Countries (Deaths)**:
- The country with the highest total deaths (mortality) is **Global**, with 6M deaths.
- **215 countries** recorded between 0-10 deaths.
- **8 countries** had no recorded deaths.
- **Germany** had the highest mortality rate per 100,000 population within the last 7 days.
- **Peru Island** had the highest overall mortality rate per 100,000 population.

**Regions (Cases)**:
- The region with the highest total cases (prevalence) is **North America (NA)**, with 563M cases.
- **NA** also recorded the highest incidence of cases within the last 7 days.
- **Europe** had the highest incidence rate per 100,000 population in the last 7 days.

**Regions (Deaths)**:
- The region with the highest total deaths (prevalence) is **North America (NA)**, with 6.4M deaths.
- **NA** still has the highest mortality of COVID-19 within the last 7 days.
- **Europe** had the highest mortality rate per 100,000 population over the last 7 days.


### **Correlation Analysis**

  **1. Case-Death Correlation**:
There is a positive correlation between cumulative cases and deaths, which is consistent across most countries and regions. For example, **NA** shows a high total case count of 563M and a similarly high death toll of 6.4M, suggesting that regions with more cases are more likely to experience higher death tolls.

  **2. Per Capita Adjustments**:
When looking at cases and deaths per 100,000 population, smaller regions or countries may experience disproportionately high rates despite their low overall numbers. For example, **Pitcairn Island** had the highest incidence rate per 100,000 population over the last 7 days, and **Germany** had the highest mortality rate per 100,000 within the same period, indicating that population size and density may contribute significantly to the overall impact.

  **3. Time-Specific Analysis**:
The surge in cases and deaths within the last 7 days and 24 hours highlights active pandemic regions. While **Global** leads in total cases and deaths, the data suggests a more recent wave in **Europe**, which has the highest incidence and mortality rates per 100,000 population in the last 7 days.


### **Suggestions**

1. **Targeted Containment Measures**:  
   - **Regions with recent surges** such as Europe should focus on reinforcing containment measures, particularly in areas with high incidence rates per 100,000 population.  
   - **Countries with low case and death counts** should continue to enforce preventative measures to maintain these low numbers and prevent further outbreaks.

2. **Strengthening Healthcare Systems**:  
   - Countries with high death rates per 100,000 population, like **Peru Island** and **Germany**, may need to strengthen healthcare capacity, focusing on critical care resources to manage surges effectively.

3. **Data Transparency and Reporting**:  
   - Countries that report zero cases or deaths, such as the **4 countries with no cases** and **8 countries with no deaths**, should be investigated for potential underreporting. Ensuring accurate data collection is vital for global coordination efforts.

4. **Vaccination and Public Health Campaigns**:  
   - **Regions like NA**, with high cumulative cases and deaths, should focus on **vaccination campaigns** and **public health awareness**, especially in areas still recording high numbers in the last 7 days and 24 hours.


### **Recommendations**

1. **Monitor Hotspot Regions**:  
   Special attention should be given to Europe, as it has shown the highest incidence and mortality rates in the last 7 days.  

2. **Investigate Anomalies**:  
   Investigate countries with **no recorded cases or deaths** to ensure data accuracy and address potential gaps in reporting.  

3. **Long-Term Strategies**:  
   Develop a **long-term containment strategy** for countries like **Germany** and **Peru Island**, where mortality rates remain high per 100,000 population.  

4. **Regular Data Analysis**:  
   Continuous analysis of new case and death data is crucial, particularly focusing on regions like **NA** and **Europe**, which continue to show high case and death numbers both cumulatively and recently.


### **Limitations**

1. **Data Gaps**:  
   Some countries did not report cases consistently, leading to incomplete datasets.  
   
2. **Methodological Constraints**:  
   The analysis was limited by the availability of demographic data, restricting deeper insights into the affected populations.


### **Conclusion**

The COVID-19 pandemic has impacted different regions and countries in unique ways. This analysis highlights the regions and countries that require urgent public health interventions, based on both cumulative and recent data. The correlations between case and death counts, particularly when adjusted for population, reveal critical insights into how the pandemic is evolving and which regions are most vulnerable. Strategic recommendations have been provided to help guide ongoing policy responses and future planning.


### **Contributing**
Contributions are welcome! If you find any issues or improvements, feel free to submit a pull request or open an issue.


### **Acknowledgments**
- World Health Organization (WHO) for the dataset.
- Microsoft Power BI, Excel, and SQL for making data analysis accessible
