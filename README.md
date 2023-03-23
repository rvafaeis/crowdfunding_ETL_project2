# Crowdfunding ETL Project
## For this project, a raw dataset was provided showing details for various crowdfunding projects around the world. The goal is to extract, transform, and load specific values to conduct the data analysis. Python, Pandas, and Python Dictionary methods were used to extract and transform the data. Afterwards, the newly transformed DataFrames were saved into .csv files and uploaded into PostgreSQL using the pgAdmin client.  
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### First, four seperate DataFrames were created using Python. For the first DataFrame created, the categories were extracted from the original crowdfunding dataset. A column was added to show a distinct category ID for each category. The data was extracted into a .csv file.

![image](https://user-images.githubusercontent.com/120426753/227072781-421cbb5e-5923-43cf-9029-3f9521bdfc71.png)
#### [Category.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/category.csv)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The second DataFrame was created and the subcategories were extracted from the original crowdfunding dataset and a column was added to show a distinct subcategory ID. The data was extracted into a .csv file.

![image](https://user-images.githubusercontent.com/120426753/227073290-5b4e6add-0c9c-4ebe-aeab-9843d4bc481b.png) 
#### [Subcategory.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/subcategory.csv)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The third DataFrame was created and to merge the newly created category and subcategory DataFrames were extracted from the original dataset. Data types for each column were updated accordingly and some column names were updated as well. 

![image](https://user-images.githubusercontent.com/120426753/227076101-5a1c106a-822a-40ea-8fba-8bf49ade3bea.png)
#### [Campaign.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/campaign.csv)
