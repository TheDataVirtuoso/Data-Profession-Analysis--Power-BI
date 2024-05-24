# Data Professions Data Analysis

### Report Link :https://drive.google.com/file/d/1RCriVapA2zUtPVP7nV46q6WcosxKD7Jp/view?usp=sharing

## Problem Statement

Despite the growing appeal and lucrative opportunities within data professions, there remains a lack of comprehensive understanding regarding career transitions, compensation trends, and overall job satisfaction in the field. This gap in knowledge makes it challenging for aspiring data professionals to make informed career decisions and for organizations to attract and retain top talent. Additionally, there is a need to explore the geographical variations in pay and work/life balance, as well as the perceived difficulty of entering data professions. Addressing these issues through a detailed analysis of survey data will provide valuable insights and actionable recommendations to guide both individuals and organizations in navigating the evolving landscape of data careers effectively.

## Steps followed 


### 1. REQUIREMENTS GATHERING

###  - Identify Stakeholders
- Aspiring Data Professionals

- Current Data Professionals

- HR Departments
- Data-Driven organizations
- Job Market Platforms







### - Objectives
- Track Current Career Transitions and Compensation Trends

Monitor the number of individuals transitioning into data professions.

Analyze compensation trends across various data-related roles.

- Analyze Trends in Job Satisfaction and Work/Life Balance
Examine how job satisfaction levels and work/life balance have evolved over time.

Identify patterns in job satisfaction and work/life balance across different demographic groups (e.g., age, gender, geographic location).


- Detail Industrial and Demographic Profile Analysis

Analyze the distribution of data professionals across different roles and departments.

Investigate differences in job satisfaction and compensation based on job roles, educational background, and other demographic factors.

Explore how factors such as age, gender, and geographic location influence job satisfaction and compensation to identify key areas for intervention.

### - Scope of the Study



Includes tracking career transitions, analyzing compensation trends, and performing detailed analyses by Industry and demographic profiles.

Focuses on identifying patterns and trends to inform career decisions and organizational strategies.

### 2. DATA COLLECTION

- Data Source: Used a excel as a data connector to collect data.
- Loading Data: Loaded the data into Power BI for further processing and analysis.

### 3. DATA TRANSFORMATION

- Ensure Correct Data Types:
Verified that all data types are in the correct format.


- Data Validation:
Ensure that every row and Column has correct data

- Data Cleaning:
Split Column by Delimiter:

Split columns to separate and remove unwanted details in:

    Favorite Programming Language
    Job Title
    Country You Live In
    Industry You Work In
Finding Average Salary:

    Split Salary Range Column:
    Split the column containing salary ranges by separating digits from non-digits.
    Remove Unwanted Columns:
    Eliminate any columns that are not necessary for the analysis.
    Calculate Average Salary:
    Create a custom column to compute the average salary using the formula: 
 
         (Q1+Q3)/2.

 ### 4. DATA MODELLING
There was no need for data modeling as the data consisted of a single table.

 ### 5. DATA VISUALIZATION
1. Key Performance Indicators (KPIs):

    Total Number of Survey Responses:
Use the unique ID to count the total number of survey responses.

Snap of Total Number of Total Survey:

![1](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/9115d80a-92b4-4cb7-8be6-c3cd42a64647)

2.  Average Age
 
     Calculate the average age of the respondents.

Snap of Average Age:

![2](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/e8025291-a316-427a-9b96-ff503905b4ab)   

3.  Conversion to Data Profession:     
          

        In Power Query, create a   conditional column:
            Assign "Yes" for those  who converted to a data profession.
            Assign "No" for those who did not switch.
        Using a Conditional Column:
          If "Yes," then assign 1; if "No," then assign 0.
          Convert the data type from text to whole numbers.
          Calculate the summation of those who converted.





4. Visualization Creation:

-  Stacked Column Chart:

Display the total count by role and gender.

Snap of Stacked Column Chart

![5](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/bd2f5b52-a5f6-459f-a84c-6e4b496da74d)

