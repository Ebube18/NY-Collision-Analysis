# NY-Collision-Analysis

![Intro image](https://github.com/user-attachments/assets/fd01f8b0-6d46-4115-b6be-f1b719935d41)

## Introduction
This is a power BI project on analysis of accidents that ocuured within a city.

The aim of the project is to analyze, reveal patterns and drive insight to answer crucial questions and help the reduce rate of future accidents.

**_Disclaimer_**:_All dataset and report do not represent any company, institution or country, but just a dummy dataset to demonstrate capabilities of Power BI._

## Problem statement
1. Compare the % of total accidents by month. Do you notice any seasonal patterns?
2. Break down accident frequency by day of week and hour of day. Based on this data, when do accidents occur most frequently?
3. On which particular street were the most accidents reported? What does that represent as a % of all reported accidents?
4. What was the most common contributing factor for the accidents reported in this sample. What about fatal accidents specifically?

## Skills and concepts demonstrated
The following power BI features were incorporated:
- Power query
- DAX
- Modelling
- Visualization
## Data Transformation and cleaning
Created dimension tables and fact table for easy data modelling, find and replace, fill down, added conditional column

![NY collision conditional column](https://github.com/user-attachments/assets/f4d07f2c-38dd-41c4-ab33-de50118532d3)

## Data Modelling

Automatically derived relationships were adjusted and replaced with the required relationship.

Auto model                        | Adjusted model
----------------------------------|----------------------------

![NYC Collision auto model](https://github.com/user-attachments/assets/a056e242-24e4-4e07-a8db-a8e3c2a327df) | ![NY collision adjusted model](https://github.com/user-attachments/assets/f8e3627f-843a-4896-bd50-2dc055c27e23)

There are 2 dimension and 1 fact tables and the dimension tables were joined to the fact table using the one-to-many relationship.

## Data Analysis and Visualization

![NY collision dashboard](https://github.com/user-attachments/assets/46d9f60a-dc01-4226-8af5-26f6bf13dfb8)

The highest percentage of accident happened in June 2021 and June 2022. There was no record for June in 2023.

Accidents occur most frequently on the 4th day of the week at 4.00pm

Most accidents were reported on Belt Parkway with a percentage of 1.56%

The most contributing factor was not recorded but right behind that is the Driver inattention/distraction, and then Failure to yield right-of-way. While the most contributing factor for fatal accidents specifically is also unspecified, followed by unsafe speed and then driver inattention/distraction.

## Conclusion/Recommendation

The most accidents happened in June 2021 and June 2022, but no record for June in 2023. We could say that there is a seasonal pattern, but I will recommend a complete record of collisions in 2023 and 2024 for better analysis and a more accurate result on the pattern.

Thank you

![conc  image](https://github.com/user-attachments/assets/88613253-e87d-4301-be30-a7ebf99fd4bf)

