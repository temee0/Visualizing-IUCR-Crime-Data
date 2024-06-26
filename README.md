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
      
You can interact with the report [here](https://drive.google.com/file/d/1056X5TvWRvZHeRB6buDS7v-_wdq19rKy/view?usp=drivesdk)

## Page Navigation
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/navigation%20panel.jpg)    
**CTrl + click to use navigation panel**

## General Crimes
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/general%20crimes.jpg)
Between 2001 and the present, a total of **1,048,575** crimes were committed under the Illinois Uniform Crime Reporting (IUCR) system.

- **Arrests**: Only 27% of these cases resulted in an arrest, with a total of **281,225** arrests made.
- **Domestic Cases**: 17% of these cases were domestic in nature, amounting to **174,533** incidents.
- **Historical Trends**: Crime was at an all-time high in 2001 and 2002, with total counts of **484,154** and **382,497** respectively. In 2003, there was a **99.39%** drop in crime rates, and the rates remained relatively stable until 2023, when a **2000%** increase was observed. The current count for 2024 stands at **69,547**.
- **Offense Types**: There are **33** distinct primary types of offenses in the IUCR dataset. Theft is the most prevalent crime, followed closely by Battery, Criminal Damage, Narcotics, and Assault. The least common offenses include Domestic Violence, Non-Criminal Offenses, Human Trafficking, Ritualism, and Other Narcotic Violations.
- **Crime Locations**: The top locations for overall crimes are streets, residences, apartments, and sidewalks. The least common locations for crimes are loading docks, lagoons, funeral parlors, and junkyards.

## Child-Related Crimes
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/child-related%20crimes.jpg)
Between 2001 and the present, a total of **34,292** child-related crimes (crimes committed by minors or against minors) were recorded under IUCR.

- **Arrests**: **30%** of these cases resulted in an arrest, with a total of **10,118** arrests made.
- **Domestic Cases**: Only **10%** of these cases were domestic, with a total count of **3,523**.
- **Historical Trends**: Child-related crimes were at an all-time high in 2001 and 2002, with total counts of **16,737** and **13,233** respectively. In 2003, there was a **99.89%** drop in crime, which remained very low before experiencing a significant increase of **1400%** in 2023, and the current count for 2024 stands at **1,715**.
- **Offense Types**: Battery was the most prevalent crime under child-related crimes, followed closely by Assault, Offenses Involving Children, Theft, and Liquor Law Violations. The least common offenses include Prostitution, Interference with Public Officer, Obscenity, Homicide, and Stalking.
- **Crime Locations**: The top locations for child-related crimes are schools, residences, apartments, and streets. The least common locations for child-related crimes are airport buildings (non-terminal), savings and loan institutions, appliance stores, athletic clubs, and movie theaters.

## Sex Crimes
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/sex%20crimes.jpg)
Between 2001 and the present, a total of **23,988** sex crimes were recorded under IUCR.

- **Arrests**: **61%** of these cases resulted in an arrest, with a total of **14,550** arrests made.
- **Domestic Cases**: Only **11%** of these cases were domestic, with a total count of **2,630**.
- **Historical Trends**: Sex crimes were at an all-time high in 2001 and 2002, with total counts of **11,172** and **8,798** respectively. In 2003, there was a **99.60%** drop in crime. This drop lasted until 2007, when the sex crime count started on an upward trend and had a significant surge in 2023, with sex crimes increasing by **450%**. The current count for 2024 stands at **1,026**.
- **Offense Types**: There are six distinct primary types of offenses under this subcategory. The most prevalent of these offenses is Prostitution, with a total count of **11,172**, and the least occurring is Human Trafficking, with just **5** cases reported.
- **Crime Locations**: The top locations for sex crimes are streets, residences, apartments, and sidewalks, while the least common locations for sex crimes are airports, boats/watercraft, and appliance stores.

## Homicides
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/homicides.jpg)
Between 2001 and the present, a total of **13,087** homicides were recorded under IUCR.

