# CMSC6950-Final-Project-Renea
## **Garments Worker Productivity**    
This repository contains the code and data used for analyzing and visualizing productivity in a garments factory. The project aims to explore relationships between various factors like team performance, productivity, and workforce distribution.  
### **Table of Contents**  
    1. Data source and column explanation
    2. Python Packages
    3. Steps to Reproduce Figures
    4. Generated Figures
    5. Tests  


### **Data source and column explanation**  
The dataset is from UCI machine learning repository and can be accessed [here](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees). We have to ensure that the dataset is placed in the root folder of this project with the correct name of the file of the dataset.  

### **Column definitions:**  
    1. date : Date in MM-DD-YYYY
    2. day : Day of the Week
    3. quarter : A portion of the month. A month was divided into four quarters
    4. department : Associated department with the instance
    5. team_no : Associated team number with the instance
    6. no_of_workers : Number of workers in each team
    7. no_of_style_change : Number of changes in the style of a particular product
    8. targeted_productivity : Targeted productivity set by the Authority for each team for each day.
    9. smv : Standard Minute Value, it is the allocated time for a task
    10. wip : Work in progress. Includes the number of unfinished items for products
    11. over_time : Represents the amount of overtime by each team in minutes
    12. incentive : Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action.
    13. idle_time : The amount of time when the production was interrupted due to several reasons
    14. idle_men : The number of workers who were idle due to production interruption
    15. actual_productivity : The actual % of productivity that was delivered by the workers.  

### **Python Packages**  
    • pandas
    • numpy
    • matplotlib
    • seaborn  

**Install these dependencies using the command:**  
`bash`  
`pip install pandas numpy matplotlib seaborn`  

# **Steps to Reproduce Figures**  
**Follow these steps to generate the visualizations:**  

## **1. Clone the Repository**  
Download or clone this repository:
`bash`  
`git clone [https://github.com/Renea-Chowdhury/CMSC6950-Final-Project-Renea.git]`  
`cd CMSC6950-Final-Project-Renea`  

OR 
Download the file ***project-Cmcs_final.ipynb***  

## **2. Ensure Dataset Availability**  
Place the dataset *garments_worker_productivity.csv* in the repository folder. The expected file path is:  
`bash`  
`./garments_worker_productivity.csv`  

OR  
Download the dataset ***garments_worker_productivity.csv***  

## **3. Run the Main Analysis Script**  
The main script performs data loading, cleaning, analysis, and visualization.
Run the script with:
`bash`  
`python main.py`

OR  
Run the file *project-Cmcs_final.ipynb* after ensuring the correct path of *garments_worker_productivity.csv* in your device   

## **4. Reproducing Figures**  
It will generate some bar plots, histograms and line graphs  

# **Tests**  
The script includes basic tests to validate the dataset and calculations:  
    • Column Name Test: Ensures critical columns like team and actual_productivity are present.  
    • Data Type Test: Validates that key columns have numeric data types.  
    • Metric Calculation Test: Verifies the correct computation of the achievement_rate.  

*Run the tests automatically by executing:*  
`bash`  
`python main.py`  
Test results will appear.    
Or    
You can download the file *Test_garments_worker_productivity.ipynb* and run the file along with the *project-Cmcs_final.ipynb*  


