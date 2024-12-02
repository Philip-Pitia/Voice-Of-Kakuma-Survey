# Voice-Of-Kakuma-Survey
README for Analysis of "The Voice of Kakuma Survey Data Cleaning" Dataset
________________________________________
Project Overview
This project analyzes "The Voice of Kakuma Survey Data Cleaning" dataset. The dataset includes responses from participants on various aspects such as country of origin, reasons for migration, and other socio-economic details. The analysis is conducted in Microsoft Excel and R, with insights derived through cleaning, summarization, and visualization.
________________________________________
Dataset Description
The dataset comprises multiple sheets:
1.	Sheet1-Sheet4: Aggregated data, including summaries of responses categorized by questions like "COUNTRY OF ORIGIN" and "WHY DID YOU LEAVE YOUR COUNTRY OF ORIGIN?".
2.	Form Responses 1: Raw survey data with individual responses.
________________________________________
Excel Workflow
1.	File Name: THE VOICE OF KAKUMA SURVEY Data Cleaning.xlsx
2.	Analysis Sheet:
o	Contains pivot tables, charts, and summary statistics based on the survey data.
o	Key insights such as counts, averages, and distributions are calculated.
3.	Formulas Sheet:
o	Stores the Excel formulas used for calculations (e.g., =COUNTIF(), =SUM(), =AVERAGE()).
o	Example formulas:
	=COUNTIF('Form Responses 1'!B:B, "Kenyan") to count respondents from Kenya.
	=AVERAGE('Form Responses 1'!D:D) to calculate average responses for a numeric question.
4.	Steps for Use:
o	Open the file in Excel.
o	Review the Analysis sheet for summaries.
o	Refer to the Formulas sheet for understanding calculations.
o	Update the Form Responses 1 sheet if new data is added; the formulas automatically update insights.
________________________________________
R Workflow
1.	R Script File: kakuma_analysis.R
2.	Steps in the R Script:
o	Data Import: Load data from all sheets using readxl.
o	Data Cleaning:
	Replace missing values with "Unknown".
	Remove empty rows and columns.
o	Summarization:
	Aggregate data by country of origin.
	Analyze reasons for migration.
o	Visualization:
	Create bar plots for country distributions.
	Plot reasons for migration.
o	Export:
	Cleaned data and summaries are saved to new Excel files using writexl.
3.	Requirements:
o	R (version 4.0+)
o	Packages: dplyr, ggplot2, readxl, writexl
4.	How to Run:
o	Set the file path in file_path.
o	Run the script using an R editor (e.g., RStudio).
o	Output files:
	Cleaned_VOICE_OF_KAKUMA_SURVEY_Data.xlsx: Cleaned data.
	Summary_VOICE_OF_KAKUMA_Data.xlsx: Summarized insights.
________________________________________
File Outputs
1.	Excel Outputs:
o	Updated dataset with analyses and formulas stored in separate sheets.
o	Key insights visualized through pivot tables and charts.
2.	R Outputs:
o	Cleaned dataset with missing data handled.
o	Summary Excel files with aggregated insights.
o	Bar plots showing data distributions.

