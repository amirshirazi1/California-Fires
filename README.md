# Final Project - Part One
A shared repository for our final project_part one

## Presentation

#### Selected Topic 

We will be analyzing California wildfire risk, specifically what factors contribute to a wildfire being classified as a major fire event. Cal Fire defines a major fire event as an extended-day wildfire that is 10 acres or greater. By utilizing historical California wildfire, housing and environmental conditions datasets, we hope to identify the factors that most commonly increase the risk of a wildfire becoming a major fire event.

#### Reason why they selected topic

California has recently had some of the most deadly and destructive fire seasons. With the state entering an extreme drought, the 2021 fire season is expected to be very high risk. With this analysis, main contributing factors will be identified and resources can be allocated to decrease the risk of major wildfire events in California regions. 

#### Description of their source of data

All datasets are from Kaggle 

**California Wildfires (2013-2020)**
- The dataset contains the list of wildfires that have occurred in California between 2013-2020. The dataset includes the location of the fire, including county and latitude and longitude. Several values are included for each fire, some of which are acres burned, fuel type and if the fire was considered a major fire event.  

**California Housing Data**
- The California housing data include location, population size of the block, house value and median income.

**California Environmental Conditions Dataset**
- The California Environmental Conditions dataset was pulled from the CIMIS weather stations and includes weather information organized by region. Data includes precipitation, air temperature relative humidity and wind speed. 

#### Questions they hope to answer with the data

1) What factors contribute to certain California fires becoming a major fire event? 
2) Which factor(s) are main contributors to increasing the risk of a California fire becoming a major fire event?

#### Technologies

UPDATE

## GitHub

#### Communication Protocols

1) Slack group chat will be used to share resources, ask questions and coordinate progress on deliverables.
2) The 7-9 pm PST workblock will be used for group working sessions
3) Main branch merge and weekly submissions will be coordinated by repository team member aligned with team established deadline.

#### Individual Branches & Commits (4)

## Machine Learning Model

### Purpose:
![Machine_Learning_Model](https://github.com/erinrkahn/project_one/blob/main/Images/Machine%20Learning%20Model%20Overview_Draft.png)
The purpose of this analysis is to analyze which factors from previous California (CA) wildfires made that wildfire into either a major wildfire or not. To perform this analysis, we will use the following features (X) in our supervised machine learning model to predict whether a wildfire was a major wildfire or not (y):
#### Environmental Factors
- Precipitation (in) in zip code
- Average vapor pressure (mBars) in zip code
- Maximum air temperature (F) in zip code
- Maximum relative humidity (%) in zip code
- Average wind speed (mph) in zip code
- Average soil temperature (F) in zip code
#### Region
- The zip codes in which wildfires started and occurred
- The proximity of that zip code to the ocean
#### Demographics
- Population of zip code
- Median income of zip code
- Median house value of zip code
#### Electricity
- Electricity consumption per zip code
#### Amount of Resources Allocated to Stop Fire
- Number of Air Tankers
- Number of Cal Fire Incidents
- Number of Dozers
- Number of Engines
- Fuel Type
- Number of Helicopters
- Number of Water Tenders
#### Time
- Year

Historically, high wind speed and dry heat contribute to the ignition and exacerbation of wildfires in CA. Therefore, inputting these environmental factors along with others into our supervised machine learning model will help predict whether a wildfire becomes a major wildfire or not.

Additionally, inputting zip codes where previous wildfires have started and occurred will help predict whether the wildfire was major or not. Also, inputting the proximity of these zip codes to the ocean will aid in this prediction as wildfires are typically inland.

Demographics of a region may also help in predicting wildfire outcomes such as the population of a zip code, median income of a zip code, and the median house value of a zip code.

Another interesting factor that may aid in predicting major wildfire risk is the electricity consumption per zip code.

Likewise, the amount of resources used to stop the fire such as the number of air tankers deployed and number of water tenders utilized will help predict whether the wildfire became a major wildfire or not.

Finally, the year that the wildfire occurred will help in predicting whether the wildfire became a major wildfire incident or not as the factors that contribute to wildfire risk like environmental factors may change over time to increase or decrease the likelihood of major wildfire incidents.

Ultimately, knowing these factors will give insight as to which California (CA) zip codes are more at risk of suffering from major wildfires and will guide future decisions in allocating more resources to zip codes where the likelihood of major wildfire risk is high.

### Description & Explanation of Model:

- **Which model did you choose and why?**
  - We chose a **supervised machine learning model** based on a **logistic regression model** because we want to predict whether a wildfire was a major wildfire or not.
- **How are you training your model?**
  - We are training our model on a **logistic regression model** because our output, y, is binary: major wildfire **or** not a major wildfire. 75% of our data will be training data, while the other 25% of our data will be testing data.
- **What is the model's accuracy?**
  - To be determined.
- **How does this model work?**
  - This supervised machine learning model will be built as a deep learning neural network because a deep learning neural network will learn and figure out relationships between the various variables. Likewise, it will be able to determine which input features are more significant in determining whether a wildfire becomes a major wildfire or not.

## Database

Provisional database that stands in for the final database.
- Sample data that mimics the expected final database structure or schema 
- Draft machine learning model is connected to the provisional database

#### Description & Explanation

- Create a document describing the schema of the database (this can be a markdown document or an ERD).
