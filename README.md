# Date created
09.09.2020
# Project title
Engaging customers through unsupervised and supervised learning
# Description
Using unspervised and supervised approaches to engage new and existing customers on customer and population demographics.
Find the related medium blogpost [here](https://jannis-j.medium.com/engaging-customers-through-unsupervised-and-supervised-learning-b2dfaf90f98f)
# Motivation
Acquiring new customers and engaging existing customers is a core activity for any business. In this project I am taking two approaches to support these activities with unsupervised and supervised machine learning to create a more efficient process that yields higher conversion.
# Data source
The data was supplied by a company supplying financial services. Since the data is confidential it is not provided in the repository.
# Results
The unsupervised clustering of population demographics yielded 12 nicely distributed clusters. The clustering on the customer data resulted in one main cluster within the customers which is a very good result to work with in a business context.

Among the supervised prediction of customer responses the support vector regression yielded a better average ROC score of 0.6248 compared to the ramdom forest regressor with 0.5895. Since it also trains faster it is the prefered method. The model achieved a score of 0.56572 in the [kaggle competition](https://www.kaggle.com/c/udacity-arvato-identify-customers/overview)
# Conclusion
The unsupervised clustering of customers worked very well as I was able to extract one main cluster that the customers belong to compared to the general population. This will enable the company to target new customers very well and drive conversion up.

The supervised prediction of which customers will respond to a campaign yielded mediocre results, but will already heavily improve the conversion in comparison to mailing all existing customers. Therefore it is a good first step in the right direction.
# Dependencies
matplotlib==3.3.3
numpy==1.19.3
pandas==1.1.3
scikit-learn==0.23.2
seaborn==0.11.0
sklearn==0.23.2
# Files
Arvato Project Workbook.ipynb - Jupyter notebook with the analysis
