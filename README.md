# ML_for_binary_classification
This project aims to compare the performance of a set machine learning algorithims on binary classification.
The objective for each model is to be detect if a weblink is safe or malicious based on a set of parameters (11 in total).
The algorithims used here are LogisticRegression, Multinomial Bias, Support Vector classifcation, Decision Tree and the XGB Classification Models.
The project is split into 3 main parts namely Data Analysis, model developmenr & feature engineering for evaluation data(ie extractingg the numerical pararmeters from the string weblink).
Notable Libraries used were Pandas, Seaborn & Scikit-Learn(for loading the ml algorithims) other libraries include opendatasets,string & whois api.
The Dataset used for this project is sourced from kaggle and is made up of 96000 weblinks and using aforementioned parameters the weblinks are classed into either safe(1)  or harmful(0) based on.
The project was made on a GPU powered Deep Note IDE.
