# **Advancing Healthcare Analysis through Data Insights PowerBI**
![image](https://github.com/user-attachments/assets/437a2757-881e-4eeb-b3b1-e71ede6e359e)


## **Overview**

This repository contains the Power BI healthcare dashboard project developed as part of HealthStat Solutions' analytical initiatives. The dashboard provides deep insights into patient demographics, treatment outcomes, cost analysis, and hospital performance metrics. Leveraging advanced data modeling, DAX calculations, and interactive visualizations, this tool aids healthcare providers in improving patient care, optimizing operations, and making data-driven decisions.

---

## **Objective**

The primary goal of this project is to create a comprehensive and interactive Power BI dashboard that:

- Explores the relationships between patient demographics and treatment outcomes.
- Analyzes cost implications of medical procedures.
- Assesses hospital performance through key metrics.
- Supports decision-making for enhanced patient care and operational efficiency.

---

## **Key Features**

1. **Data Cleaning and Modeling**:
   - Addressed missing data, duplicate entries, and irrelevant data points.
   - Merged two datasets using the `PatientID` as the key.
   - Created calculated columns and measures using DAX.
2. **Advanced Analysis**:
   - Categorized patients into age groups for demographic analysis.
   - Analyzed trends in patient admissions over time.
   - Explored recovery ratings by treatment type and hospital performance metrics.
   - Implemented predictive modeling for recovery ratings.
3. **Interactive Dashboard**:
   - Visualized key metrics like diagnosis distribution, treatment costs, and recovery ratings.
   - Enabled hospital, diagnosis, and treatment type filters for targeted insights.
   - Designed time-based trend analysis and hospital performance comparisons.
4. **Data Storytelling**:
   - Highlighted significant insights and trends through engaging visual elements.
   - Summarized findings in a narrative format to support decision-making.

---

## **Datasets**

### **HealthcareDataset1.xlsx**

- Contains patient information, diagnosis, treatment details, and billing data.  
**Key Columns**: `PatientID`, `Age`, `Gender`, `Diagnosis`, `Treatment`, `AdmissionDate`, `DischargeDate`, `TotalBill`.

### **HealthcareDataset2.xlsx**

- Includes hospital details, doctor assignments, and recovery ratings.  
**Key Columns**: `PatientID`, `Hospital`, `DoctorName`, `RoomNumber`, `DailyCost`, `RecoveryRating`.

---

## **Dashboard Highlights**

### **Key Metrics**:

- Patient demographics by age group, gender, and blood type.
- Diagnosis and treatment distributions.
- Average treatment costs and recovery ratings by hospital and treatment type.
- Seasonal trends in patient admissions.

### **Advanced Insights**:

- Correlation between recovery ratings and treatment effectiveness.
- Impact of doctors and hospitals on patient outcomes.
- Room utilization and efficiency analysis.

### **Interactive Visualizations**:

- Filters for hospitals, diagnoses, and treatment types.
- Time-series analysis for trends in patient care.
- Comparisons of hospital performance metrics.

---

## **Technologies Used**

- **Power BI**: Data modeling, DAX calculations, and interactive visualizations.
- **Excel**: Data preparation and cleaning.
- **DAX**: Advanced measures and calculated columns.

---

## **Future Enhancements**

1. **Automating Data Updates Using Power BI Service**  
   - Implement scheduled refresh in Power BI Service to ensure the dashboard always displays up-to-date data without manual intervention.

2. **Integrating More Datasets for Deeper Insights**  
   - Incorporate additional datasets, such as patient feedback, insurance claims, and regional healthcare metrics, to enhance the scope of analysis and provide a more comprehensive view.

3. **Enhancing the Predictive Model for Recovery Ratings**  
   - Improve the DAX-based predictive model by integrating machine learning models using Python or R scripts in Power BI.  
   - Add features like patient history and treatment adherence to increase prediction accuracy.

4. **Adding Real-Time Analytics for Hospital Capacity Needs**  
   - Leverage real-time data streams to predict hospital occupancy and capacity requirements dynamically.  
   - Use tools like Azure Stream Analytics to feed real-time data into Power BI dashboards for actionable insights.


