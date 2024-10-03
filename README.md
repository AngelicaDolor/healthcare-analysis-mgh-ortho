### Project Background

**Company**: MaineGeneral Health, Orthopedics Department <br>
**Industry**: Healthcare (Orthopedics) <br>
**Active Years**: Established in the late 1800s, MaineGeneral Health has been providing medical services for over a century.  <br>
**Business Model**: The company operates on a patient-centric healthcare model, focusing on delivering specialized orthopedic services. It collects patient feedback (PSAT scores), tracks wait times, and analyzes patient flow to enhance the quality of care.  <br>
**Key Business Metrics**:  
- **# of Patients (2023)**: 531  
- **Average PSAT Score**: 5.1  
- **Average Wait Time**: 36 minutes  

As a **Data Analyst**, my role is to assess key operational and patient satisfaction metrics of year 2023, offering insights that will improve hospital efficiency, reduce patient wait times, and ultimately enhance the overall patient experience.

---

### Insights and Recommendations

The analysis focuses on the following key areas:

- Average Patient Satisfaction (PSAT) Scores  
- Patient Flow and Volume by Month and Age Bracket  
- Wait Time Correlation with Patient Volume  
- Patient Distribution Across Different Times of Day  

---

### Data Structure & Initial Checks

The hospital's dataset included patient visits, wait times, and satisfaction scores across several months. I imported the data into **Excel**, then used **Pivot Tables and Charts** to analyze the relationships between variables.

**Here’s how Excel was used:**

- **Data Cleaning:** I standardized date formats and checked for missing or inconsistent data before analysis.
- **Pivot Tables:** I created pivot tables to summarize key metrics like patient count, PSAT scores, and wait times by month, age group, and time of day.
- **Charts:** To visualize trends, I used bar charts, line charts, and tables, making it easier to spot patterns and correlations.

The company's main database consists of the following data:  
- Patient Visits (Patient ID, Visit Date, Age Bracket, PSAT Score)  
- Time of Day Data (Visit Time, Wait Time in Minutes)  
- Patient Flow (Number of Patients per Day/Month)  
- Operational Metrics (PSAT Score, Wait Time)

Download Excel report [here](https://github.com/AngelicaDolor/healthcare-analytics-mgh-ortho/blob/main/Orthopedics%20Dashboard%20Report.xlsx).

---

### Executive Summary

#### Overview of Findings

1. The average PSAT score is 5.1, with significant variation by month.
2. Patient wait times and volume vary widely by time of day, with peak wait times coinciding with peak patient volumes.
3. Patients aged 21-60 comprise the majority of hospital visits, but wait times are longest for the 61-70 age group.

---

### Insights Deep Dive

![Orthopedics Dashboard 2023](https://github.com/AngelicaDolor/healthcare-analytics-mgh-ortho/blob/main/Orthopedics-Dashboard.png)

#### **Average Patient Satisfaction (PSAT) Scores**

- **Main Insight 1**: The average PSAT score across the year is **5.1**. The highest score was recorded in **January** at **6.4**, while the lowest was in **June** at **4.1**.  
  *Analysis*: PSAT scores may fluctuate based on seasonal factors or changes in operational efficiency during specific months.

- **Main Insight 2**: There is a steady decline in PSAT scores from January through June, indicating possible issues with patient satisfaction in the middle of the year.  
  *Recommendation*: Investigate if any policy or staff changes occurred during this period to address any operational shortcomings.

#### **Patient Flow and Volume by Month and Age Bracket**

- **Main Insight 1**: The hospital saw its highest number of patients in **July** (60 patients) and its lowest in **February** (45 patients).  
  *Analysis*: A rise in patient volume correlates with warmer months, possibly due to seasonal injuries or procedures being more frequent during this period.

- **Main Insight 2**: Patients aged **21-60** make up the largest proportion of visitors, with relatively stable volumes across different age brackets. The **41-50 age group** had a spike in visits during the year.  
  *Recommendation*: Consider targeted outreach or services for the 21-60 age group to maximize satisfaction and streamline operations during their visits.

#### **Wait Time Correlation with Patient Volume**

- **Main Insight 1**: The average wait time is **36 minutes**. The correlation between wait time and the number of patients is evident, with peak wait times occurring during the busiest hours (10 AM, 12 PM, 3 PM).  
  *Analysis*: Overcrowding during these hours suggests a need for operational adjustments during high-traffic periods to reduce wait times.

- **Main Insight 2**: During **early morning hours (12 AM to 4 AM)**, wait times are lower, but they peak later in the day, particularly after **12 PM**.  
  *Recommendation*: Allocate more staff or resources during peak hours to manage wait times effectively, as prolonged waits could negatively impact PSAT scores.

#### **Patient Distribution Across Different Times of Day**

- **Main Insight 1**: Most patients arrive during **late morning to early afternoon**, with a consistent rise in visits from **9 AM to 3 PM**. The number of patients drops significantly after **6 PM**.  
  *Analysis*: This distribution highlights key hours where demand is highest. Identifying bottlenecks during these hours is essential for improving patient flow.

- **Main Insight 2**: Although patient volume is higher during the day, the evening sees fewer visitors, which suggests that additional staffing or resources may be unnecessary during these times.  
  *Recommendation*: Explore potential for scheduling more complex procedures in the early morning or evening to balance out the load during peak hours.

---

### Recommendations

Based on the insights and findings above, I would recommend the **Operations Team** to consider the following actions:

1. **Optimize Staffing Levels**: Adjust staff schedules, particularly around peak hours (late morning and early afternoon), to better accommodate the influx of patients and reduce wait times.
2. **Investigate PSAT Score Decline**: Conduct a thorough review of changes made between January and June, and explore interventions to maintain a steady patient satisfaction rate.
3. **Targeted Services for the 41-60 Age Group**: Since this demographic forms the majority of visits, consider offering tailored services or priority scheduling to ensure timely care.
4. **Reduce Evening Staff**: As patient volume drops after 6 PM, reallocate staff to busier periods or adjust evening hours of operation.

---

### Assumptions and Caveats

Throughout the analysis, the following assumptions were made:

- **Assumption 1**: Any missing data for the PSAT score was assumed to be the average of that month's scores to ensure consistent reporting.
- **Assumption 2**: The wait time data, especially for overnight periods, was assumed to be accurate despite low patient volumes.
- **Assumption 3**: Data inconsistencies between months (e.g., missing patient records) were handled by averaging values from adjacent months to fill in gaps.
