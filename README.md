# Food Recipe Alternation and Generation
*Based on Dietary Needs and Food Availability with NLP*

- Work by: **Yuran Pan, Qiangwen Xu**. 
- Based on: the course project of Fordham University CISC6210 Natural Language Processing. 


## Requirements

Before running our code, you need to make sure the environment has Python>=3.0 and all other required modules, which are listed in ***reqirements.txt***.  

Or you can simply run following command in the project directory:  
 
```
pip install -r requirements.txt
```

Then you can implement our models.

## Data
Our data is almost from [Spoonacular API](https://spoonacular.com/food-api). It provides various information about food, including the ingredients, instructions, and the nutritions and so on. 

We've already collected over 3000 recipes from it for you to train the models on. The raw dataset is saved as ***nlp_finalproj_data_withids.csv***. 

To convert some information into the frame our task need, we did some data cleaning and preprocessing work, then the processed data is saved as ***nlp_finalproj_data_preprocessed.csv***.  

The all data file paths in our code are written as: 

```
./data/...
```
If you want to use your own dataset, please make sure it has the frame this project demands, then change the file paths.


## Code Files  
All .ipynb files contains running log inside so that you can see the output without actual executing them. And all of them can be convert to .py file through python notebook editor like jupyter book, if you need.  

- ***NLP_FinalProj_Data.ipynb***: collecting data from spoonacular API. If you want to use our collected dataset or your own data, you don't need it.  
- ***NLP_final_PreProcessing.ipynb***: The data cleaning and preprocessing to raw datasets. If you want to use our collected dataset, you don't need to run it. The processed dataset is already there.
- ***nlp_finalProj_EDA.ipynb***: The EDA code showing some statistical information about the data.
- ***NLP_final_Word2Vec.ipynb***: Implementing word embedding models (skip-gram with negative samples) to the datasets. 
- ***nlp-recipe-generator-ngram.ipynb***: Recipe generator based on language model.
- ***nlp-finalproj-recipe-generator-wordbased.ipynb***: Recipe generator based on LSTM.


