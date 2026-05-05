#  Hotel Booking Cancellation Analysis

##  Overview
This project analyzes hotel booking data to identify key factors driving cancellations.  
The analysis includes data cleaning, feature engineering, and an interactive Power BI dashboard.

---

##  Objectives
- Analyze cancellation patterns  
- Identify key drivers of cancellations  
- Build an interactive dashboard for insights  

---

##  Dataset
- Hotel booking dataset (cleaned using Python)  

### Includes features such as:
- Lead time  
- ADR (Average Daily Rate)  
- Hotel type  
- Booking dates  

---

##  Tools Used
- Python (Pandas, NumPy)  
- Power BI  
- Jupyter Notebook  

---

##  Key Insights
- **Lead Time is the strongest predictor**
  - Cancellations increase from **19% (0–30 days)** to **68% (365+ days)**  

- **City Hotels have higher cancellation rates**
  - ~42% vs ~28% for resort hotels  

- **Seasonal patterns exist**
  - Higher cancellations in mid-year months  

- **Weekly trends**
  - Higher cancellations towards the end of the week  

---

##  Data Quality Considerations
The dataset contains approximately **27% fully duplicated records**.

Due to the absence of a unique booking identifier, it is unclear whether these duplicates represent:
- actual repeated bookings, or  
- data duplication issues  

### Impact on Analysis:
- Cancellation Rate:
  - **37% (with duplicates)**
  - **27% (without duplicates)**  

This highlights a **significant impact on KPI reliability**, and results should be interpreted with caution.

---

##  Dashboard Preview
![Dashboard](dashboard.png)

---

##  Business Impact
High cancellation rates can negatively affect:
- Revenue stability  
- Room allocation efficiency  
- Demand forecasting accuracy  

Understanding cancellation behavior helps improve:
- Pricing strategies  
- Overbooking decisions  
- Operational planning  

---

##  Outcome
Built an end-to-end data project including:
- Data cleaning  
- Feature engineering  
- Exploratory analysis  
- Interactive dashboard  


