 kickstarter projects

Data Source: Two CSV Files (2016,2018) from (kaggle)
https://www.kaggle.com/kemical/kickstarter-projects


1- Data Transformation:
- Create Custom Column has the file name (ex: 2016 or ks-projects-201612) (M Language)
- Append (Union) two files using M Language (Power Query)
- Rename the table with the whole data with a clear name (AllDate).
- Remove or hide other table/tables based on the steps.

Modeling:
- Create Hierarchy ( Main Category, Category and Project Name) Called it "Project Category Hierarchy"  
- We can hide the unneeded tables or rename tables.
- Number of Projects Measure
- Number of Backers Measure
- Total Pledged Measure 
- Total Goal Measure

Visuals: (Use Measures)
- Number of Projects (# Projects) Card
- Number of Backers Card
- Total Pledged Card
- Total Goal Card

- # Projects by State
- # Projects by Category Hierarchy (Drill Down)
- # Projects by launched
- Total Pledged by Country
