# Food Delivery Analysis

## All about our project...
---
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on investigating the reasons why there is an increase in demand for online delivery in metropolitan cities such as Singapore. Our dataset is set in a metropolitan city in India, Bangalore. All walkthroughs will be on a single file. (Note: Separate run needed for different methods of NLP used. Details included in the file.)

## How to navigate through our project!
---
First and foremost, start by cloning our repository. After doing so, the third cell of our project notebook would contain the Table of Contents. Anchor tags for each segment of our project are inserted for easy access. To access, simply click on the segment you wish to browse (has to be done in the Jupyter Notebook environment). 

All our code should be executed sequentially, except for the portion on Natural Language Processing under section 5 of our project. As we have two different methods of doing NLP, if you have already executed section 5.1, which is our first method of NLP using NLTK and SkLearn's TFIDFVectorizer, skip section 5.2 and continue with section 6. If you wish to proceed with our second method of NLP using the pattern library, restart your kernel and execute sequentially again, skipping section 5.1 and execute from section 5.2 onwards.

For our SweetViz Visualisations and geographical maps, if you experience any trouble viewing the visualisations, you can either view it in our slides or from the files placed in our repository.  

## Contributors
---
- @jonathannghj - Data Resampling, Data Cleaning, Data Classification Modelling
- @DanielxDante - EDA, Natural Language Processing, Data Classification Modelling
- @ktnnm - EDA, Visualizations

## Problem Definition
---
- What are the optimal factors for a restaurant to attract consumers via food delivery service?
- Which model would be the best to predict it?

## Classification Models Used
---
- Logistic Regression
- K-Nearest Neighbours Classifier
- Random Forest
- XGBoost Classifier

## Conclusion
---
The top 3 things that customers look out for in food delivery services are (of decreasing impact):
- Ease and convinience of delivery
- Time saving services
- Services that have more offers and discounts 

Turns out that people value their time and money! :astonished:

The model that produces the best score would be the Random Forest Model. However, it is possible that the most optimal classification model would be the XGBoost classifier for reasons stated in our walkthrough.

## What did we learn from this project?
---
- Using gmaps API for Geographical Analysis
- Vizualisations using SweetViz 
- Natural Language Processing Techniques using NLTK, SkLearn's TFIDFVectorizer and Open Source Library Pattern
- Handling imbalanced datasets using resampling method SMOTE
- Logistic Regression, KNNeighbours, RandomForest Classification methods using sklearn
- XGBoost Classification API Usage
- Handling small datasets using Cross Validation Techniques
- Concepts about ROC-AUC, and F1 Score
- GitHub Collaboration



## References
---
- https://www.kaggle.com/code/rafjaa/resampling-strategies-for-imbalanced-datasets/notebook
- https://www.kaggle.com/code/onadegibert/sentiment-analysis-with-tfidf-and-random-forest/notebook
- https://intellipaat.com/community/14889/f1-score-vs-roc-auc#:~:text=In%20general%2C%20the%20ROC%20is,area%20under%20the%20ROC%20curve.
