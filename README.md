
# NCAA Signing Day to NFL Draft:

A data analysis project designed to measure the relationship between the player rating received as a highschool football player and the rating received when entering the NFL Draft. I took highschool football recruiting data from 2015 to 2023 and compared it with NFL Draft player rating data.

![Signing Day](image-2.png) ![NFL Draft](image-1.png)

## Questions:

1. How accurate are the High School Scouts ratings when compared to NFL Scouts?

2. Are there any trends with the outliers?

3. Do any college teams improve ratings at a higher rate? 

## The Data:

The data used in this project can be found here: [Datasource](https://collegefootballdata.com/exporter)

This data was downloaded by year and then combined. This was done for Recruiting Ranking and NFL Draft data.

## Data Dictionary:

| Field Name              | Data Type | Example Value |
| ----------------------- | --------- | ------------- |
| `CollegeAthleteId`      | float64   | 3917315.0     |
| `Name`                  | object    | Kyler Murray  |
| `Position`              | object    | Quarterback   |
| `College`               | object    | Oklahoma      |
| `HighSchoolRank`        | float64   | 0.9855        |
| `NflTeam`               | object    | Arizona       |
| `DraftYear`             | int64     | 2019          |
| `HometownInfoLatitude`  | float64   | 33.103174     |
| `HometownInfoLongitude` | float64   | -96.67055     |
| `Overall_Pick`          | int64     | 1             |
| `NFLPreDraftGrade`      | float64   | 90.0          |
| `ChangeInRating`        | float64   | -0.0855       |

## How to Run:

The project was created using Jupyter Notebook with a virtual environment in Visual Studio. The main project file '''Capstone.ipynb''' will contain all the code. There is a '''requirements.txt''' included in this repository to install all the packages needed to run this project on your own machine exactly as I have done.

## Visualizations:

I used tableau Public for my visualizations in order for the end-user to be able to interact with data. Those visualizations can be found here:
[Visualizations](https://public.tableau.com/app/profile/brandon.hines5364/viz/NCAAtoDraftDashboard/Dashboard1?publish=yes)

# Key Findings:

There are very few players that have a positive rating change, meaning they were underrated when entering college. This is what I expected but the average change is -0.2206, which I found to be interesting. I thought the rating change average would be closer to -0.10 -0.15. 

It was also interesting to compare schools with specific positions. There are schools like Ohio State University and University of Southern California, that are historically known to produce more wide receivers. The data I collected did not show that they produced the most receivers, but it did show on average to have a better change in rating. This "stereotyping" of schools held true. They might not have produced the most, but on average they produced a more consistant rated player.

Another thing I found interesting was looking at the data from specific colleges. The colleges that are ranked in the Top 10 every year are the ones that are on the average or below, except Alabama. However, your schools that are known to float in the Top 15-30 and have really good seasons periodically, produced players with a better than average rating change. 


