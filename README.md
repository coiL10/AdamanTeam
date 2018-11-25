# Impacts of Globalization on Food 

# Abstract
  With the fast growth and democratization of transports, the food we eat everyday no longer depends on the local production but tends to come from various parts of the globe. Using the Open Food Facts Dataset, our goal is to discover and analyze the various impacts of this food globalization.
  
  Our project will mainly focus on important actual issues regarding its ecological and health aspects. We will first get more insights about the food transportation process, about its origin and destination and the ecological footprint of this transportation. We will then get to find how food affects our health by comparing the food consumption of countries to their global health indicators and look for the effects of this uniformization of food consumption.

# Research questions
- How does the globalization impacts the food quality (based on a nutrition score) for countries like France or Switzerland ?
- How does the food we eat affect our Life expectancy ? 
- Is there a relationship between the wealth of a country and its food quality ?
- How much do the food travel before reaching the countries we study ?

# Dataset
  We want to use the Open Food Facts database dataset. This dataset provides different tags that will help us to classify countries into exporters and importers depending on the food. The main tags we will use are the "origins of ingredients", "place of manufacture", "countries where the product is sold". This will help us to perform some estimations on the travelled distance of the food. This dataset also provides the Nutricient Score per country and the different ingredients and nutrition facts per food, which we will use to quantify the nutritional quality of food.
  
  Some of the products if not all of them from this dataset are provided in CSV format so we can use Pandas to read them.
  
  In addition, we want to use statistics from the [World Bank](https://www.worldbank.org/) in order to relate the Gross Domestic Product (GDP), the Life Expectancy or other values with our data.

# External libraries
- Numpy
- Pandas
- GeoPy
(to be completed)

# A list of internal milestones up until project milestone 2
Week 1 (9 Nov)

- Access to the database from the cluster. - *We decided that pandas was enough to handle the data in its size*
- Create table with Life expectancy per country based on the WHO - *Finally found on World Bank, done*

Week 2 (16 Nov)

- Create table with the positions of countries for distance estimation. - *Library geopy will take care of the locations*
- Relate Nutricient Score to Average Life expectancy per country - *Done*
- Analyze the most popular types of food - *Decided it will not be useful*

Week 3 (23 Nov)

- Create the dataframe and clean the dataset - *Done
