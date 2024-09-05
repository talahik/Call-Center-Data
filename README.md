# Call-Center-Data
## Overview
This project involves the analysis of anonymized call data from a marketing company using PowerBI and DAX. The dataset covers call records from 2018 to 2021, along with employee details, call types, and call charges. The main goal is to gain insights into call performance, employee efficiency, and cost management.

## Dataset Description
The dataset consists of the following tables:

### Call Charges:

- Call Charges 2018 (Min), Call Charges 2019 (Min), Call Charges 2020 (Min): Call cost per minute for the years 2018, 2019, and 2020.

### Employees:

- EmployeeID: Unique identifier for each employee.
- EmployeeName: Name of the employee.
- Site: Location of the employee's office.
- ManagerName: Name of the employee's manager.
  
### Call Type:

- CallTypeID: Unique identifier for the type of call.
- CallTypeDesc: Description of the call type.
  
### Call Data (2018-2021):

- CallTimestamp: Timestamp of the call.
- CallType: Type of the call.
- CallDuration: Duration of the call (in seconds).
- WaitTime: Time the caller waited before the call was picked up (in seconds).
- CallAbandoned: Indicates if the call was abandoned before it was answered.
  
## Objectives
- Analyze call costs over the years and detect trends.
- Evaluate employee performance based on metrics such as call duration, wait time, and call abandonment rates.
- Explore the relationship between call types and call outcomes (e.g., abandonment).
- Provide insights on cost efficiency and performance improvements using DAX measures and visualizations.
  
## Key Insights Explored
- Trends in call costs across different years.
- Employee productivity breakdown by site and manager.
- Analysis of call abandonment rates and wait times.
- Distribution of call types and their operational impact.
  
## Tools and Methods
- Power BI: Used for data visualization and reporting.
- DAX (Data Analysis Expressions): Used for advanced calculations and aggregations within Power BI.
- Data Model: Power BI's relational model was used to link tables and create meaningful insights.
