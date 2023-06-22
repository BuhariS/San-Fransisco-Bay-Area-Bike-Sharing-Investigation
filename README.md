# Investigation of the factors affecting the biking duration in San Fransisco Bay Area Bike Sharing Scheme

<img src="bike.jpg" alt="Bike Sharing" style="max-width: 100%;">

## Overview
A bicycle-sharing system, bike share program,public bicycle scheme, or public bike share (PBS) scheme, is a shared transport service where bicycles are available for shared use to individuals on a short-term basis at low or zero cost. It was initiated to as way to promote bicycles as a non-polluting form of transportation — and bike-lease businesses. [see](https://en.wikipedia.org/wiki/Bicycle-sharing_system)

The systems themselves include both docking and dockless systems, where docking systems allow users to borrow a bike from a dock, i.e., a technology-enabled bicycle rack and return at another node or dock within the system — and dockless systems offer a node-free system relying on smart technology. In either format, systems may incorporate smartphone web mapping to locate available bikes and docks.[see](https://en.wikipedia.org/wiki/Bicycle-sharing_system)


## Method

### Data
In this project, I analyse the bike sharing datasets of San Fransisco Bay Area for the [first quarter of 2019](https://s3.amazonaws.com/fordgobike-data/index.html) to find the factors affecting biking durations. 

### Data Wrangling
The dataset is distributed in four different files with each file showing the data for a month. These files were merged together and missing values and outliers were taken care of for quality analysis.

### Feature engineering and analyses
I extracted only the features of interest, engineered new ones and explored their distributions with histograms and column charts. I then check the relationships between the variables of interest using scatter plots and heat maps. I also studied how other variables like age, hour, user type, and gender can affect the biking durations using multivariate plots. 

### Files
Two files, namely: Part_I_exploration and Part_II_explanation were produced in this project. The Part_I_exploration shows the exploratory data analyses and Part_II_explanation communicates the key findings.

**Note**: Part_II_explanation is a slide in HTML which can be viewed in a web browser.

## Findings

Key findings from the analysis include:

1. Peak Hours: The busiest hours for biking are typically around 8 AM and 5 PM, indicating that a significant portion of riders are likely 9-5 workers.

2. Daytime Rides: The majority of rides occur during the daytime, suggesting that biking is more common during daylight hours.

3. Gender Distribution: Across different hours of the day, the proportion of different genders sharing bikes is relatively equal, indicating a balanced gender participation in bike rides.

4. Long Rides in the Evening: A considerable number of riders who took rides between 3:00 PM and 2:00 AM ended up spending close to a full day before returning the bike, indicating potential overnight rentals or extended usage.

5. Short Rides in Early Morning: Rides between 3:00 AM and 6:00 AM rarely exceed a duration of 15 hours, indicating shorter rides during these early morning hours.

6. Biking Duration by Gender: Most rides by individuals of the "other" gender tend to be shorter, lasting less than an hour, compared to rides by other genders.

7. Age and Duration: Riders above 60 years of age and teenagers are less likely to engage in longer bike rides, while individuals in the age range of 20-40 tend to have longer durations.

8. User Type and Duration: The analysis suggests that user type does not significantly impact biking duration, implying that both customers and subscribers have similar ride durations.
