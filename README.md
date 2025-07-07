# Palmora-Group-Employee-Analysis-and-Dashboard
This project focuses on gender issues within the Palmora Group and its regions. It provides analyis and corresponding dashboard views using Microsoft Power BI Software. The project started with understanding the dataset, and removal of invalid rows, nomenclature of the undisclosed gender proper transformation of the tables and creation of calculated columns, after these exploratory data analysis was done.
# Introduction
The Dataset used consists of several features, ranging from quantitative to qualititative dsta categories. The following are labels of the data.
- Name
- Gender
- Department
- Salary
- Region
- Rating
- Department Rating
- Bonus Rate
- Annual Bonus
- Total Pay
- Salary Band
# Procedure 
The project passed a list of processes before completion. Taking the proper steps was a major requirement to generating sancroscant insights from the dataset. Below are the steps taken in the course of the project execution.
- Data Collection
- Data Transformation using power query
  - Removal of duplicate names
  - Assigning generic gender status, "Undisclosed", to staff whose genders were not disclosed
  - Assigning zero to a few empty cells
  - Removal of employees without salary because they have left the company
  - Removal of departments with null entries.
-  Feature Extraction
   - Merging of two queries Employee data and Bonus mapping to create two features
     1. Department/Rating
     2. Bonus Rate
   - Creation of calaculated columns from the datasets in order to generate more insisghts. Examples are:
     1. Salary band
     2. Total Pay
     3. Annual Bonus
- Dashboard Creation, using:
  - Pivot Table tool
  - Scatter plot
  - Bar Chart and,
  - Pie chart
# Results
The outputs of the project were exploratory data analysis, which consisted of graphs and charts of gender count, employee count, sum of salary, sum of annual bonus and total pay against regions, departments and salary band etc.  The following are conclusion derived from the EDAs.
- The Kaduna region has the highest gender count followed by Abuja. Lagos region has the least.
- The Kaduna region has the highest employee gender gap followed by Abuja. Lagos region has the least.
- Product management department has the highest gender and employee count across regions, followed by Legal deparment. Marketing has the least.
- The number of undisclosed gender status is greatest in Abuja, followed by Kaduna, then Lagos region.
- The number of undisclosed gender status is highest in the legal and engineering departments across the regions of Palmora group. It is least in the marketing department.
- The male gender is more than the female gender accross boards in the company. 
- The salary received is highest in Kaduna region and lowest in Lagos.
- The EDA reveals that the male category recieved more salary than the female gender across the regions. The undisclosed gender status received the least.
- Most employees were paid above 90,000 per year while the least were paid between 20,000 and 30,000 per year. etc.
