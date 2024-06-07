# Understanding Crime Patterns in the US: A Visual Exploration of IUCR Data (2001-Present)
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/front_page.jpg)

## Introduction
This report is a meticulous examination of crimes cataloged under the **Illinois Uniform Crime Reporting (IUCR)** system, spanning from 2001 to the present day. The IUCR, a standardized method for classifying criminal offenses, offers a comprehensive framework for organizing and interpreting diverse criminal activities, providing invaluable insights into the evolving nature and patterns of crime over the years. Within this report, there are subsections derived from the main data that focus on child-related crimes, sex crimes, and homicides.

Structured Query Language (SQL) was utilized to understand the crime dynamics, thereby facilitating informed decision-making and targeted interventions. To further enhance our insights and analysis, I used PowerBI to bring the data to life through interactive and visually compelling dashboards. This combination of SQL and Power BI not only deepened our understanding of the crime trends but also allowed for more effective communication of my findings to end users.

## Problem Statement

#### 1. Total Crime Count
What is the total count of reported crimes?

#### 2. Overall Crime Trends and Trends in Specific Subsections
How have the overall count of crimes, as well as crimes in specific subsections, changed over the years?

#### 3. Most Common Types of Crime
What are the most prevalent types of crime?

#### 4. Crime Locations
What are the top locations for overall crime and crimes in specific subsections?
What are the least common locations for these crimes?

#### 5. Crime Offenses Breakdown
What are the primary types of offenses committed?
What specific descriptions are mostly associated with each primary type of offense?

#### 6. Domestic Cases
How many domestic cases have been reported in general and in specific subsections?
What are the trends in domestic cases over the years?

#### 7. Arrests and Prosecutions
How many arrests have been made?
What proportion of overall cases or cases in specific subsections resulted in arrests?

## Analysis Toolkits
### Structured Query Language (MySQL):
- Database creation
- Table creation
- Dataset Importation
- Data cleaning
- Data exploration
- Data analysis
### PowerBI:
- Dataset importation
- DAX
- Data modelling
- Visual tools
- Page navigation
- Bookmarks
- Buttons
- Filters
- Tooltips
  
## Modelling
Automatically derived relationships have been adjusted to remove or replace unwanted relationships with the required relationships.

![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/data%20model.jpg)

## Visualization
This report comprises of 4 pages 
- General crimes
- Child-Related Crimes
- Sex crimes
- Homicides
      
You can interact with the report [here]()

## General Crimes
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/general%20crimes.jpg)
- A total count of **1,048,575** crimes were committed under IUCR between 2001 till present.
- Only 27% of these cases resulted in an arrest, with a total count of **281,225** arrests made.
- 17% percent of these cases where domestic, with a total count of **174,533**.
- Crime was at an all time high in 2001 and 2002 with total count of **484,154** and **382,497** respectively. There was a **99.39%** drop in crime in 2003 and it there wasnt any major difference in the crime rate in the years to come until 2023 when a **2000%** increase in crime under the IUCR and it's presently at a total count of **69,547.**
- There are **33** distinct primary type of offenses in the IUCR dataset which can be seen in the report, Theft being the most prevalent crime, followed closely by Battery, Criminal damage, Narcotics and assualt in top 5 and domestic violence, non-criminal offense, human trafficking, ritualism, and other narcotic violations in bottom 5.
- the top locations for overall crimes are the streets, residence, apartments, and sidewalks. while the least common locations for crime are loading dock, lagoon, funeral parlor, and junkyards.

## Child-Related Crimes
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/child-related%20crimes.jpg)
- A total count of **34,292** chidl-related crimes(crimes committed by minors or against minors) were recorded under IUCR between 2001 till present.
- 30% of these cases resulted in an arrest, with a total count of **10,118** arrests made.
- Only 10% of these cases were domestic with a total count of **3523**.
- child relatd crimes were at an all time high in 2001 and 2002 with a total count of **16,737** and **13,233** respectively. There was a **99.89%** drop in crime in 2003 amd remained very low but has strted to see a spike in 2023 where crime rate increased by **1400%** and is presently at **1715.**
- Battery was the most prevalent crime under child_related crimes, followed closely by Assault, Offense involving children, Theft and Liqour law violation in top 5 and prostitution, interfernce with public officer, obscenity, homicide and stalking in bottom 5.
- The top locations for child-related crimes are schools, residence, apartment and streets. while the least common locations for child-related crimes are airport building non-terminal, saving and loan, appliance stores, athletic clubs and movie theaters.
  
## Sex Crimes
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/sex%20crimes.jpg)
- A total count of **23,988** sex crimes were recorded under IUCR between 2001 till present.
- 61% of these cases resulted in arrest, with a total count of **14,550** arrests made.
- only 11% of these cases were domestic with a total count of **2630**.
- sex crimes were at an all time high in 2001 and 2002 wiith a total count of **11,172** and **8798** respectively. there was a **99.60%** drop in crime in 2003, this drop lasted until 2007 when the sex crime count started on an upward trend and experienced a huge spike in 2023 when sex crimes increased by **450%** and is presently at **1026.**
- there are six distinct primary type of offenses under this subcategory. the most prevalent of these offenses is prostitution with a total count of **11,172** and the least occuring is human trafficking with just **5** cases reported.
- The top locations for sex crimes are streets, residence, apartment, and sidewalks, while the least common location for sex crimes are airports, boat/watercraft, and appliance stores
## Homicides
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/homicides.jpg)

