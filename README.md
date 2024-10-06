Advanced Data Analytics - Portfolio Project
Project Overview
This repository contains all the essential components for the Advanced Data Analytics portfolio project, including the transformed dataset, Power BI file, research questions, and presentation materials. The project focused on analyzing large datasets using big data technologies, such as SnowSQL, for data transformation, with visualizations created using Power BI.

Sections
A. Data Analysis (75%)
Research Questions: Five research questions were clearly formulated based on the provided dataset.
Dataset Creation: The dataset was merged using SnowSQL and SQL queries.

Data Preprocessing:
Initial cleaning and preprocessing of the dataset were performed using Excel. The dataset was initially combined in a single sheet and was separated into individual tables based on the year.
In SnowSQL, a database and schema were created, and the separated tables were imported. The tables from different years were then merged into one using the UNION function.
Missing values were handled, duplicates removed, data types validated, and formatting adjustments made on SnowSQL.
After preprocessing, the dataset was transformed in Power Query for further refinement before visualization. Due to the large size of the dataset, semicolons were used as delimiters during the import to properly split the data into separate columns.

Visualization: Data visualizations were created using Power BI after the transformation in Power Query was completed.

Project Structure
data/: Contains the transformed dataset (Transformed_Data_FinalProject.csv).
notebooks/: Contains notebooks with data cleaning, analysis, and dataset creation processes.
visualizations/: Contains the Power BI file.
presentation/: Contains the project presentation materials:
Oke_Deborah_PowerBi_Presentation.pbix – Power BI file showcasing the presentation.
Issues_and_Solutions_in_Big_Data_Technologies.pptx – PowerPoint presentation on issues and solutions in big data technologies.

