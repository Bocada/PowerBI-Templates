Copyright © 2023 Bocada LLC All Rights Reserved.

# PowerBI-Templates

This repository contains the Power BI reports for Bocada. 
•	Readme.txt
•	Bocada_*.pbit per each bi template report.
	

Requirement
The template only works in the release of Bocada 22.3.12 or later.
Power BI online Service needs to have access to Bocada Database to refresh the dataset.

Step 1: open Power BI desktop. From File Menu select Import Template and select the file downloaded with extension “pbit”.
 
Step 2: enter SQL Server Name and Bocada database name and click Load.
 
Step 3: enter SQL Server Database credentials and click on Connect.
 
Step 4: after the data is loaded, there’re available five pages with different Bocada reports
Backup Page: 
•	Backup Health
•	Backup Health Trends
•	Backup Trends
•	Backup Duration Trends
•	Backup Error Trends
•	Restore Health
Storage Page:
•	Storage Trends
Data Domain Page:
•	Data Domain Utilization
•	Data Domain Utilization Trends
•	Data Domain MTree Trends

Store Once Page:
•	Store Once Utilization
•	Store Once Dedup Trends
Vast Page:
•	VAST Utilization
•	VAST Utilization Trends

Step 5: modify and save the reports as .pbix files.
Step 6: publish the reports online in the Power BI Service. When the reports are published, power BI will create the dataset. 
Remember adding a schedule to your dataset to refresh the data in our Power BI instance. 