-  Treemap:

Show the distribution of respondents by different countries.


Snap of Treemap.

![6](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/1043a187-b3ad-4db6-b0cb-45cea68437c3)

- Horizontal Bar Chart:

Illustrate the count of respondents by difficulty level of entering the data profession.

Snap of Horizontal Bar Chart

![7](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/5c2c9cb0-06eb-4b30-aead-f0e8e0242dc5)

-  Donut Chart:

Show the number of respondents who switched to data professions, segmented by gender.

Snap of Donut chart



-  Pie Chart:

Display the count of respondents by level of education.

Snap of Pie Chart

![10](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/37cc2a9b-b712-437d-912d-0a30fc1ca8bc)

-  Gauge Chart:
Measure satisfaction levels:

Happy with Salary

Happy with Work/Life Balance

Snap of Gauge Chart

![11](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/1e24ea41-3106-4728-806d-e6c95fbaee73)

![12](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/dba26291-0af5-40c9-bc2c-6219b717c7f4)


-  Slicer:
Add a slicer to filter visualizations by Industry Category. 

This allows users to dynamically view data and insights specific to different industry sectors.

![4](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/df91f9c8-eb27-459b-9332-6897f01149b5)



5. Build Aesthetics:

Canvas Background:
I changed the canvas background using MS PowerPoint to enhance the visual appeal.

I ensured that the background complemented the overall theme and was not too distracting.

6. Interactivity:

Edit Interactions:
I enabled edit interactions to ensure every visual was interactive with each other.
This ensured that selections in one visual filtered the data in the other visuals, providing a more dynamic and insightful user experience.

 # Report Snapshot (Power BI DESKTOP)

 
![DATA PROFESSION ANALYSIS](https://github.com/TheDataVirtuoso/CollinsBahati.github.io/assets/87636760/98fba0e7-45ed-4a25-9953-c5a53a6f8cff)


# Insights and Recommendations

A One page report was created on Power BI Desktop 

Following inferences can be drawn from the report;

### [1] Career Transitions:

   A significant portion, 372 respondents, have switched to a data profession, indicating a strong trend towards data-related careers.


    Recommendation: Aspiring professionals should consider transitioning into data-related fields 
    due to their growing popularity and opportunities.Organizations should facilitate this by 
    offering training programs and clear career pathways.
           
### [2] Highest Paying Professions:



  Data Science emerged as the highest paying profession, closely followed by Data Engineering. Data Analysis had the highest number of professionals, suggesting its widespread appeal and potentially lower entry barriers.


    Recommendation: Individuals should explore Data Science and Data Engineering roles 
    for higher earning potential. Educational institutions and training providers 
    should emphasize these areas in their curricula.
  
  ### [3] Satisfaction with Salary:
  
According to a gauge chart, the average satisfaction score regarding salary was 4.29, suggesting a generally positive sentiment among respondents about their earnings.


    Recommendation: Companies should maintain competitive salary packages to sustain high 
    levels of satisfaction. Regular salary reviews and transparent compensation policies 
    can help achieve this.

 ### [4] Geographical Insights:
The United States reported the highest pay across most data professions, indicating a lucrative market for data professionals in the US.


    Recommendation: Data professionals seeking higher salaries should consider opportunities 
    in the US. Companies outside the US should benchmark their salaries against US standards to
     attract and retain talent.


### [5] Ease of Entering the Profession:

The majority of respondents felt that breaking into the data profession is neither difficult nor easy, suggesting a moderate level of challenge.

    Recommendation: To ease the entry into data professions, educational 
    and training institutions should provide comprehensive, accessible programs. 
    Mentorship and internship opportunities can also help bridge the gap. 

### [6] Ease of Entering the Profession:

The majority of respondents felt that breaking into the data profession is neither difficult nor easy, suggesting a moderate level of challenge.

    Recommendation: To ease the entry into data professions, educational 
    and training institutions should provide comprehensive, accessible programs. 
    Mentorship and internship opportunities can also help bridge the gap. 
    
