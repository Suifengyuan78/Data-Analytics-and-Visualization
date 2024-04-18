
#                                Social-Buzz

## Task: The popularity analysis for Social Buzz
 Identifies the top user preferences, particularly the top 5 categories with the highest aggregate popularity, informing content strategies for optimal user engagement.

## Data Sources
### Data model
 <img width="515" alt="Screenshot 2024-04-18 171721" src="https://github.com/Suifengyuan78/Social-Buzz/assets/167149285/0f84b55e-ce76-4143-8560-b1c38cc49f98">

- "Reaction Types.csv" [Download Here]( https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298399720/ReactionTypes.csv)
- "Reactions.csv" [Download Here](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298375459/Reactions.csv)
- "Content.csv" [Download Here](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298350004/Content.csv)

## The following steps were taken in this analytics process:
### 1. Identify relevant datasets:
Use this data model to identify which datasets will be required - “Reaction”, ”Content”, and ”Reaction Types”. 

### 2. Data Cleaning: 
- Removing rows that have values which are missing,
- Changing the data type of some values within a column, and
- Removing columns which are not relevant to this task.

### 3. Data Modelling: 
- Using the Reaction table as the base table. 
- "Content” link “Reaction” via Content ID;
- “Reaction” link ”Reaction Types” via ReactionType. 
- “VLookUp” formula is used here.

### 4. Data Sum and Order: Sum up scores for each category and order them, find the top 5 performing categories.
- Add up the total scores for each category.
- The “Sum If” formula is used here.

### 5. Data Visualizing: Visual the findings.

 
## Tools: 
- Excel 
- PowerBI desktop
- PowerBI Service

## Final Reports
