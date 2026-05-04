# MIST4610-Project2

# Team Information
Hailey Brakke (https://github.com/haileybrakke/MIST4610-project2)

Will Federer (put link here)

Summer Sayedzada (put link here)

Tony Jimenez (put link here)

Ja’Khiyan Dowdy (https://github.com/jakhiyan0219-hub/MIST4610-Project2.git)

# Our Dataset

The dataset used for this analysis is the U.S. Chronic Disease Indicators dataset, obtained from Data.gov and originally compiled by the Centers for Disease Control and Prevention (CDC). This dataset provides comprehensive, state-level data on a wide range of chronic health conditions and risk factors across the United States. The dataset has 34 columns and over 300,000 rows. Data can be analyzed across several dimensions, including time (year), geography (state), health condition (indicator), and demographics. 

Key Columns and Data Types:  
Year (Numerical): The year data was collected   
Location (String): The U.S. state where data was collected   
Question (String): Describes the specific health indicator being measured  
Data Value (Numerical): The number associated with the specific health indicator   
Data Value Unit (String): Specifies the unit of measurement    
Stratification Category (String): Collects demographic information   
Stratification (String): Collects more specific demographic breakdowns within the category   
Geolocation (Geographic values): Specifies the exact location data was collected   

We are basing our analysis on geographic variation and demographic disparities in colorectal cancer screening across U.S. states. The team chose to analyze colorectal cancer for two reasons: 

1. Amount and depth of colorectal cancer data in the dataset. The dataset includes data on screening rates and mortality rates by location, year, data value type, and stratification group, which makes it possible to study both statewide patterns and disparities across groups.
2. Colorectal cancer prevalence within the United States. Recently, colon cancer has been the subject of many news articles due to the increase in number of cases, especially in young people. As of 2026, about 1 in 25 men and 1 in 26 women will develop colorectal cancer (Cancer Research Institute).


# Question 1

How do colorectal cancer screening rates vary across U.S. states, and which regions consistently show the lowest screening rates?     
Importance: This question is important because geographic variation in screening rates can reveal differences in access to preventive healthcare, public health outreach, insurance coverage, healthcare infrastructure, and awareness across different parts of the country. Colorectal cancer screenings are immensely important for the mortality of a patient, reducing death by up to 73% (American Cancer Society). Understanding which areas have low screening rates is important to realize where to focus education efforts on colorectal cancer screenings.

# Question 2

How do colorectal cancer screening rates differ by race/ethnicity across U.S. states, and where are the largest disparities?   
Importance: This question is critical because racial and ethnic disparities in screening rates reflect the difference in healthcare access, quality of care, and societal determinants of health. While screening can reduce colorectal cancer mortality by up to 73%, these benefits are not distributed equally, which is shown by the difference in the screening rates.

# Manipulations Applied to Dataset

Question 1: For Question 1, we used Excel’s Transform feature to narrow the original U.S. Chronic Disease Indicators dataset to only the records needed for colorectal cancer screening analysis. We filtered the data to the Cancer topic, selected “Colorectal cancer screening among adults aged 45–75 years,” kept only Age-adjusted Prevalence and Overall values, limited the data to 2020 and 2022, and removed non-state locations so the dataset matched our focus on U.S. states. We also created a new Region column that grouped states into the Northeast, Midwest, South, and West. Finally, we kept only the columns needed for analysis and visualization, resulting in a clean dataset ready for Tableau.

Question 2: For Question 2, we utilized the same data tranfromation from question 1, we just added the stratification column which included Race/Ethnicity and the description for race and ethnicity.The dataset utilized the same years,and same topics as stated for question 1, leaving us with another clean dataset.


# Question 1 Analysis
<img width="1374" height="888" alt="Screenshot 2026-05-02 at 9 58 57 PM" src="https://github.com/user-attachments/assets/127a6740-05e7-4241-97ad-48fc15e8022b" />


# Question 2 Analysis
<img width="1231" height="801" alt="Screenshot 2026-05-04 at 5 11 01 AM" src="https://github.com/user-attachments/assets/3a529df4-f083-49f3-865e-d6b8882be45f" />

<img width="1229" height="778" alt="Screenshot 2026-05-04 at 5 12 31 AM" src="https://github.com/user-attachments/assets/8d49ac46-19ca-4024-8b4a-00cbfb30a18e" />



