#raw data source:https://www.kaggle.com/datasets/bhuviranga/customer-churn-data
##Dashboard link:https://public.tableau.com/app/profile/solomon.kure/viz/BankCustomerChurnPrediction_17289109640440/Dashboard1?publish=yes
### Problem Statement
-Displaying an overview of the estimated salary for 3 countries
-Analysing which age group has the highest customer that are liable to churn
-Creation of box and whisker visualizations for age,active members and balance

Sheet 1
-The text file was loaded i.e Bank Customer Churn Prediction.csv
-On the Show Me Panel and clicked on Symbol Maps 
-I went to Marks Panel and used drag and drop to drop Country and enabled Text and Estimated Salary and enabled Text
-I finally labelled it as "A Map Displaying Each Country With its Corresponding Estimated Salary"

Sheet 2
-Using darg and drop from Tables Panel i dragged and dropped Churn on rows and then went to Age  and right clicked on it and went to
create  and picked Bins which created bin bars of interval of 5 bins each
-On Marks Panel i dragged and dropped Age(bin) and enabled color 
-From the bar chart people within the Age range from 35-45 years were more likely churn especially those from 40-45 years
-People from the age range of 15-30 years and from 55-80 years of age were less likely to churn
-Finally labelled as "Relationship of Ages of People who were likely to churn based on preference"

Sheet 3
-From Tables panel using drag and drop
 -dropped Age(bin) on columns 
 -dropped SUM(Active Member) and VAR(Balance) on rows
 -On Marks Panel dropped Product Number and enabled details
 -I finally saved the graph as "Box & Whisker Graph indicating Age,Active Member & Balance"
