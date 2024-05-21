# AML detection



## Project Overview
There is a lack of public available datasets on financial services and specially in the emerging mobile money transactions domain. Financial datasets are important to many researchers and in particular to us performing research in the domain of fraud detection. Part of the problem is the intrinsically private nature of financial transactions, that leads to no publicly available datasets.


## Data Overview
PaySim simulates mobile money transactions based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country. The original logs were provided by a multinational company, who is the provider of the mobile financial service which is currently running in more than 14 countries all around the world.

This synthetic dataset is scaled down 1/4 of the original dataset and it is created just for Kaggle.



## Key Features 
id: Unique identifier for each transaction
Amount: The transaction amount
isFraud: Binary label indicating whether the transaction is fraudulent (1) or not (0)

## Model Results

We checked the ROC curve

- Linear Kernel SVM = AUC 0.96

## Dataset
https://www.kaggle.com/datasets/ealaxi/paysim1