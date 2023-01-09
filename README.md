![SPP_Webpage](https://user-images.githubusercontent.com/105435209/211263828-9c89d33c-31dc-43a2-8295-8cee5a1c5ea5.jpeg)

# Shipment Pricing Prediction

### Problem Statement:
The market for supply chain analytics is expected to develop at a CAGR of 17.3 percent
from 2019 to 2024, more than doubling in size. This data demonstrates how supply
chain organizations are understanding the advantages of being able to predict what will
happen in the future with a decent degree of certainty. Supply chain leaders may usede
this data to address supply chain difficulties, cut costs, and enhance service levels all at
the same time.

The main goal is to predict the supply chain shipment pricing based on the available
factors in the dataset.




### Software And Tools Requirements
1. [Github Account](https://github.com)
2. [VSCodeIDE](https://code.visualstudio.com/)
3. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)


### Create a new environment

```
conda create -p venv python==3.7.6 -y
```
## Technical Aspects
The whole project has been divided into three parts. These are listed as follows :

• Data Preparation : This consists of storing our data into cassandra database and utilizing it, Data Cleaning, Feature Engineering, Feature Selection, EDA, etc.

• Model Development : In this step, we use the resultant data after the implementation of the previous step to cross validate our Machine Learning model and perform Hyperparameter optimization based on various performance metrics in order to make our model predict as accurate results as possible.

• Model Deployment : This step include creation of a front-end web application using Flask framework with Postman API by using our Pickled model file.
