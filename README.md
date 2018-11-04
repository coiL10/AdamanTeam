# Impacts of Globalization on Food 

# Abstract
With the fast growth and democratization of transports, the food we eat everyday no longer depends on the local production but tends to come from various parts of the globe. Using the Open Food Facts Dataset, our goal is to discover and analyze the various impacts of this food globalization. Our project will mainly focus on important actual issues regarding its ecological and health aspects. We will first get more insights about the food transportation process, about its origin and destination and the ecological footprint of this transportation. We will then get to find how food affects our health by comparing the food consumption of countries to their global health indicators and look for the effects of this uniformization of food consumption.

# Research questions
# Milestone 1
- Which countries are the highest exporters and importers and is there a relationship with the GDP?
- How does the transport and production of food affect the ecosystem?
- How does the food we eat affect our Life expectancy? 

# Dataset
We want to use the Open Food Facts database dataset. This dataset provides different tags that will help us to classify countries into exporters and importers depending on the food. The main tags we will use are the "origins of ingredients", "place of manufacture", "countries where the product is sold" and "store where the product is purchased". This will help us to perform some estimations on the travelled distance of the food. This dataset also provides the Nutricient Score per country and the different ingredients and nutrition facts per food. If relevant, we will also look into the carbon footprint. Some of the products if not all of them from this dataset are provided in CSV format so we can use Pandas to read them. If it becomes necessary this dataset is also provided in JSON format.
In addition, we want to use statistics from the World Health Organization (WHO) in order to relate the Gross Domestic Product (GDP), the Life Expectancy or other values with our data.

# A list of internal milestones up until project milestone 2
Week 1 (9 Nov)

- Access to the database from the cluster.
- Create table with Life expectancy per country based on the WHO

Week 2 (16 Nov)

- Create table with the positions of countries for distance estimation.
- Relate Nutricient Score to Average Life expectancy per country
- Analyze the most popular types of food

Week 3 (23 Nov)

- Create the dataframe and clean the dataset

# Questions for TAa
- Is it okay to use some statistics from the WHO in project ?
