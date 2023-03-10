# Crowdfunding_ETL
```
## Building an ETL pipeline using Python, Pandas, and Python dictionary methods to Transform Data 
```
> #### *Collaborators: Lorela Cabral, Luis Hernandez, Mohammad Arab, Drew Barnhart, and Anna Remler*
```
## Background
```
Within this collaborative effort we transformed data utilizing an ETL Pipeline process using Python and Pandas methods. Initially we were provided data in excel workbooks (located witin the resources folder: Contacts & Crowdfunding). Our goal was to process and read this data, eventually providing it within a CSV file. 
```
## Objectives
```
The objectives for this process were divided into several subsections: 

- Create the Category and Subcategory DataFrames
- Create the Campaign DataFrame
- Create the Contacts DataFrame
- Create the Crowdfunding Database


## Steps

### Step 1. Extract and transform the crowdfunding.xlsx Excel data

<img width="780" alt="image" src="https://user-images.githubusercontent.com/116226080/224200936-4bf5a943-8756-4049-9d39-1c090752d800.png">

### Step 2: Create the Category and Subcategory DataFrames
  - After creation of these data frames we exported them as CSV Files (*category.csv & subcategory.csv*)

<img width="427" alt="image" src="https://user-images.githubusercontent.com/116226080/224203139-7925e344-f4c1-4fdd-a289-18f925ec85c4.png">


### Step 3: Creted a campaign DF with specified columns
  - These included :cf_id, contact_id, company_name, blurb, goal, pleadged, and 8 other columns (*depicted below*)
  - Merged the campaign_df with the category_df on the "category" column and the subcategory_df on the "subcategory" column. 
  - utilized .drop() function to remove unwanted columns
  
<img width="809" alt="image" src="https://user-images.githubusercontent.com/116226080/224203218-8e4ddb1b-0016-4ad3-a70f-4d7f2252b8b2.png">

### Step 4: Exported Campaign DF to CSV
  - utilized following code to create campaign csv. 

<img width="801" alt="image" src="https://user-images.githubusercontent.com/116226080/224204109-513aee46-9f4d-4078-8617-02d2c3bfbdca.png">





### Software Used:

> - Python
> - SQL
> - Pandas
> - Numpy


### Functions used: 

> - Print
> - To_csv 
> - Iterrows
> - strftime
> - Copy
> - Rename
> - Info
> - Merge
> - Drop
> - As_type
> - info


# Schema Diagram

### Exported from QuickDBD: https://www.quickdatabasediagrams.com/

<img width="559" alt="Screenshot 2023-03-08 190228" src="https://user-images.githubusercontent.com/116226080/223905655-377f716b-51c6-4d7c-acd8-73382eddf430.png">

<img width="647" alt="Screenshot 2023-03-08 190146" src="https://user-images.githubusercontent.com/116226080/223905771-dddcd92c-99a4-44ed-87b6-0b266febcba6.png">


<img width="636" alt="Screenshot 2023-03-08 190205" src="https://user-images.githubusercontent.com/116226080/223905729-4b2d49b5-9d83-4235-be63-5b91522e736a.png">










