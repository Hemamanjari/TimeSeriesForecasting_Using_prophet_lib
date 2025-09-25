Airline Passengers Time Series Forecasting
Project Objective  
1.	Forecast “airline passenger traffic” using machine learning time series methods.  
2.	Apply “Facebook Prophet” library to capture trend and seasonality.  
3.	Validate model performance using cross-validation and RMSE.  

Dataset  
Columns:  
    •	`Month` → Converted to Prophet-compatible `ds` (date).  
    •	`Passengers` → Converted to Prophet-compatible `y` (target).  
Records: ~144 months (~12 years of monthly data).  

Project Workflow  
1. Data Preparation  
      •	Loaded dataset from Excel file.  
      •	Renamed columns to `ds` (date) and `y` (target).  
      •	Removed missing values.  

2. Modelling with Prophet 
      •	Initialized and trained a “Prophet model”.  
      •	Created future dates (365 days)  for forecasting.  
      •	Generated predictions for unseen data.  

3. Visualization  
      •	Plotted forecast curve (actual vs predicted).  
      •	Visualized trend and yearly seasonality components.  
  
4. Model Evaluation  
      •	Performed “cross-validation” with rolling windows.  
      •	Calculated performance metrics (RMSE, MAPE, MAE).  
•	Visualized error trends across forecast horizon.  


Key Insights Gained  

i.	 Airline passenger traffic has a “clear upward trend” over time.  
ii.	 A strong “yearly seasonal pattern:” is visible (peaks in summer travel).  
iii. Prophet effectively captured both “trend and seasonality”.  
iv.	 Cross-validation showed the model performs well with “low RMSE”.  
v.	 Forecast predicts “continued growth in passenger numbers” beyond 1960.  
  

 Business Actions Based on Insights  
 
1. “Airline Industry Planning”  
      •	Prepare for “peak summer demand” with additional resources (flights, crew, promotions).  
      •	Optimize “pricing strategies” based on forecasted seasonal demand.  

2. “Revenue Growth”  
      •	Anticipate “steady growth in passenger numbers” → plan capacity expansion.  
      •	Design “marketing campaigns” aligned with seasonal travel patterns.
 
3. “Operational Efficiency”  
      •	Use forecasts to improve “resource allocation” (staff, aircraft scheduling).  
      •	Mitigate risks of “under/over-capacity” through proactive planning.  
