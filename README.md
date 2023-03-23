# Crowdfunding ETL Project
![image](https://user-images.githubusercontent.com/120426753/227378892-f971fd18-b088-420a-8ded-02d2d4ff51a2.png)

## For this project, a raw dataset was provided showing details for various crowdfunding projects around the world. The goal was to extract, transform, and load specific values to conduct the data analysis. Python, Pandas, and Python Dictionary methods were used to extract and transform the data. Afterwards, the newly transformed DataFrames were saved into .csv files and uploaded into PostgreSQL using the pgAdmin client.  
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### First, four separate DataFrames were created using Python. For the first DataFrame created, the categories were extracted from the original crowdfunding dataset. A column was added to show a distinct category ID for each category.

![image](https://user-images.githubusercontent.com/120426753/227072781-421cbb5e-5923-43cf-9029-3f9521bdfc71.png)
#### The "Category" DataFrame was extracted into a .csv file.
#### [Category.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/category.csv)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The second DataFrame was created and the subcategories were extracted from the original crowdfunding dataset and a column was added to show a distinct subcategory ID.

![image](https://user-images.githubusercontent.com/120426753/227073290-5b4e6add-0c9c-4ebe-aeab-9843d4bc481b.png) 
#### The "Subcategory" DataFrame was extracted into a .csv file.
#### [Subcategory.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/subcategory.csv)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The third DataFrame was created to merge the newly created category and subcategory DataFrames with the original dataset. Some unwanted columns were dropped and data types for each column were updated accordingly. The column names were updated accordingly as well.

![image](https://user-images.githubusercontent.com/120426753/227076101-5a1c106a-822a-40ea-8fba-8bf49ade3bea.png)
#### The new "Campaign" DataFrame was extracted into a .csv file.
#### [Campaign.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/campaign.csv)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The data for the fourth DataFrame to be created was extracted from a supplied excel dataset. After using Pandas to extract the data, the first step was to clean up the data due to the original dataset having all the separate values inside one column. To do this, Python dictionary methods were used to extract the data into a list and then placed into an empty dictionary. From there, columns were added to place the separated dictionary list into their appropriate columns. After adding a few columns and confirming the correct datatypes for each column, the final DataFrame was completed. Below shows the before and after for the contacts dataset.

Before:                                                                                                           |  After:
:----------------------------------------------------------------------------------------------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/120426753/227373916-66c7b903-34db-4be0-aa42-0dc044e9a1cf.png)  |  ![image](https://user-images.githubusercontent.com/120426753/227374259-8d5f382e-e2ac-491d-af01-3bd90ede7253.png)

#### The "Contacts" DataFrame was extracted into a .csv file. 
#### [Contacts.csv](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Resources/contacts.csv)

##### [Final Python Code](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/ETL_Mini_Project_Starter_Code-checkpoint.ipynb)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The last step for this project was to sketch an ERD and create tables in PostgreSQL using the pgAdmin client. The previously created .csv files were imported into the tables in pgAdmin. Below shows the ERD created using QuickDBD.

![image](https://user-images.githubusercontent.com/120426753/227376865-afa02221-867c-4045-86e9-cf0ccc8c67bc.png)
#### [Final SQL Code](https://github.com/rvafaeis/crowdfunding_ETL_project2/blob/main/Crowdfunding_db_Schema.sql)


