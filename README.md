
# 1853 Stockholm Cholera Outbreak
 
### Dashboard Presentation Link : https://www.linkedin.com/posts/maria-imuede-a7230152_powerbi-activity-7111590327534145536-_OEf?utm_source=share&utm_medium=member_desktop

![Cholera](https://github.com/MariaImuede/MY-Project/assets/159175444/65e9d839-953b-4b43-8677-9a797c3fc6dc)

## Problem Statement

The 1853 Stockholm Cholera Outbreak presents a historical epidemiological challenge, requiring a comprehensive analysis to understand the factors contributing to the outbreak and its impact on the population. The goal is to examine the spread of the disease, identify key patterns and trends in morbidity and mortality rates, and explore potential correlations with factors such as sanitation practices, water sources, and socio-economic conditions. By delving into the historical context and analyzing available data, the objective is to gain insights that can inform public health strategies and interventions to mitigate the spread of cholera and prevent similar outbreaks in the future.



### Steps followed 

- Step 1 : Open Power BI Desktop and select "Get Data" from the Home tab.
Choose "Text/CSV" and navigate to the location of the CSV file containing the data related to the 1853 Stockholm Cholera Outbreak.
Select the CSV file and click "Open" to import the data into Power BI.

- Step 2 : Once the data is imported, Power BI will display a preview of the data. Review the data and click "Load" to load it into Power BI.
In the Query Editor, perform data cleaning and transformation tasks such as removing duplicates, handling missing values, and standardizing formats as needed.

- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

- Step 4 : Create visualizations by selecting fields from the Fields pane and dragging them onto the canvas. Choose appropriate visualization types such as charts, graphs, and maps to represent the data effectively.

- Step 5 : In the report view, under the view tab, theme was selected.

- Step 6 : Visual filters (Slicers) were added for four fields named "Death Count", "Total Profession", "Average age at death".
- Step 7 : Visuals were added to the canvas, one representing total death by age group, top 10 death by profession, average death age by month and total death by qtr and month
Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation for average death by month.
           
- Step 8 : New measures were created 

a. Total Death count was 248 = Total Case = COUNT('cholera-katarina-1853'[Name])

b. A total of 151 individuals from various professions fell victim to the outbreak.
Total Profession = DISTINCTCOUNT('cholera-katarina-1853'[Profession])

c. Total gender
Total Gender = DISTINCTCOUNT('cholera-katarina-1853'[Gender])


  - Step 9 : The report was then published to Power BI Service.
 
 


 # Report Snapshot (Power BI DESKTOP)

 

![Cholera Outbreak](https://github.com/MariaImuede/MY-Project/assets/159175444/8776fa93-2fd8-4d5e-8ae5-33d77189541b)


# Insights

During the outbreak, there were 248 reported cholera-related deaths
A total of 151 individuals from various professions fell victim to the outbreak.
The average age at the time of death was 34 years old.

Age Group Distribution: Cholera deaths were distributed across different age groups:
Older Adults (40%)
Adults (24%)
Children (24%)
Senior Citizens (10%)

The average age at death varied by month:
August: 41 years
September: 34 years
October: 33 years
November: 29 years


September recorded a significant spike in deaths, with 178 individuals succumbing to cholera.
October saw 41 deaths.
November had the lowest death count, with only 8 cases.

Gender Distribution: The gender distribution of cholera-related deaths was as follows:

Female: 52%
Male: 48%

Recommendations:
Understanding historical disease outbreaks can provide valuable insights for public health. While we can't change the events of the past, we can draw lessons from them to better prepare for future health crises:

1. Improved Sanitation: Invest in improved sanitation infrastructure and hygiene practices to prevent the spread of waterborne diseases like cholera.


2. Public Health Awareness: Promote public health awareness campaigns to educate the population on disease prevention, symptoms, and early intervention.

3. Medical Preparedness: Ensure that healthcare facilities are adequately prepared with medical supplies, treatments, and trained personnel to respond swiftly to outbreaks.

5. Vaccination Programs: If available, consider vaccination programs as an additional layer of defense against cholera and similar diseases.

By learning from historical events like the 1853 Stockholm cholera outbreak, we can work towards a healthier and more resilient future Men: 48%

