# LA_Crime_Prediction
![image](https://user-images.githubusercontent.com/59149638/184992096-70df0472-423b-478b-9070-6baef05df0e1.png)

<sub> Figure Source: [Link](https://digital.hbs.edu/platform-rctom/submission/machine-learning-at-predpol-risks-biases-and-opportunities-for-predictive-policing/) </sub>
## Project Description
In this project, we aimed to simulate the crime prediction tool used by the police, Predpol, to assess any existing bias in this tool. The project consists of the following steps:
1) We first implmeneted the epidemic type aftershock (ETAS) model that the PredPol patent is built on.
2) Using the training on LA geographical data from 2018 we did prediction in 2019. 
3) Then showed the proportions of Police Deployments among historically-redlined zones with different grades.  
4) Then Using our Predpol Simulation and Census Data, we calculate proportions of demographics that are policed when above different “risk” thresholds. Then, combining actual crime data from 2019 with the Predpol’s predictions, we determine the success rate of policing for different demographics.


## Data
The first dataset that we used for this project is the 2017, 2018, and 2019 Los Angeles County Sheriff’s Department’s records of federal crimes within their jurisdiction. Within this dataset, individual rows describe a single federal crime that occurred within the jurisdiction of Los Angeles County. Descriptors of the crimes include the date of the crime, the type of crime committed, the exact location of the crime in longitude, latitude, and address, and specific details about the crime.

For the Census Analysis, we used the American Community Survey (ACS) 2019 5-year count from the U.S. Census Bureau. Specifically, we selected a survey for Table B03002, which details Hispanic or Latino Origin by race. We also download it in terms of Census tracts in Los Angeles. We use this table to find distributions for White, Black, and Latina/o populations, used in our bias analysis section. 


## Results
Check out the project proposal [here](https://github.com/rojinbakhti/LA_Crime_Prediction/blob/main/Final%20Report.pdf) and the presentation [here](https://github.com/rojinbakhti/LA_Crime_Prediction/blob/main/Final%20Presentation.pdf).
