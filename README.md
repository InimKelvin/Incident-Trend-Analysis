# Incident Trend Analysis

## Project Overview

The **Incident Trend Analysis** project involves conducting statistical analysis on incident reports to identify recurring issues and recommend preventive measures. The analysis was performed using a synthetic dataset, cleaned and pre-processed in Python, and visualized in Tableau to create an interactive dashboard. The main goal of the project was to provide insights into incident trends, resolution times, and priorities to aid in decision-making and process improvement.

---

## Key Steps

### 1. **Data Generation & Cleaning**
   - **Dataset**: A synthetic dataset was generated to simulate incident reporting in a corporate environment. The dataset contained various columns, such as incident ID, type, department, priority, resolution time, and status.
   - **Data Preprocessing**: Missing values, duplicates, and outliers were identified and handled using Python’s pandas library. The data was then cleaned and saved for further analysis.
   
   **Generated Dataset**: [Incident_Trend_Analysis_Generated.csv](https://github.com/InimKelvin/Incident-Trend-Analysis/blob/main/incident_trend_analysis_dataset.csv)

### 2. **Exploratory Data Analysis (EDA) in Python**
   - **Data Inspection**: The dataset was inspected using Python (pandas and matplotlib) to understand its structure and to identify trends in incidents.
   - **Key Metrics**:
     - Trends in incident frequency over time.
     - Distribution of incidents by department and type.
     - Average resolution times by priority and department.
     - Insights into the most common incident types and their resolution efficiency.

   **Python Notebook for EDA**: [Incident_Trend_Analysis.ipynb](https://github.com/InimKelvin/Incident-Trend-Analysis/blob/main/Incident_trend_analysis.ipynb)

### 3. **Data Analysis and Visualization in Tableau**
   - **Dashboard Design**: An interactive Excel dashboard was created using pivot tables, slicers, and charts to visualize key trends and patterns.
   - **Key Excel Visualizations**:
     - **Incident Trend Over Time**: A line chart showing the frequency of incidents reported over the months.
     - **Incident Type Distribution**: A pie chart showing the proportion of each incident type.
     - **Incident Priority Analysis**: Bar charts to visualize incident counts by priority.
     - **Resolution Time Analysis**: Scatter plot and line charts to showcase the correlation between incident priority and resolution time.

   **Tableau Dashboard**: [Incident_Trend_Analysis_Dashboard.twb](https://public.tableau.com/views/IncidentTrendAnalysisDashboard/IncidentTrendAnalysis?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link&:device=desktop)

### 4. **Key Findings from the Analysis**
   - **Increase in Incidents**: There was a noticeable increase in incident reporting over the period, particularly in high-priority incidents.
   - **Departmental Trends**: The Sales department reported the highest number of incidents, followed by the HR department.
   - **High Priority Incidents**: High-priority incidents had significantly longer resolution times compared to low and medium-priority incidents.
   - **Recurring Incident Types**: Security Breach incidents were the most frequent, followed by Software issues. These incidents often took longer to resolve, especially when related to critical systems.

### 5. **Recommendations**
   - **Preventive Measures for Recurring Issues**: Focus on proactive monitoring and maintenance of software systems to reduce recurring issues.
   - **Improved Incident Response for High-Priority Issues**: Implement better workflows and automated tools for quicker resolution of high-priority incidents.
   - **Resource Allocation**: Allocate more resources to IT support and maintenance teams to manage the increasing number of incidents, particularly for critical systems.

---

## 📁 **Project Files**

| File | Description |
|------|-------------|
| 🔗 [**Incident_Trend_Analysis.ipynb**](https://github.com/InimKelvin/Incident-Trend-Analysis/blob/main/Incident_trend_analysis.ipynb) | Python Jupyter Notebook containing the EDA and data analysis. |
| 🔗 [**Incident_Trend_Analysis_Cleaned.csv**](https://github.com/InimKelvin/Incident-Trend-Analysis/blob/main/clean_incident_data.xlsx) | Cleaned data after data wrangling and preprocessing steps. |
| 🔗 [**Incident_Trend_Analysis_Dashboard**](https://public.tableau.com/views/IncidentTrendAnalysisDashboard/IncidentTrendAnalysis?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link&:device=desktop) | Tableau link with the interactive dashboard including charts, KPIs, and slicers. |
| 🔗 [**Incident_Trend_Analysis_Generated.csv**](https://github.com/InimKelvin/Incident-Trend-Analysis/blob/main/incident_trend_analysis_dataset.csv) | **Generated Dataset**: A synthetic dataset used for the project, containing incident records with details such as incident type, department, priority, resolution time, and status. This dataset simulates real-world incident reporting. |

---

## 🧠 **Key Insights**

- **Top Departments Reporting Incidents**: Sales and HR are the most active departments in terms of incident reporting.
- **Incident Type Frequency**: Security Breaches and Software incidents are the most frequent, suggesting a need for enhanced software monitoring.
- **Incident Resolution Time**: High-priority incidents tend to take longer to resolve, highlighting the need for quicker resolution strategies.
- **Impact of Incident Priority**: There is a strong correlation between priority levels and resolution times, with high-priority incidents requiring more time.

---

## 🔍 **Conclusion**

This analysis provides valuable insights into the incident reporting trends within a corporate environment. The findings and recommendations can help in optimizing incident management strategies, improving response times, and reducing the recurrence of issues.

The interactive dashboard built in Tableau allows users to quickly filter and analyze the incident data based on various parameters, aiding decision-makers in identifying trends and areas for improvement.

---

Feel free to clone, fork, or extend this project to suit your needs! If you have any questions or suggestions, please reach out.

---

