# Call-Centre-Performance

![call-center image](https://github.com/user-attachments/assets/c6d96385-2e78-4167-a3f0-36e9d0f8eed2)
---

## Introduction
This is a power BI project on call centre analysis of an imaginary company.The project is to analyze and derive insights to answer crucial questions and help the company madata driven decisions.

**_Disclaimer_** : _All datasets and reports do not represent any company or country,but just a dummy dataset to demonstrate capabilities of power BI._


## Data Set

In this analysis, the dataset employed is comprised of a single data file in Microsoft Excel Worksheet (.xlsx) format. Each row within this dataset represents unique customer details, while the columns encompass diverse attributes related to the call center. The structure of these datasets is designed with columns that house a multitude of information pertaining to each individual customer record. Below is the screenshot of the dataset.

![raw data image](https://github.com/user-attachments/assets/795c9162-0a2d-44c8-9bce-c82945c5ccb9)


## Data Cleaning

The dataset underwent a transformation process within Power Query Editor to ensure data integrity. Several checks and adjustments were made: Duplicate Entries: A thorough examination for duplicate entries was conducted to maintain dataset integrity. No duplicates were identified. Data Type Corrections: Incorrect data types for certain columns were adjusted to align them with their intended purpose. Blank Cells: A few blank cells were identified and filled with zero to enhance the accuracy of the findings. Categorical Data Enhancement: To improve precision, categorical data was enhanced:  "Y" in the "Resolved" column was substituted with "Resolved," and "N" was replaced with "Not Resolved." These steps were taken to optimize the dataset for further analysis and to ensure that the data accurately reflects the intended information. Below is a screenshot of the transformed dataset.
![calls resolved](https://github.com/user-attachments/assets/78feb58f-e90e-4f52-8d00-ff7102048528)


## The Key Performance Indicators (KPIs)
1. Total agent 
2. Top 1 agent who got highest satisfaction rate.
3. Total % of the calls been answered and total % of calls been rejected.
4. calls been resolved and not resolved.
5. Top 1 agents who answered maximum calls.
6. Durations on calls by every agent.
7. slicers to interact with other charts by month and day wise.
8. Total number of calls.
9. New column to calculate total number of calls answered and total number of calls been rejected.

## Skills/ concepts demonstrated:

The following Power Bi features were incorporated:
- Bookmarking,
- Quick neasures,
- New column
- Page navigation,
- Modeling,
- Filters,
- Tooltips,
- Button,

## Call Rejected:

A doughnut chart was employed to illustrate the distribution of total calls rejected by agent, showcasing the proportion of calls rejected by agents. This was achieved by including the "rejected" column in both the legend and value sections of the visualization, utilizing the if function to tally call rejected cases.
Below is a screenshot of the resulting visualization:

![call rejected](https://github.com/user-attachments/assets/660faedc-aa92-4f32-96cf-7e3aaacb184e)

## Total calls by month:

To compute the total call by month, I initiated the process by selecting the "Area chart" option within the "Build Visual" section of the visualization menu. Next, I dragged the "total call" and "month" column into the "Fields" section.
Below is a screenshot of the resulting visualization:

![total call by month](https://github.com/user-attachments/assets/a7467d4e-c519-4a4d-8112-aa58dbd2bfe0)

## Month and date:

To compute month and date, I initiated the process by selecting the "slicer" option within the "Build Visual" section of the visualization menu. Next, I dragged the "date " column into the "Fields" section. Below is a screenshot of the resulting visualization:


![slicer 2](https://github.com/user-attachments/assets/a73d0863-41ef-489e-9e26-8f73c9a8ce09)
![slicer 1](https://github.com/user-attachments/assets/442cb0fa-98ff-4996-bbc9-d19d99df7109)


## Total calls by resolution:

A column chart was employed to illustrate the distribution of complaints among various customers, showcasing the proportion of resolved and unresolved complaints by customers. This was achieved by including the "resolution" column in both the legend and value sections of the visualization, utilizing the if function to tally both resolved and unresolved cases.
Below is a screenshot of the resulting visualization:

![resolution](https://github.com/user-attachments/assets/ba8157bc-58fa-47c5-8d00-058c7f316c52)

- Insight

This analysis indicates that a substantial portion of cases, 3.6k, have been successfully "Resolved." This suggests an efficient and effective resolution process within the organization. However, the presence of 1.4k cases marked as "Not Resolved" highlights the need for improvement in handling specific customer issues.


 ## Top agent who answered highest call:
 
 To compute the top agent who answered highest call, I initiated the process by selecting the "Card" option within the "Build Visual" section of the visualization menu. Next, I dragged the "Agent" column into the "Fields" section. Then, I clicked on filter type to choose Top N on "filter" section and chose and also type 1 on show items  Below is a screenshot of the resulting visualization:

 ![highest call](https://github.com/user-attachments/assets/279401b5-6396-4913-9401-faeb98cb8007)



 ## Total call by topic:

 To determine the total call by topic, I utilized a column chart. Firstly, I positioned the "total call which i calculated with new measure" on the y-axis and applied "topic column" to catagory. Below is a screenshot illustrating the resulting visualization.

 ![total cal by topic](https://github.com/user-attachments/assets/bc31ad40-4e3d-4b48-abf2-2fc5aaa01104)


 ## Duration of calls by every agent:

 To determine the total call by topic, I utilized a stacked bar chart. Firstly, I positioned the "Duration column " and applied "Agent column" 
 Below is a screenshot illustrating the resulting visualization.
 
  ![Sum of duration by agent](https://github.com/user-attachments/assets/f811e01d-e3bd-4fcf-989c-f2ffefa996d1)


## Dashboard :

This dashboard is created to visually depict and present all pertinent Key Performance Indicators (KPIs) and metrics within the dataset


![Call performance report](https://github.com/user-attachments/assets/161acdb4-0391-4053-8d5c-c535a8b7a17c)


Recommendation and conclusion:

Reviewing recurrent cases in this analysis, support teams should trained for complex issues. Streamlining processes for quicker resolution, collecting feedback from unresolved cases, and maintaining quality checks are essential. Additionally, prioritize response time reduction, critical call handling, and support team training. Implement a feedback system to address unanswered calls and enhance satisfaction, with a focus on improving "Admin Support" and "Contract related" areas.