- **Arrests**: **47%** of these cases resulted in an arrest, with a total of **6,181** arrests made.
- **Domestic Cases**: Only **7%** of these cases were domestic, with a total count of **907**.
- **Historical Trends**: The total count of homicides was **667** in 2001 and dropped by **25%** in 2004. It made little change or movement until 2016 when it increased by 59% and reached an all-time high in 2021, where the count went up to **806**. The current count of homicides is **136**, which is a **78%** drop from the previous year.
- **Offense Types**: There is only one primary type of offense under this subsector: homicide, which is described in two ways: First Degree Murder and Reckless Homicide. The most prevalent is First Degree Murder, accounting for **99.97%** of cases, with a total count of **13,083** cases. Reckless Homicide has just **4** cases reported.
- **Crime Locations**: The top locations for homicides are streets, autos, apartments, alleys, and houses. The least common locations for homicides are loading docks, lagoons, laundromats, funeral parlors, and beaches.

## Word Cloud of Offense Descriptions
![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/word-cloud%20(3).jpeg)
**The following word cloud represents the frequency of words found in the offense descriptions within the dataset. The size of each word is proportional to its frequency of occurrence; larger words appeared more frequently than smaller ones.**

## Conclusion
Although crime rate dropped in 2003, and stayed stable, which can be accounted for other crimes not reported but since 2023 crime has also increased and is skyrocketing similarly to early 2000s, this can be due to the current economy situation and other systemic issues. Additionally, it is crucial to differentiate between trends in overall crime rates and specific categories such as homicides. The homicide rate has increased significantly in recent years and, although it is at an all-time low in 2024, the year is not yet over, and there may still be changes in the coming months.

This report has highlighted a significant disparity between the number of arrests and the number of crimes committed. For example, the percentage of arrests made in theft cases is **14%**, in burglary and criminal damage cases it is **7%**, in burglary cases alone it is **9%**, in criminal sexual assault cases it is **18%**, and in kidnapping cases it is **12%**. 

In response to the recent increase in crime rates, the number of domestic cases has also risen.

The most common location for overall crimes and other subsections is the street, except in child-related crimes, where the top location is school. Other common locations for crimes include residences, apartments, and sidewalks. However, in the homicide subsection, residences and sidewalks do not rank among the top ten locations.

## Recommendation
In response to the findings outlined in this analysis, I propose a multifaceted approach to address the recent surge in crime rates and the observed disparities in arrest counts. First and foremost, there is a pressing need to increase law enforcement efforts. This entails enhancing police presence and surveillance in areas identified as high-crime zones, particularly on streets, in residential areas, apartments, and sidewalks. By enhancing visibility and proactive policing strategies, we aim to deter criminal activities and improve arrest rates.

Moreover, targeted intervention programs are essential to tackle the root causes of the escalating homicide rates and other violent crimes. These programs should encompass community outreach initiatives, conflict resolution training, and support services tailored to at-risk individuals. By addressing underlying socio-economic factors contributing to criminal behavior, we can work towards long-term crime prevention.

Additionally, there is a critical need to streamline crime reporting mechanisms and enhance response protocols. Timely and accurate data collection is pivotal in facilitating effective law enforcement responses and resource allocation. Strengthening community-police partnerships is equally vital. By fostering trust and collaboration through neighborhood watch programs, community policing initiatives, and public safety campaigns, we can empower communities to play an active role in crime prevention efforts.

Given the notable increase in domestic cases amid the overall rise in crime rates, it is imperative to prioritize support services for victims of domestic violence. This includes the provision of shelters, counseling, and legal aid. Furthermore, specialized training for law enforcement officers is important in handling sensitive cases such as domestic violence and sexual assault with empathy and expertise.

Advocating for policy reforms is also imperative in addressing systemic issues underlying crime, including poverty, unemployment, and inadequate education. Comprehensive social policies aimed at improving living conditions and socioeconomic opportunities can yield sustainable reductions in crime rates over time.

In conclusion, by implementing these recommendations comprehensively, we endeavor to curb the upward trend in crime rates and foster a safer and more secure environment for all members of the community.

---

![](https://github.com/temee0/Visualizing-IUCR-Crime-Data/blob/main/thank%20youuuu.jpg)  
#### Thank you for taking the time to read through this report.






