# US Wildfires and Data Breaches
--- 

# Premise:
Looking at wildfire occurrences across the continental United States between the years 2008 and 2014:
* H<sub>o</sub>: 
  When wildfires occur in a specific state, there is no change in data breaches within that state.
* H<sub>A</sub>: 
  When wildfires occur in a specific state, there is an increase in data breaches within that state.
  
---
# How we got started:

**How did you decide on your hypothesis?**
* We initially decided to explore the relationship between natural disasters and cyber crime, but after starting the research process, we quickly realized that these topics were extremely broad in nature, so we would need to significantly narrow the scope of each of these in order find consistent data to analyze and to scientifically measure our results. So we decided to narrow 'cyber crime' down to 'cyber data breaches' and narrow 'natural disasters' down to 'wildfires'. We also narrowed the date range down to years 2008-2014 and narrowed the geographic area to the continental US. 

    
**How is data breach defined?**
* Per the data set we used, 'data breach' is defined as an incident where secured information is stolen, taken, or exposed from a system without the knowledge and/or authorization of the system's owner. This includes breaches of both virtual and physical nature from both internal and external points of access.
    
**What data did you use and how did you find it?**
* For our data sources, we used both Kaggle and APIs. For our cyber crime data, we found a data set on cyber data breaches on Kaggle. For the wildfire data, we use the FEMA open API to pull data on wildfires.
    
**What was your data clean up process?**
* To clean the data, we had to initially look through the data to familiarize ourselves with the actual content of the data, and then find common parameters in each data set that were relevant to our study, which included the state and the date of each event in each data set. 
    
**How did you decide what information to focus on?**
* In order to narrow down the scope of our analysis to be scientifically measurable, we decided to mainly focus on the state and the date of each event. Both the cyber data breach data set and the wildfire data set contained these two attributes for each event listed. 
    
---  
# What we found:

We accepted the null hypothisis according to this data set. With a Pval of 4.8E-53 we felt confident thsi was a reliable conclusion. After reviewing our plots we can visually observe this.
* The line chart shows that breach & fire counts per year generally moved in opposite directions.
* Our combo box plot demonstrates the data sets were distributed in opposite extremes.
* Our bar charts represent years and states with different highs and lows with little to no commonality.
We did find interesting information in our data:
* The pie chart shows a shocking majority of fires in Texas as compared to our expectation of California.
* Our line chart shows huge amounts of fire in 2011 compared to the year before.
---
# Limitations:

We felt with more time and resources we would have liked to . . .
* Gather more data from alternate sources on both sets to verify any unusual or extreme results were true.
* Performed deeper analysis on time delayed effects of fire on breaches.
* If there were effects of fires in one state on data breaches on another state. 
* Investigate for accuracy and data integrity on
	* Why did 2014 breach counts drop so drascially?
	* Why did 2011 have such a high fire rate compared to the previous and following years?
	* Why was Texas fire rate so disproportional to the other states?

---
### Team Members:
* Pramod - API Calls
* Lindsey - Data Clean-up
* Juan - Plotting
* Emerald - Data Isolation and Team Admin
* Nader - Data Clean-up and DF Builder

### Datasets Used:

Cyber Security Breaches Data (kaggle)
https://www.kaggle.com/alukosayoenoch/cyber-security-breaches-data?select=Cyber+Security+Breaches.csv

FEMA Data Sets on Disaster Information
https://www.fema.gov/about/openfema/api
