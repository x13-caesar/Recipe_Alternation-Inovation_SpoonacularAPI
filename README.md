# Recipe_Alternation-Inovation_SpoonacularAPI
International Recipe Alternation and Innovation Based on Dietary Needs and Food Availability with NLP

##PROJECT TITLE
International Recipe Alternation and Innovation Based on Dietary Needs and Food Availability with NLP

##ABSTRACT 
Analyzing the similarity and substitutability across various cuisines is beneficial to both diners and food operators. In this project, we propose quantitative deep learning approaches to recipes to find out if there are alternative options for some ingredients. We would like to alter some ingredients to take into account different dietary needs and/or food-availability while trying to retain its authentic taste in terms of texture and flavor. This work requires an understanding of how ingredients are paired within each cuisine. We will explore whether there is a universal or cuisine-specific rule on which ingredients go or against each other.  Our work is based on a real-world dataset scraped off some major recipe websites such as BBC Food and Epicurious. We will also obtain information on nutrition values from USDA. We will address two challenges associated with our task: transforming the recipes from text form to numeric data, and the choice of appropriate deep learning algorithm. Our experimental results would be able to serve as an effective tool for recipe design and alteration. 

###Detailed analysis includes:
Cuisine similarities using clustering techniques
Most prominent ingredients in each cuisine/cluster
Which ingredients always and never go to together within and cross cuisines

##DATASET DESCRIPTION
We will obtain data mainly through scraping off two websites: BBC Food and Epicurious. Both of the sites has cuisine tags. We will organize the information into a dataframe and saved in a CSV file. To obtain information on the nutrition values of each ingredient, we will use USDA API.

###Some necessary information we want to include but not limited to are:
`Cuisine`: cuisine types
`ingredients` string of  ingredients with quantity amount
`instructions`: a string of detailed instructions
`prep time`: minimum food prep time 
`total time`: include cooking time
`cooking process`: extract verbs that provide information that indicates how food is cooked
`kitchenware` 
`serving size`
`total calories`: total calories counts of the recipe based on ingredients
`nutrition`: nutrition values 


##LEARNING TOOLS
Python

###NLP METHODS
Data Acquisition
Web scraping using BeautifulSoup
API
Preprocessing Unstructured Data
Regular expression
Stop words removal
Entity Extraction
Stemming
Tokenization
Analysis and Modeling
BOW model
WordCloud to visualize commonly used ingredients of each cuisine 
Word2vec to learn similarities 
LDA to study ingredient pairing
Others 

