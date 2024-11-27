# CMSC6950-Final-Project-Renea
## **Garments Worker Productivity**    
This repository contains the code and data used for analyzing and visualizing productivity in a garments factory. The project aims to explore relationships between various factors like team performance, productivity, and workforce distribution.  
### **Table of Contents**  
    1.	Data source and column explanation
    2.	Python Packages
    3.	Steps to Reproduce Figures
    4.	Generated Figures
    5.	Tests  


### **Data source and column explanation**  
The dataset is from UCI machine learning repository and can be accessed [here](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees). We have to ensure that the dataset is placed in the root folder of this project with the correct name of the file of the dataset.  

### **Column definitions:**  
    1.	date : Date in MM-DD-YYYY
    2.	day : Day of the Week
    3.	quarter : A portion of the month. A month was divided into four quarters
    4.	department : Associated department with the instance
    5.	team_no : Associated team number with the instance
    6.	no_of_workers : Number of workers in each team
    7.	no_of_style_change : Number of changes in the style of a particular product
    8.targeted_productivity : Targeted productivity set by the Authority for each team for each day.
    9.	smv : Standard Minute Value, it is the allocated time for a task
    10.	wip : Work in progress. Includes the number of unfinished items for products
    11.	over_time : Represents the amount of overtime by each team in minutes
    12.	incentive : Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action.
    13.	idle_time : The amount of time when the production was interrupted due to several reasons
    14.	idle_men : The number of workers who were idle due to production interruption
    15.	actual_productivity : The actual % of productivity that was delivered by the workers.  

### **Python Packages**  
    • pandas
    • numpy
    • matplotlib
    • seaborn  

**Install these dependencies using the command:**  
`bash`
`pip install pandas numpy matplotlib seaborn`  



