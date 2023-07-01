# Investigation of the factors affecting the biking duration in San Francisco Bay Area Bike Sharing Scheme

<img src="bike.jpg" alt="Bike Sharing" style="max-width: 100%;">

## Overview
A bicycle-sharing system or public bike share (PBS) scheme, is a shared transport service where bicycles are available for shared use to individuals on a short-term basis at low or zero cost. It was initiated as way to promote bicycles as a non-polluting form of transportation. [see](https://en.wikipedia.org/wiki/Bicycle-sharing_system)

The systems themselves include both docking and dockless systems, where docking systems allow users to borrow a bike from a dock, i.e., a technology-enabled bicycle rack and return at another node or dock within the system — and dockless systems offer a node-free system relying on smart technology. In either format, systems may incorporate smartphone web mapping to locate available bikes and docks.[see](https://en.wikipedia.org/wiki/Bicycle-sharing_system)

In this project, we gleaned valuable insights into bike sharing patterns and user behaviours. By examining various factors such as ride duration, user age, gender, and user type, we uncovered trends, correlations, and patterns within the dataset. Through visualizations and statistical analysis, we explored the impact of these variables on bike usage and identify key factors that influence biking behaviours. The outcomes of this project will provide valuable information for the bike sharing company to optimize their resources, understand user preferences, tailor marketing strategies, and enhance the overall biking experience.

### Data Description
In this project, I analyse the bike sharing datasets of San Fransisco Bay Area for the [first quarter of 2019](https://s3.amazonaws.com/fordgobike-data/index.html).

### Dependencies
To run this project successfully, one needs to install and import the following dependencies:
- [NumPy](https://numpy.org)
- [Pandas](https://pandas.pydata.org)
- [Seaborn](https://seaborn.pydata.org)
- [Matplotlib](https://matplotlib.org)

## Data Wrangling and Feature Engineering
The dataset for this project consists of four separate files, each representing data for a specific month. These files have been merged together to create a unified dataset. In order to ensure data quality, missing values and outliers have been addressed through careful analysis and appropriate treatments. 
After merging the dataset, I focused on extracting only the features that are relevant to our analysis. Additionally, I performed feature engineering to create new variables that could provide deeper insights into the bike sharing data. 

## Exploratory Data Analysis
During the exploratory data analysis (EDA) phase, I employed various visualizations to gain a deeper understanding of the dataset. By utilizing histograms and column charts, I examined the distributions of the variables, allowing me to identify any notable patterns or trends. Additionally, I explored the relationships between the variables of interest by employing scatter plots and heat maps, uncovering any potential correlations or dependencies. Furthermore, I delved into the impact of other variables, such as age, hour, user type, and gender, on biking durations through the use of insightful multivariate plots. This comprehensive analysis provided valuable insights into the dataset, enabling me to draw meaningful conclusions and make informed decisions based on the observed patterns and relationships.


## Conclusions

Key findings from the analysis include:

1. Peak Hours: The busiest hours for biking are typically around 8 AM and 5 PM, indicating that a significant portion of riders are likely 9-5 workers.
2. Daytime Rides: The majority of rides occur during the daytime, suggesting that biking is more common during daylight hours.
3. Gender Distribution: Across different hours of the day, the proportion of different genders sharing bikes is relatively equal, indicating a balanced gender participation in bike rides.
4. Long Rides in the Evening: A considerable number of riders who took rides between 3:00 PM and 2:00 AM ended up spending close to a full day before returning the bike, indicating potential overnight rentals or extended usage.
5. Short Rides in Early Morning: Rides between 3:00 AM and 6:00 AM rarely exceed a duration of 15 hours, indicating shorter rides during these early morning hours.
6. Biking Duration by Gender: Most rides by individuals of the "other" gender tend to be shorter, lasting less than an hour, compared to rides by other genders.
7. Age and Duration: Riders above 60 years of age and teenagers are less likely to engage in longer bike rides, while individuals in the age range of 20-40 tend to have longer durations.
8. User Type and Duration: The analysis suggests that user type does not significantly impact biking duration, implying that both customers and subscribers have similar ride durations.

These findings provide valuable insights into the biking patterns and behaviour of riders, which can be used by the bike-sharing company to optimize their services, improve resource allocation during peak hours, and tailor marketing strategies to different demographics.

## License 
The project is licensed under the MIT License.
