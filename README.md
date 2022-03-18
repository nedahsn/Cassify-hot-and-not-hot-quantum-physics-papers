# Cassify-hot-and-not-hot-quantum-physics-papers
In this project we work with a dateset on all papers published in quant-ph category on arXiv between 2012-01-01 and 2016-12-31 that had at least ten citations in SciRate.
The aim is to detect hot-topic quantum papers based on their citations. 
We first do EDA. 
We then do feature engineering including vectorization of the text features (abstract, title) to build our predictors for ML models.
We next bulid our binary categorical target by putting a threshold on citations to classify papers as hot and not-hot topics. 
We use two different techniques for text vectorization, word embedding in SpaCy and count vectorization.
We also use different ML models, Logistic Regression, SVM, Random Forest, and compare their performance using different classification metrics. 
We also find similar papers in the dataset to a given paper. 

See the dataset in https://www.kaggle.com/datasets/peterwittek/scirate-quant-ph?datasetId=609&sortBy=dateRun&tab=profile
