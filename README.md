# US Wildfires and Data Breaches
--- 

# Premise:
Looking at wildfire occurrences across the continental United States between the years 2008 and 2014:
* H<sub>o</sub>: 
  When wildfires occur in a specific state, there is no change in data breaches within that state.
* H<sub>A</sub>: 
  When wildfires occur in a specific state, there is an increase in data breaches within that state.

	

# Questions Answered:

**How did you decide on your hypothesis?**
* We initially decided to explore the relationship between natural disasters and cyber crime, but after starting the research process, we quickly realized that these topics were extremely broad in nature, so we would need to significantly narrow the scope of each of these in order find consistent data to analyze and to scientifically measure our results. So we decided to narrow 'cyber crime' down to 'cyber data breaches' and narrow 'natural disasters' down to 'wildfires'. We also narrowed the date range down to years 2008-2014 and narrowed the geographic area to the continental US. 

    
**How is data breach defined?**
* Per the data set we used, 'data breach' is defined an incident where secured information is stolen, taken, or exposed from a system without the knowledge and/or authorization of the system's owner. This includes breaches of both virtual and physical nature from both internal and external points of access.
    
**What data did you use and how did you find it?**
* For our data sources, we used both Kaggle and APIs. For our cyber crime data, we found a data set on cyber data breaches on Kaggle. For the wildfire data, we use the FEMA open API to pull data on wildfires.
    
**What was your data clean up process?**
* To clean the data, we had to initially look through the data to familiarize ourselves with the actual content of the data, and then find common parameters in each data set that were relevant to our study, which included the state and the date of each event in each data set. 
    
**How did you decide what information to focus on?**
* In order to narrow down the scope of our analysis to be scientifically measurable, we decided to mainly focus on the state and the date of each event. Both the cyber data breach data set and the wildfire data set contained these two attributes for each event listed. 
    


### Team Members:
* Pramod 
* Lindsey
* Juan
* Emerald
* Nader

### Datasets Used:

Cyber Security Breaches Data (kaggle)
https://www.kaggle.com/alukosayoenoch/cyber-security-breaches-data?select=Cyber+Security+Breaches.csv

FEMA Data Sets on Disaster Information
https://www.fema.gov/about/openfema/api
