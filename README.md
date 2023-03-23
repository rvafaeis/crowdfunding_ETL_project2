# Crowdfunding ETL Project
## For this project, a raw dataset was provided showing details for various crowdfunding projects around the world. The goal is to extract, transform, and load specific values to conduct the data analysis. Python, Pandas, and Python Dictionary methods were used to extract and transform the data. Afterwards, the newly transformed DataFrames were saved into .csv files and uploaded into PostgreSQL using the pgAdmin client.  
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### First, four seperate DataFrames were created using Python. For the first DataFrame created, the categories were extracted from the original crowdfunding dataset. A column was added to show a distinct category ID for each category. The "Category" DataFrame was extracted into a .csv file.

![image](https://user-images.githubusercontent.com/120426753/227072781-421cbb5e-5923-43cf-9029-3f9521bdfc71.png)
#### [Category.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/category.csv)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The second DataFrame was created and the subcategories were extracted from the original crowdfunding dataset and a column was added to show a distinct subcategory ID. The "Subcategory" DataFrame was extracted into a .csv file.

![image](https://user-images.githubusercontent.com/120426753/227073290-5b4e6add-0c9c-4ebe-aeab-9843d4bc481b.png) 
#### [Subcategory.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/subcategory.csv)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The third DataFrame was created to merge the newly created category and subcategory DataFrames with the original dataset. Some unwanted columns were dropped and data types for each column were updated accordingly. Column names were updated as well. The new "Campaign" DataFrame was extracted into a .csv file.

![image](https://user-images.githubusercontent.com/120426753/227076101-5a1c106a-822a-40ea-8fba-8bf49ade3bea.png)
#### [Campaign.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/campaign.csv)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The data for the fourth DataFrame to be created was extracted from a provided excel dataset. After using Pandas to extract the data, the first step was to clean up the data due to the original dataset having all the seperate values inside one column. To do this, Python dictionary methods were used to extract the data into a list and then placed into an empty dictionary. From there, columns were added to place the seperated dictionary list into their appropriate columns. After adding a few columns and confirming the correct datatypes for each column, the final DataFrame was completed. The "Contacts" DataFrame was extracted into a .csv file. Below shows the before and after for the contacts dataset.

Before:                                                                                                           |  After:
:----------------------------------------------------------------------------------------------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/120426753/227373916-66c7b903-34db-4be0-aa42-0dc044e9a1cf.png)  |  ![image](https://user-images.githubusercontent.com/120426753/227374259-8d5f382e-e2ac-491d-af01-3bd90ede7253.png)

#### [Contacts.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/contacts.csv)



